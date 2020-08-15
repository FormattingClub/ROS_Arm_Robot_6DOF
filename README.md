# ROS_Arm_Robot_6DOF
ROS六自由机械臂
基于ROS Melodic + Ubuntu 18.04 + Python 3.7（Anaconda全家桶） + PyFirmata协议
话题名称：joint_value
消息格式：
  int64 joint1_angle
  int64 joint2_angle
  int64 joint3_angle
  int64 joint4_angle
  int64 joint5_angle
  int64 joint6_angle
硬件环境：Arduino+StandFirmata（Arduino例程）
硬件引脚关系：
  Joint1------>D3
  Joint2------>D5
  Joint3------>D6
  Joint4------>D9
  Joint5------>D10
  Joint6------>D11
