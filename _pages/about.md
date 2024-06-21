---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<span class='anchor' id='about-me'></span>
许尔霈目前是北京理工大学自动化学院研二研究生，求学于复杂决策与控制**国家重点实验室**，研究方向为无人机/无人车路径规划与控制。他在2018-2022年在北京理工大学自动化学院获得学士学位。

他的研究兴趣包括无人机/无人车路径规划与控制等，在这些方面有着丰富的动手和项目经验。他在国际会议上发表了多篇论文，包括IEEE CASE、IEEE ICCA等。他曾获得国家奖学金、优秀学生奖学金等荣誉。






# 🔥 News


# 📖 教育经历

- *2018.08 - 2022.06*  本科  北京理工大学  自动化学院  自动化 ('**双一流学科**'，'**A+**')
  
  核心课程  自动控制原理(92)  工科数学分析(99)  程序设计基础(99) 线性代数(99)
  
  学分绩：90.4 (19/220，前10%)   荣誉/奖项：**国家奖学金** 连续三年优秀学生奖学金

- *2022.08 - 至今*        硕士(**保研**) 北京理工大学  自动化学院  控制工程  ('**双一流学科**'，'**A+**')
  

# 📝 论文发表 

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">ICCA 2024</div>
      <img src="images/ICCA.png" width="100%"/>
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

  **Topological Risk-Based Path Selection in Dynamic Environments**

  <!-- IEEE International Conference on Unmanned Systems (ICCA), Guangzhou, China, 2023  Under Review -->
  IEEE International Conference on Control & Automation (ICCA), Reykjavík, Iceland, 2024
  已接收

  **Erpei Xu**, Chengpu Yu, Yixuan Liu

  <!-- - Eliminate dynamic feature points while retaining static points of movable objects to improve robustness. The localization accuracy is improved by up to 21.69% compared with ORB-SLAM in the KITTI dataset. -->
  - 本文介绍了一种在动态环境中选择安全拓扑路径的方法，该方法不需要对移动障碍物进行建模。该方法首先生成几条平滑的拓扑路径，然后通过计算粒子动态图上每条路径的风险来选择最安全的路径。此外，在动态场景中提出了一种重新规划策略，以主动应对即将到来的障碍，提高规划安全性。最后，在仿真和实际环境中对该方法进行了验证。

  </div>
</div>

  <div style="position: relative; padding: 15% 15%;">
<iframe style="position: absolute; width: 100%; height: 100%; left: 0; top: 0;"  src="//player.bilibili.com/player.html?aid=1953703931&bvid=BV1tC411H7Wd&cid=1521593533&p=1&high_quality=1&danmaku=0&loop=1" scrolling="no"  frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>
</div>


<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">CASE 2023</div>
      <a href="https://youtu.be/aPXxOKf1o10" title="TDLE"><img src="https://res.cloudinary.com/marcomontalbano/image/upload/v1685324236/video_to_markdown/images/youtube--aPXxOKf1o10-c05b58ac6eb4c4700831b2b3070cd403.jpg" alt="TDLE: 2D Lidar Exploration with Hierarchical Planning Using Regional Division" width="100%"/></a>
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

  **[TDLE: 2D Lidar Exploration with Hierarchical Planning Using Regional Division](https://arxiv.org/abs/2307.02852)**

  IEEE International Conference on Automation Science and Engineering (CASE), Auckland, New Zealand, 2023 

  Xuyang Zhao, Chengpu Yu, **Erpei Xu** and Yixuan Liu

  - 提出了一种利用全球动态区域划分和本地化度量评价来实现高效、低计算要求的自主测绘的勘探系统。该方法可以在 Jetson Nano 这样的低功耗边缘平台上高频(> 100Hz)运行，与以前的方法相比，效率提高了57.57% 。

  </div>
</div>


# 📚 项目经历

  xep对自主无人系统有着浓厚的兴趣和经验丰富的动手能力，以下是他的一些项目经历和自己搭建的平台

  [室内机器人集群探索]  

  - *2022年6月 - 至今*, **空地异构平台协同的室内导航与侦测  国家重点研发项目**

  <!-- 项目描述：In disaster relief scenarios, there is a safety risk for rescuers when they enter damaged buildings, such as those affected by an earthquake. 
  To tackle this issue, we have developed a Solid-state LiDAR exploration and mapping system. The proposed system conduct indoor information surveys and return autonomously after completion, helping to inspect the internal environment and find trapped people.
  The whole process requires no remote control or pre-specified routes, as the decision is made entirely by the on-board processing unit. -->

  项目描述：
  在救灾场景中，救援人员进入受损建筑物（例如受地震影响的建筑物）时存在安全风险。

  为了解决这个问题，我们开发了固态激光雷达勘探和测绘系统。该系统进行室内信息勘察，完成后自动返回，帮助检查内部环境并找到被困人员。

  整个过程不需要远程控制或预先指定的路线，因为决策完全由机载处理单元做出。

  负责模块：全局探索的一些决策、路径规划、轨迹优化等 和还有一些无人机控制算法的设计

<!-- <table><tr>
<td style="width:50%"> <a href="https://youtu.be/BFo1Ke8co4k" title="Exploration with Solid-state Lidar (3 UAVs)"><img src="https://res.cloudinary.com/marcomontalbano/image/upload/v1688958193/video_to_markdown/images/youtube--BFo1Ke8co4k-c05b58ac6eb4c4700831b2b3070cd403.jpg" alt="Exploration(3 UAVs)"></a></td>
<td> <a href="https://youtu.be/hQJ7u7scb8Y" title="Exploration with Solid-state Lidar (2 UAVs)"><img src="https://res.cloudinary.com/marcomontalbano/image/upload/v1688958424/video_to_markdown/images/youtube--hQJ7u7scb8Y-c05b58ac6eb4c4700831b2b3070cd403.jpg" alt="Exploration(2 UAVs)"></a></td>
</tr></table> -->

<table><tr>
<td style="width:50%"> 
<img src="images/proj 2-1.gif" alt="Exploration(3 UAVs)">
</td>
<td> 
<img src="images/proj 2-2.gif" alt="Exploration(2 UAVs)">
</td>
</tr></table>

<!-- 【小飞一下记录】 https://www.bilibili.com/video/BV19T421y7ri/?share_source=copy_web&vd_source=4b9edb7cdb221c2a812392f928bb3105
  [室内机器人协同定位] -->

<!-- <div style="position: relative; padding: 30% 45%;">
<iframe style="position: absolute; width: 100%; height: 100%; left: 0; top: 0;" src="https://player.bilibili.com/player.html?cid=145147963&aid=84267566&page=1&as_wide=1&high_quality=1&danmaku=0" frameborder="no" scrolling="no"></iframe>
</div> -->



  - *2021年10月 - 至今*, **无人集群协同探测与态势评估技术研究**

  项目描述:构建支持任意数量智能体、可高效协同探索的无人集群，进行未知环境态势评估
  
  负责模块: 搭建硬件平台，设计无人机控制算法

  [无人机自主探测]

  
  <table>
  <tr>
  <td style="width:25%;  text-align: center;">
    <img src="images/uav1.png" alt="PX41" style="height:300px; width:auto; display:inline-block;" />
  </td>
  <td style="width:25%;  text-align: center;">
    <img src="images/uav2.png" alt="PX42" style="height:300px; width:auto; display:inline-block;" />
  </td>
  <td style="width:50%; vertical-align: top; padding-left:1px;">

  <table>
  <tr>
  <td style="width:25%;  text-align: center;">
    <img src="http://cdn.xuerpei.xyz/uav1.png" alt="PX41" style="height:300px; width:auto; display:inline-block;" />
  </td>
  <td style="width:25%;  text-align: center;">
    <img src="http://cdn.xuerpei.xyz/uav2.png" alt="PX42" style="height:300px; width:auto; display:inline-block;" />
  </td>
  <td style="width:50%; vertical-align: top; padding-left:1px;">


    (1) 从零构建小型无人机：从硬件选型、连接件设计，到飞控配置、软硬件联调；  
    
    (2)利用无人机动力学模型，设计无人机规划与底层飞控的中间控制器，包括姿态控制器与角速度控制器；  
    
    (3) 搭建了基于ROS的完整控制器接口与状态机模型，并且构造 PID、LQR、MPC、NMPC 等轨迹跟踪优化模型。   

  </td>
  </tr>
  </table>

  <div style="position: relative; padding: 15% 15%;">
<iframe style="position: absolute; width: 100%; height: 100%; left: 0; top: 0;"  src="//player.bilibili.com/player.html?aid=1904687766&bvid=BV1ZU411f7nV&cid=1543733214&p=1&high_quality=1&danmaku=0&loop=1" scrolling="no"  frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>
</div> 
<!-- <iframe src="//player.bilibili.com/player.html?aid=1904687766&bvid=BV1ZU411f7nV&cid=1543733214&p=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe> -->
  <div style="position: relative; padding: 15% 15%;">
<iframe style="position: absolute; width: 100%; height: 100%; left: 0; top: 0;"  src="//player.bilibili.com/player.html?isOutside=true&aid=1104865491&bvid=BV1qw4m1D7Sj&cid=1554923868&p=1&high_quality=1&danmaku=0&loop=1" scrolling="no"  frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>
</div>

  <div style="position: relative; padding: 15% 15%;">
<iframe style="position: absolute; width: 100%; height: 100%; left: 0; top: 0;"  src="//player.bilibili.com/player.html?isOutside=true&aid=112629611759647&bvid=BV1wmVHetEQS&cid=500001584955490&p=1&high_quality=1&danmaku=0&loop=1" scrolling="no"  frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>
</div>


  <div style="position: relative; padding: 15% 15%;">
<iframe style="position: absolute; width: 100%; height: 100%; left: 0; top: 0;"  src="//player.bilibili.com/player.html?aid=1703514000&bvid=BV19T421y7ri&cid=1519641466&p=1&high_quality=1&danmaku=0&loop=1" scrolling="no"  frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>
</div>




>

# 🎖 荣誉奖项

- *2019.10* 国家奖学金 北京理工大学
- *2018.8 - 2021.6*  优秀学生奖学金 北京理工大学 自动化学院
- *2018.8 - 2022.6* 班长 北京理工大学 自动化学院自动化专业
- *2020.9*  全国大学生智能车竞赛全国三等奖
- *2022.9* 以**8.6%**(19/220)成绩**保研**至北京理工大学自动化学院复杂系统与智能控制**国家重点实验室**硕士研究生
<!-- - *2023.1* 获得挑战杯北京赛区一等奖 -->

# 📚 专业技能

- **编程语言**: 熟悉Python, C++, C，Git.
- **机器人操作系统**: 熟悉ROS, Gazebo, Cmake, Rotors.
- **数值优化库**: 了解OSQP, Casadi, Acados, Nlopt等数值优化库 
- **嵌入式系统**: 熟悉STM32, Arduino, Nvidia jeston nano\NX\TX2.
- **无人机组装**: 熟悉PX4, QGroundControl, Mavros 无人机常用硬件选型机载计算机、电调电机、激光雷达视觉等传感器.
- **状态滤波方法**: 了解Kalman Filter, EKF, UKF.
- **路径规划与控制**: 熟悉A\*、RRT*等路径规划算法，PID、LQR、MPC等控制算法.
- **深度学习框架**: 了解Pytorch, Keras.