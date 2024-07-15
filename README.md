# ROS-W2-Task-1
The steps that I took to installing Linux Ubuntu then ROS neotic &amp; foxy.
## Linux 
I got the iso for Ubuntu [Here](https://releases.ubuntu.com/20.04/),
and Oracle VM [Here](https://releases.ubuntu.com/20.04/),
Virtual box recognized the iso and did an unattended install
afterward, I had to add my local user to the sudoers file,
then I installed an alternative Terminal as the included one was unresponsive,
With the new terminal, I upgraded the system packages and got to work
I then repeated the process with a separate VM for the ROS foxy installation.
## ROS neotic
### One step at a time
By following the steps provided [Here](http://wiki.ros.org/noetic/Installation/Ubuntu),
I managed to install this version of ROS but not without faults the keys provided in step 1.3 were no longer working the new ones can be found [Here](https://discourse.ros.org/t/new-gpg-keys-deployed-for-packages-ros-org/9454/1),
then finally testing with the roscore command gave the expected version.
