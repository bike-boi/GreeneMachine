# ROS Notes
## Our setup
* Distro: ROS Indigo
* Nodes
	* hokoyu_node (Lidar)
		* Needs to be setup. See [daslhub.org](http://www.daslhub.org/unlv/wiki/doku.php?id=using_ros_to_read_data_from_a_hokuyo_scanning_laser_rangefinder)
	* vesc (speed controller)
		*	Needs to be setup. See [jetsonhacks.com](https://www.jetsonhacks.com/2017/06/01/get-your-motor-running-vesc-jetson-racecar-build/)
	*	To be continued...

__Dear team, Before messing with ROS, please try and understand the basic principles (see [ROS Wiki](http://wiki.ros.org/ROS/Introduction)). I'm tired of going in circles.__

__-Sean__

## ROS commands
ROS contains many command line tools. See [ROS Wiki](http://wiki.ros.org/ROS/CommandLineTools) for a list, but I can't guarantee they will all work for our ROS distro.

## Which ROS distro for your ubuntu version?
From [ROS Forums](https://answers.ros.org/question/233818/which-is-the-best-ubuntu-version-to-use-for-ros/)
* kinetic: 15.10, 16.04
* jade: 14.04, 14.10, 15.04
* indigo (what we're using): 13.10, 14.04
* hydro: 12.04, 12.10, 13.04
* groovy: 11.10, 12.04, 12.10
* fuerte: 10.04, 11.10, 12.04
* electric: 10.04, 10.10, 11.04, 11.10
* diamondback: 10.04, 10.10, 11.04
* cturtle: 9.04, 9.10, 10.04, 10.10s