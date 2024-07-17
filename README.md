# ROS-W2-Task-1
The steps that I took to installing Linux Ubuntu then ROS neotic &amp; foxy.
## Linux ![image](https://github.com/user-attachments/assets/542f8a28-138f-4e8e-abb1-344f6be0656d)

I got the iso for Ubuntu [Here](https://releases.ubuntu.com/20.04/), <br />
and Oracle VM [Here](https://releases.ubuntu.com/20.04/), <br />
Virtual box recognized the iso and did an unattended install <br />
afterward, I had to add my local user to the sudoers file, <br />
then I installed an alternative Terminal as the included one was unresponsive, <br />
With the new terminal, I upgraded the system packages and got to work <br />
I then repeated the process with a separate VM for the ROS foxy installation. <br />
![image](https://github.com/user-attachments/assets/ffc81ae8-c2ed-43ac-8521-b61e551b2ee3)

## ROS neotic
### One step at a time
By following the steps provided [Here](http://wiki.ros.org/noetic/Installation/Ubuntu), <br />
I managed to install this version of ROS but not without faults the keys provided in step 1.3 were no longer working the new ones can be found [Here](https://discourse.ros.org/t/new-gpg-keys-deployed-for-packages-ros-org/9454/1), <br />
then finally testing with the roscore command gave the expected version. <br />
## ROS foxy
after setting up a seperate Ubuntu VM I followed the steps [Here](https://docs.ros.org/en/foxy/Installation/Ubuntu-Install-Debians.html) <br />
I also added the keys from the perovius installation before proceding to be on the safe side <br />
after having a bit of truble installing python3 it worked I tested it with the included talker demo.
![image](https://github.com/user-attachments/assets/9df3cac0-4d0a-46e2-8472-44a27936ef1d)
