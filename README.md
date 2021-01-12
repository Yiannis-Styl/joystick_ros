# joystick_ros
Connect a usb joystick to commuinicate with ros operating system.


Install first:
ROS operating system
Pygame
-----------------------------------
Win:
pip install pygame

Linux:
apt get install pygame

Run:

roscore

and in new terminal:

python talker_joystick.py

To check the published message open rqt --> Plugins --> Topics --> Topic Monitor

It will publish Int16 std_msgs(topic:cw_move) from axis1 of joystick & Int32 std_msgs(topic:cw_move) from axis2 of joystick
ex. when you move the axis1 full it publishes "50" (cw_move:Int16) with rate of 10 Hz.
it works only when you have the joystick window in front.

This program can be improved. This is something that i did with not even the basic knowledge of python languange. 
I used this addon autopep8 for fixing the code! (pip install autopep8)

For any update that someone did please send me a link to the code.
