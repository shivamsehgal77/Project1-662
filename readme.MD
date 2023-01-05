The babat package needs to be put in a catkin_ws and then catkin_make.
Use the commamd --    "roslaunch batbat template_launch.launch"  to launch the robot in the competition world.
Then to use the teleop use the command --   "rosrun batbat teleop_template.py"  to run the teleop python file.
Then use the commands as displayed in terminal to move the robot in the gazebo competion world.(shown in the teleopvideo)
Then close this terminal and run the command -- rosrun batbat open_loop_controller.py. This will make the robot circle(As shown in the video)
Then simaltaneously run the following subscriber command on a new terminal rosrun batbat subscriber.py.(also shown in video)

These are the steps to run the package.

How the project was made what problems were faced is written in the pdf report.

Three videos are there in the folder teleop, open loop controller and rviz with lidar
