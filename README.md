# Init_ROS

## Create a ROS Workspace

~~~
1 mkdir -p ~/catkint_ws/
2 cd ~/catkint_ws/
3 catkint_make
4 source devel/setup.bash
5 echo %ROS_PACKAGE_PATH
~~~

## Example rospy 

~~~
1 chmod +x namefile
2 rosrun package_robot nodo_publher.py 
~~~

## SEE ALL TOPIC, data type

~~~
1 rostopic list
2 rostopic echo /example -n 3
~~~

## CREATE PKG 
~~~
catkin_create_pkg atom_bot rospy std_msgs geometry_msgs sensor_msgs
~~~
