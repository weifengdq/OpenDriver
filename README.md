# OpenDriver

A Revision of Hardware for [http://www.ros-robot.com/](http://www.ros-robot.com/)

![](/assets/OpenDriver_top.png)

The board based on ArduinoDue, as a driver board for ROS Car in [http://www.ros-robot.com/](http://www.ros-robot.com/).

Three Bushed-Motors\(integration encoder\) are driven by A4950. CP2104 is designed for serial port communication, It's  stable, small and cheap. MPU6050 is used for IMU. Encoder voltage level is 5V while Arduino Due is 3.3V, so the OpenDriver board integrate 3.3V-5V switching circuit for encoder:

![](/assets/3.3to5.png)

Enjoy it !

