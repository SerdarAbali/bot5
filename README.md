# Bot5
## Differential drive SLAM robot
## Requirements

You can either buy an old used hoverboard or order the following:

Method 1
Buy a hoverboard, the most compatible model would be "Orb Wheel X8"

Method 2
Buy seperate parts:
- Hoverboard motor controller:

 https://www.aliexpress.com/item/10000057151391.html
 
- 10" Hoverboard hubwheels with hall sensors:

 https://www.aliexpress.com/item/32850640454.html

- 36V battery pack:

 https://www.aliexpress.com/item/32809906886.html
 
- A mini PC such as Intel Nuc or Raspberry Pi 4 with ROS Noetic. For Raspberry Pi 4 you can download Ubiquity Robotics image from here:

https://www.ubiquityrobotics.com/downloads-raspberry-pi/

- ST-Link V2 or a replica:

https://www.banggood.com/3pcs-ST-LINK-V2-Programmer-Emulator-Mini-STLINK-Downloader-for-STM8-or-STM32-MCU-Development-Board-p-1684588.html?imageAb=1&akmClientCountry=FI&cur_warehouse=CN

Now, assuming that you have the hardware ready, please follow the steps below:

1- Hoverboard motor controller FOC hack, please be careful with this controller, it tends to fry itself very easy. Avoid any unnecessary metal contact, liquids and such. It easily shorts and bricks.

Please refer to this video for FOC hack (Attention, Llyod flashes the controller while the controller is plugged to battery. Do not plug it to battery during any procedure explained in the video)

https://www.youtube.com/watch?v=E6JbFnRiQ5g&ab_channel=PracticalRobotics

Llyod has a great step-by-step guide how to properly hack the firmware, also showing what parameters to change/edit. 

2- Install the Hoverboard-driver from the below link (Original driver by Alex Makarov):

https://github.com/SerdarAbali/hoverboard-driver

I changed some parameters and made it compatible for 10" wheels, it is easier to get your bot up and running with my hoverboard library

3- Download Bot5 package from this repository and run the following commands:


