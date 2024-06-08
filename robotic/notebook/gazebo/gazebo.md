
```cardlink
url: https://github.com/ros-controls/ros2_control_demos/tree/humble
title: "GitHub - ros-controls/ros2_control_demos at humble"
description: "This repository aims at providing examples to illustrate ros2_control and ros2_controllers  - GitHub - ros-controls/ros2_control_demos at humble"
host: github.com
favicon: https://github.githubassets.com/favicons/favicon.svg
image: https://opengraph.githubassets.com/6ddb8aef191c9ec63ea4a6179d7c741d910cb6753bed1d661ce8fb45b9a27f78/ros-controls/ros2_control_demos
```

```cardlink
url: https://github.com/ros-controls/gazebo_ros2_control
title: "GitHub - ros-controls/gazebo_ros2_control: Wrappers, tools and additional API's for using ros2_control with Gazebo Classic"
description: "Wrappers, tools and additional API&#39;s for using ros2_control with Gazebo Classic - GitHub - ros-controls/gazebo_ros2_control: Wrappers, tools and additional API&#39;s for using ros2_control with..."
host: github.com
favicon: https://github.githubassets.com/favicons/favicon.svg
image: https://opengraph.githubassets.com/92fffa000becc4546df3d2372ace098acedd92ea134fc5f251a055e1a0471e6f/ros-controls/gazebo_ros2_control
```

# Document
```cardlink
url: https://control.ros.org/humble/doc/ros2_control_demos/doc/index.html#ros2-control-demos-install
title: "Demos — ROS2_Control: Humble Feb 2024 documentation"
host: control.ros.org
```
```cardlink
url: https://book.guyuehome.com/ROS2/3.%E5%B8%B8%E7%94%A8%E5%B7%A5%E5%85%B7/3.4_Gazebo/
title: "ROS2入门教程 gazebo"
host: book.guyuehome.com
```

查询gazebo进程
```bash
ps -ef |grep gazebo
```
kill进程
```bash
kill -9 ${ID}
```
.bashrc文件
```bash
source /usr/share/gazebo/setup.sh
```

```cardlink
url: https://blog.csdn.net/weixin_44759237/article/details/131976029
title: "【ROS2】通过launch使用gazebo11打开xacro模型（含机械臂）_xacro.parse()-CSDN博客"
description: "文章浏览阅读698次。ros2刚使用不久，如文章内容有误，欢迎在评论内讨论与指正。环境配置：ubuntu版本：22.04ros版本：ros2 humble。_xacro.parse()"
host: blog.csdn.net
```

# 前后端分离

```cardlink
url: https://answers.gazebosim.org/question/255/is-it-possible-to-run-gzserver-and-gzclient-on-separate-computers/
title: "Is it possible to run gzserver and gzclient on separate computers? - Gazebo: Q&A Forum"
description: "Is it possible to run gzserver on one computer while the gzclient on another one? I tried to change the GAZEBOMASTERURI on another computer to the IP address that the gazebo runs, and then start the gzclient. The messages printed out show that it connects to the gazebo master but shows only an empty world on GUI."
host: answers.gazebosim.org
```

```cardlink
url: https://answers.gazebosim.org/question/7117/running-gzserver-on-ec2-and-gzclient-locally-is-not-working/
title: "Running gzserver on EC2 and gzclient locally is not working - Gazebo: Q&A Forum"
description: "So I have an AWS ec2 instance that I am trying to run gzserver on and then locally I want to connect to it with gzclient. I am working with gazebo-2.2 These are my steps: AWS instance: ssh into instance (I try ssh -X, ssh -Y and ssh) source /usr/share/gazebo/setup.sh GAZEBO_IP=[aws_public_ip] GAZEBO_MASTER_URI=[aws_public_ip] gzserver worlds/shapes.world Locally: source /usr/share/gazebo/setup.sh GAZEBO_IP=[local_public_ip] GAZEBO_MASTER_URI=[aws_public_ip] gzclient The client appears to connect to the server. The gazebo GUI appears but the world does not, just a black screen. After some time both the server and client eventually crash. But if I run both gzserver and gzclient on the same machine (AWS instance or locally) it works. I setup my AWS instance and my machine to accept all traffic on all ports so I don't think that could be the problem. Any ideas would help!"
host: answers.gazebosim.org
```

```cardlink
url: https://robotics.stackexchange.com/questions/108423/multiple-isolated-gazebo-on-same-pcros2?newreg=90640c9aa3dd4676a6b405fd9a1bce74
title: "Multiple isolated gazebo on same PC(ROS2)"
description: "I need to run multiple instances of gazebo on same PC (ROS version foxy) and want to interact with them individually like spawning a robot in one of them.I tried using different ROS_DOMAIN_ID in"
host: robotics.stackexchange.com
image: https://cdn.sstatic.net/Sites/robotics/Img/apple-touch-icon@2.png?v=da210979bb08
```
