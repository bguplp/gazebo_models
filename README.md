## Installation and usage

* Clone the repository to your catkin_ws/src and make:
``` bash
cd ~/catkin_ws/src
git clone https://github.com/TalFeiner/gazebo_models.git
cd ..
catkin_make
```

* Run the launch file:
```bash
roslaunch gazebo_models citizens_human.launch
```

* Each robot have different namespaces, please check the available topics for velocity command. They all end in cmd_vel (<namespace>/cmd_vel).
