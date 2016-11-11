## ubuntu 配置ROS ##
<br/>
**1: 设置sources.list**

- **sudo sh -c 'echo "deb http://packages.ros.org/ros/ubuntu $(lsb_release -sc) main" > /etc/apt/sources.list.d/ros-latest.list'**

**2: 设置key**

- **sudo apt-key adv --keyserver hkp://ha.pool.sks-keyservers.net:80 --recv-key 0xB01FA116**

**3: 安装**

- **sudo apt-get update**

- **sudo apt-get install libgl1-mesa-dev-lts-utopic**

- **sudo apt-get install ros-jade-desktop-full**

- **apt-cache search ros-jade**

**4: 安装rosedp**

- **sudo rosdep init**

- **rosdep update**

**5： 配置环境**

- **echo "source /opt/ros/jade/setup.bash" >> ~/.bashrc**
- **source ~/.bashrc**

**6: 安装rosinstall**

- **sudo apt-get install python-rosinstall**

