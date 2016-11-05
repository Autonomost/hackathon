# hackathon
Modified code for the AE Hackathon 2016

This code is based on: http://robohub.org/up-and-flying-with-the-ar-drone-and-ros-getting-started/ 

You can download the virtual machine (VirtualBox) from: https://github.com/downloads/mikehamer/ardrone_tutorials_getting_started/ARDroneUbuntu.ova

In order to run our modified code, clone this repository and run:

# NOTE: If you are using the VM, the old ardrone_tutorials is still there, so move it elsewhere first
roscd
mv ardrone_tutorials ardrone_tutorials_orig

# Clone repository
git clone https://github.com/Autonomost/hackathon

mv hackathon ardrone_tutorials 

cd ardrone_tutorials

source setpath.sh

roslaunch ardrone_tutorials keyboard_controller_with_tags.launch
