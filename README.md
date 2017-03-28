# homework1

What to do:
  - Run the STAGE simulator
  - Write a node that:
    1. subscribes the /base_scan topic and ...
    2. … for each incoming LaserScan message computes the minimum distance from 
      the obstacles and …
    3. … publishes the minimum distance on another topic
  - Play with it!

Useful links:
  - Run stage: http://wiki.ros.org/stage/Tutorials/SimulatingOneRobot
  - Teleoperation packages:
    1. http://wiki.ros.org/teleop_twist_keyboard
    2. http://wiki.ros.org/teleop_twist_joy
  - LaserScan msg: http://docs.ros.org/api/sensor_msgs/html/msg/LaserScan.html
