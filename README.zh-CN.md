[中文](README.zh-CN.md) | [English](README.md)
# Awesome UAS List [![Awesome Lists](https://srv-cdn.himpfen.io/badges/awesome-lists/awesomelists-flat.svg)](https://github.com/awesomelistsio/awesome)
[![GitHub Sponsors](https://srv-cdn.himpfen.io/badges/github/github-flat.svg)](https://github.com) &nbsp; 
[![Ko-Fi](https://srv-cdn.himpfen.io/badges/kofi/kofi-flat.svg)](https://ko-fi.com) &nbsp; 
[![PayPal](https://srv-cdn.himpfen.io/badges/paypal/paypal-flat.svg)](https://www.paypal.com) &nbsp; 
[![X](https://srv-cdn.himpfen.io/badges/twitter/twitter-flat.svg)](https://x.com/) &nbsp; 
[![Facebook](https://srv-cdn.himpfen.io/badges/facebook-pages/facebook-pages-flat.svg)](https://www.facebook.com/)
# Awesome UAS List  

一份精选的 AI、机器学习、计算机视觉和自主控制资源清单，涵盖无人机系统（UAS）、四旋翼飞行器及空中机器人——包括导航、SLAM、飞控、路径规划、仿真与感知等方向。

## 软件
- [框架](#框架)
- [飞控固件](#飞控固件)
- [遥控器固件](#遥控器固件)
- [SDK 与函数库](#sdk-与函数库)
- [地面站](#地面站)
- [BlackBox](#blackbox)
## 工具与生态系统
- [学习资源](#学习资源)
- [SLAM 与状态估计](#slam-与状态估计)
- [计算机视觉](#计算机视觉)
- [仿真](#仿真)
- [数据集](#数据集)
- [机械结构](#机械结构)
- [电子设备](#电子设备)
- [服务](#服务)
### 硬件
- [遥控发射器](#遥控发射器)
- [无人机机架](#无人机机架)
- [头戴式显示器](#头戴式显示器)
- [视频接收器](#视频接收器)
- [电子设备与电机](#电子设备与电机)
- [摄像头](#摄像头)
### 产品与项目
- [无人机](#无人机)
- [无人地面车辆](#无人地面车辆)
- [无人水下航行器](#无人水下航行器)
### 其他
- [相关列表](#相关列表)
- [贡献](#贡献)
- [许可证](#许可证)
---

## 软件
### 框架
- [PX4 Autopilot](https://github.com/PX4/PX4-Autopilot) – 广泛使用的开源无人机飞控软件栈。
- [ArduPilot](https://github.com/ArduPilot/ardupilot) – 成熟稳定的无人机与自主车辆自动驾驶软件。
- [ROS (Robot Operating System)](https://github.com/ros/ros) – 用于无人机感知、规划与控制的标准机器人中间件。
- [ROS 2](https://github.com/ros2/ros2) – 面向分布式与实时系统的现代化机器人操作系统。
- [AirSim](https://github.com/microsoft/AirSim) – 面向无人机、机器人与自动驾驶系统的开源仿真平台。
- [DroneKit](https://github.com/dronekit/dronekit-python) – 基于 MAVLink 的 Python 无人机控制库，可用于控制兼容 MAVLink 的飞行器。
### 飞控固件
- [Ardupilot](https://github.com/ArduPilot/ardupilot)
- [BaseFlight](https://github.com/multiwii/baseflight) -
- [Betaflight](https://github.com/betaflight/betaflight) - Cleanflight 的分支。
- [ButterFlight](https://github.com/ButterFlight/butterflight) - Betaflight 的分支。专注于 Mini Quads 的固件。
- [Cleanflight](https://github.com/cleanflight/cleanflight) - BaseFlight 的分支。支持更多飞控并具有额外的 PID 控制器。
- [dRonin](https://dronin.org) - 面向 OpenPilot/Tau Labs 系列飞控的自动驾驶/飞控固件。
- [EmuFlight](https://github.com/emuflight/EmuFlight) – 专注于飞行性能、创新滤波、前沿功能扩展和广泛目标支持的飞控固件。
- [FalcoX](https://flightone.com/download.php?version=stable) - 原名 Raceflight one，现为 FlightOne。
- [INAV](https://github.com/iNavFlight/inav)
- [Kiss](https://www.flyduino.net/en_US/page/downloads) - KISS 飞控的固件。
- [LibrePilot](https://github.com/librepilot/LibrePilot) - (GitHub 分支已过时/不活跃)
- [madflight](https://github.com/qqqlab/madflight) – 适用于 Arduino ESP32 / RP2350 / RP2040 / STM32 的飞控。
- [Open Source Rover Control Code](https://github.com/nasa-jpl/osr-rover-code) – NASA JPL 开放漫游车的控制固件。
- [PX4 Autopilot](https://github.com/PX4/PX4-Autopilot) - 从固件重新品牌为 Autopilot
- [SilverWare](https://github.com/silver13/BoldClash-BWHOOP-B-03) - BoldClash BWHOOP B-03 迷你无人机的固件
- [SilverWare(NFE)](https://github.com/NotFastEnuf/NFE_Silverware) – 适用于 Alienwhoop ZER0、E011、BWHOOP B-03、H8mini 和 BETA FPV LITE 飞控的固件，包含 NotFastEnuf 设置和实验功能。
### 遥控器固件
- [FreedomTX](https://github.com/tbs-fpv/freedomtx) - 基于 OpenTX 的 TBS Tango 2 自定义固件。
- [OpenTX](http://www.open-tx.org/) – 高度可配置的 RC 无线电发射器开源固件。
- [EdgeTX](https://github.com/edgetx/edgetx) – R/C 无线电的尖端开源固件。
- [OpenVTx](https://github.com/OpenVTx/OpenVTx) – FPV 开源视频发射器固件。
- [OpenIPC](https://github.com/OpenIPC/firmware) – 来自开放社区的替代 IP 摄像头固件。
### SDK 与函数库
- [DJI Onboard SDK](https://github.com/dji-sdk/Onboard-SDK) – 通过串口（TTL UART）连接支持的 DJI 飞控。
- [GoBot](https://github.com/hybridgroup/gobot) – 面向机器人、无人机和物联网的 Go 语言框架。
- [Libcyphal](https://github.com/OpenCyphal-Garage/libcyphal) – Cyphal 协议栈的 C++ 便携式参考实现，适用于嵌入式系统和 Linux。原名 LibUAVCAN。
- [MAVLink](https://github.com/mavlink/mavlink) – 微飞行器消息编组库。
- [MAVSDK](https://github.com/mavlink/MAVSDK) – 通过 MAVLink 控制无人机的 API 集合。
- [MAVROS](https://github.com/mavlink/mavros) – 为支持 MAVLink 的飞控提供 ROS 接口。
- [UAV Toolbox (MATLAB)](https://www.mathworks.com/products/uav.html) – 用于无人机建模、仿真与控制设计的工具箱。
- [RotorS Simulator](https://github.com/ethz-asl/rotors_simulator) – 基于 ROS 的无人机控制与规划仿真框架。
- [ETHZ MPC Controllers](https://github.com/ethz-asl/mav_control_rw) – 面向四旋翼的模型预测控制器（MPC）。
### 地面站
- [QGroundControl](https://github.com/mavlink/qgroundcontrol) – 跨平台无人机地面站（Android、iOS、Mac OS、Linux、Windows）。
- [Arduleader](https://github.com/geeksville/arduleader) – 面向 Mavlink/Arduplane 的安卓地面控制器。
- [Tower](https://github.com/DroidPlanner/Tower) – 面向安卓设备的地面站。
- [MAVProxy](http://ardupilot.github.io/MAVProxy/) – 基于 MAVLink 的无人机地面站软件包。
- [Ardupilot Mission Planner](https://ardupilot.org/planner/index.html) – ArduPilot 开源自动驾驶项目的全功能地面站应用。
- [APM Planner 2](https://ardupilot.org/planner2/) – 面向基于 MAVlink 的自动驾驶仪（包括 APM 和 PX4/Pixhawk）的开源地面站应用，可在 Windows、Mac OSX 和 Linux 上运行。
- [ArduPilot Mission Planner](https://github.com/ArduPilot/MissionPlanner)
- [Paparazzi](http://wiki.paparazziuav.org/wiki/Main_Page)
- [QGroundControl](http://qgroundcontrol.com/)
### BlackBox
---

## 工具与生态系统
### 学习资源
- [MIT UAV Robotics Course](https://aeroastro.mit.edu/) – MIT 航空机器人课程与教学资料。
- [ETH Zurich Aerial Robotics](https://asl.ethz.ch/) – ETH 在无人机规划、控制与感知方面的领先研究。
- [UPenn GRASP Lab](https://www.grasp.upenn.edu/) – 涵盖无人机与自主系统的机器人研究。
- [Stanford Aerial Mobility](https://aa.stanford.edu/) – 斯坦福关于无人机与自主飞行的课程与研究。
- [PX4 Documentation](https://docs.px4.io/) – PX4 飞控、仿真与开发的完整文档。
- [ArduPilot Docs](https://ardupilot.org/) – ArduPilot 的配置与开发指南。
- [Flying Car and Autonomous Flight Engineer](https://eu.udacity.com/course/flying-car-nanodegree--nd787) – Udacity 飞行汽车与无人机机器人软件工程课程。
- [Robotics: Dynamics and Control](https://www.edx.org/course/robotics-dynamics-control-pennx-robo3x) – edX 机器人动力学与控制课程。
- [UAS/Drone Remote Pilot Test Prep for Part 107](https://www.udemy.com/remote-pilot-certificate-test-prep-for-part-107-exam/) – 无人机远程飞行员 Part 107 考试备考课程。
- [Drone Photography](https://www.udemy.com/course/dronephotography/) – 无人机摄影课程。
- [Drone Programming with Python](https://www.udemy.com/course/drone-programming-with-python-face-recognition-tracking/) – Python 无人机编程课程。
### SLAM 与状态估计
- [ORB-SLAM3](https://github.com/UZ-SLAMLab/ORB_SLAM3) – 先进的单目、双目与 RGB-D 视觉 SLAM 系统。
- [VINS-Fusion](https://github.com/HKUST-Aerial-Robotics/VINS-Fusion) – 面向空中机器人（UAV）的视觉惯性里程计。
- [OKVIS](https://github.com/ethz-asl/okvis) – 基于关键帧的视觉–惯性里程计。
- [RTabMap](https://github.com/introlab/rtabmap) – 基于外观的实时 SLAM 系统。
- [Kimera](https://github.com/MIT-SPARK/Kimera) – 具备 3D 网格重建能力的视觉–惯性 SLAM。
- [Drone-Satellite-Ground Three Platiform Localization](https://github.com/layumi/University1652-Baseline) – 无人机-卫星-地面三平台定位
- [ACM MM2023 Workshop: UAV in Multimedia](https://www.zdzheng.xyz/ACMMM2023Workshop/) – ACM MM2023 无人机多媒体工作坊
- [Visual Localization Leaderboard](https://github.com/layumi/University1652-Baseline/tree/master/State-of-the-art) – 视觉定位排行榜
### 计算机视觉
- [YOLOv8](https://github.com/ultralytics/ultralytics) – 适用于机载任务的实时目标检测模型。
- [OpenCV](https://github.com/opencv/opencv) – 计算机视觉与机载感知的核心库。
- [DeepSORT](https://github.com/nwojke/deep_sort) – 基于检测的目标跟踪框架，常用于无人机跟踪任务。
- [Detectron2](https://github.com/facebookresearch/detectron2) – 现代化的目标检测与分割框架。
- [FastSAM](https://github.com/CASIA-IVA-Lab/FastSAM) – 面向实时无人机任务的轻量级分割模型。
- [OpenMMLab](https://github.com/open-mmlab) – 完整的视觉算法栈，适用于无人机感知任务。
### 仿真
- [AirSim](https://github.com/microsoft/AirSim) – 具备真实感环境与无人机物理的仿真平台。
- [Gazebo](https://gazebosim.org/) – 广泛用于空地机器人仿真的通用模拟器。
- [NVIDIA Isaac Sim](https://developer.nvidia.com/isaac-sim) – 面向机器人与无人机的高保真仿真平台。
- [JMAVSim](https://github.com/PX4/jMAVSim) – PX4 使用的 Java 仿真器。
- [Unity ML-Agents](https://github.com/Unity-Technologies/ml-agents) – 基于 Unity 的强化学习与仿真框架。
- [Unreal Engine](https://www.unrealengine.com/) – 用于无人机仿真与合成数据生成的高真实度环境。
- [AirSim](https://github.com/Microsoft/AirSim) - 基于 Unreal Engine 的自动驾驶开源仿真器。
- [LiftOff](https://www.immersionrc.com/fpv-products/liftoff-drone-race-simulator/) - :dollar: FPV 竞速仿真器，具有逼真的 OSD（屏幕显示）体验。
- [Orqa FPV.SkyDive](https://skydive.orqafpv.com/) - Orqa FPV 的竞速和自由式仿真器。
- [RotorRush](http://rotorrush.com/) - :dollar: 原名 FPV Event。基于订阅的仿真器。
- [VelociDrone](https://www.velocidrone.com/) - :dollar: 多人对战 FPV 竞速仿真器。
### 数据集
- [EuRoC MAV Dataset](https://projects.asl.ethz.ch/datasets/doku.php?id=kmavvisualinertialdatasets) – 视觉–惯性导航基准数据集。
- [UAV123](https://cemse.kaust.edu.sa/ivul/uav123) – 用于无人机目标跟踪研究的视频数据集。
- [VisDrone](https://github.com/VisDrone/VisDrone-Dataset) – 基于无人机的检测、跟踪与分割数据集。
- [AirSim Datasets](https://github.com/microsoft/AirSim) – 基于 AirSim 仿真生成的合成数据集。
- [DronesDataset](https://github.com/Ahmedsalman88/DronesDataset) – 无人机拍摄的目标检测数据集。
- [UAVDT](https://github.com/VisDrone/UAVDT) – 面向城市环境的无人机检测与跟踪数据集。
- [UAV-Human](https://github.com/SUTDCV/UAV-Human) – 大规模无人机人体行为数据集。
### 机械结构
- [GrabCAD](https://grabcad.com/library) – 面向无人机机架和组件的开源机械 CAD 模型。
### 电子设备
- [Oshwhub](https://oshwhub.com/) – 面向 PCB 设计和电子项目分享的开源硬件平台。
### 服务
- [AirMap](https://www.airmap.com/) – 无人机的航空数据与服务。
- [DroneDeploy](https://www.dronedeploy.com/) – 无人机测绘软件。
- [RotorBuilds](https://rotorbuilds.com/) – FPV 零件清单和组装日志。
- [Zeitiew](https://www.zeitiew.com/) – 无人机服务在线市场。原名 DroneBase。

## 硬件
### 遥控发射器
- [FlySky](http://www.flyskyrc.com/) – 入门级发射器。
- [FrSky](https://www.frsky-rc.com/) – 采用 OpenTX 固件的 Taranis 和 Horus 系列发射器。
- [Futaba](https://www.futabarc.com)
- [Spektrum](https://www.spektrumrc.com)
- [Team Blacksheep](https://team-blacksheep.com) – Tango 1 和 2 发射器。
### 无人机机架
- [Source One by TBS](https://github.com/tbs-trappy/source_one) – 开源自由式 FPV 无人机机架。
- [Source Two by TBS](https://github.com/ps915/source_two) – 开源竞速 FPV 无人机机架。
- [Source Micro by TBS](https://github.com/ps915/source_micro) – 开源迷你无人机机架。
- [Source PodRacer](https://github.com/ps915/source_podracer) – 开源超轻量无人机机架。
- [Source V by TBS](https://github.com/ps915/source_v) – 开源超刚性无人机机架。
- [Source X by TBS](https://github.com/ps915/source_x) – 开源大型竞速无人机机架。
### 头戴式显示器
- [DJI Digital FPV System](https://www.dji.com/fpv/) – 低延迟数字 FPV 护目镜。
- [FatShark](https://www.fatshark.com) – 竞速玩家推崇的头戴式显示器。
- [ORQA FPV.One](https://orqafpv.com) – 头戴式显示器和控制器
### 视频接收器
- [ClearView XLR 1.3](https://clearview-direct.com/product-category/ground-station-receivers/1-3-receivers/)
- [ClearView XLR 2.4](https://clearview-direct.com/product-category/ground-station-receivers/2-4-receivers/)
- [TBS Ground station](https://www.team-blacksheep.com/products/prod:tbs_gs_2g4)
- [ClearView Goggle Receiver](https://clearview-direct.com/shop/clearview-goggle-products/clearview-goggle-module/)
- [ClearView 5.8GHz Ground Station Receivers](https://clearview-direct.com/product-category/ground-station-receivers/5-8-receivers/)
- [rapidFIRE](https://www.immersionrc.com/fpv-products/rapidfire/)
- [TBS Fusion](https://www.team-blacksheep.com/products/prod:tbs_fusion) – 具备 CRSF 集成（用于切换频道）。
### 电子设备与电机
术语说明：
- FC = 飞控 (Flight Controller)
- ESC = 电子调速器 (Electronic Speed Controller)
- PDB = 电源分配板 (Power Distribution Board)
- RX = 接收器 (Receivers)
- TX = 发射器 (Transmitters)
- VRX = 视频接收器 (Video Receiver)
- VTX = 视频发射器 (Video Transmitter)

品牌列表：
- [3BHobby](https://www.3bhobby.com) - 电机
- [Airbot](https://store.myairbot.com/flight-controller.html) - FC, ESC
- [BrotherHobby](https://www.brotherhobbystore.com) - 电机
- [ClearView](https://clearview-direct.com/) - VRX, VTX
- [DalProp](http://dalprop.com) - 桨叶
- [Diatone](https://www.diatone.us/) - FC, ESC, VTX, 电机
- [Fl1ghtOne](https://flightone.com) - FC, ESC
- [Flyduino](https://www.flyduino.net/en_US/) - FC, ESC
- [GemFan](https://www.gfprops.com/) - 桨叶
- [Hobbywing](http://www.hobbywing.com) - FC, ESC, 电机
- [Holybro](http://www.holybro.com) - FC, ESC, PDB
- [HQProp](http://www.hqprop.com) - 桨叶
- [iFlight](https://www.iflight-rc.com) - 电机
- [Lumenier](https://www.lumenier.com) - FC, ESC, PDB, VTX, 电机
- [MatekSys](http://www.mateksys.com) - FC, PDB, VTX
- [RacerStar](https://www.racerstar.com) - FC, ESC, 电机
- [SP Racing](http://seriouslypro.com) - FC
- [T-Motor](http://www.tmotor.com) - FC, 电机
- [Team Blacksheep](https://www.team-blacksheep.com) - ESC, RX, TX, VRX, VTX
### 摄像头
- [Caddx.us](https://caddxfpv.com/)
- [DJI O3 Air unit](https://www.dji.com/ee/o3-air-unit) - 具备数字视频传输的摄像头
- [Foxeer](http://www.foxeer.com)
- [RunCam](https://runcam.com)

## 产品与项目
### 无人机
- [DJI](https://www.dji.com/) – 全球消费无人机市场领导者——Mavic、Phantom、Inspire 和 Matrice 系列无人机。
- [Autel](https://www.autelpilot.eu/) – 紧凑型 EVO 系列无人机，DJI Mavic 系列的替代品。Dragonfish 系列固定翼无人机即将推出。
- [Eachine](https://www.eachine.com/) – 迷你和微型无人机。FPV 初学者套装。
- [Hubsan](https://www.hubsan.com/na/) – 微型和迷你低成本无人机。
- [Parrot SA](https://www.parrot.com/global/) – 以 Parrot Bebop 和 Parrot AR 系列无人机闻名。
- [Syma](http://www.symatoys.com/) – RC 玩具四旋翼飞行器。
- [Yuneec International](https://www.yuneec.com/) – Yuneec 摄像无人机。
- [AeroVironment](https://www.avinc.com/) – 小型近程固定翼无人机。
- [Baykar](https://www.baykartech.com/en/) – Bayraktar 系列经过实战验证的远程固定翼无人机。
- [Eli](http://www.uav.ee/) – 固定翼无人机的气动发射器。
- [INSITU](https://www.insitu.com/) – 远程和长续航固定翼无人机。
- [Threod Systems](http://threod.com/) – 固定翼和多旋翼无人机。
### 无人地面车辆
- [JPL Open Source Rover](https://github.com/nasa-jpl/open-source-rover) – NASA JPL 缩小版的好奇号漫游车，由商用现成（COTS）组件组成。
- [Turtlebot](https://www.turtlebot.com) – 开源 UGV，[ROS](http://www.ros.org/) 标准平台。
### 无人水下航行器
- [Geneinno](https://www.geneinno.com/) – 水下无人机。

## 相关列表
- [Awesome Robotics](https://github.com/awesomelistsio/awesome-robotics)
- [Awesome Computer Vision](https://github.com/awesomelistsio/awesome-computer-vision)
- [Awesome Reinforcement Learning](https://github.com/awesomelistsio/awesome-reinforcement-learning)
- [Awesome AI Agents](https://github.com/awesomelistsio/awesome-ai-agents)
- [Awesome AI Research Tools](https://github.com/awesomelistsio/awesome-ai-research-tools)
- [Awesome Drones](https://github.com/janesmae/awesome-drones)

## 贡献

欢迎贡献。请确保您的提交完全符合 [`CONTRIBUTING.md`](CONTRIBUTING.md) 中的要求，包括格式、范围对齐和分类放置。

不符合贡献指南的拉取请求可能会被关闭。

## 许可证

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](http://creativecommons.org/licenses/by-sa/4.0/)
