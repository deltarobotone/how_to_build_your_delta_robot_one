# Welcome robot friends! 

We decided to create this little robot to have an interdisciplinary subject in our studies. This project turned into a journey lasting over three years and two things always stayed the same...fun and Arduino UNO ;) Drawing, lasercutting, soldering, 3D-printing, programming an arduino library, a python package, an android and a windows app, etc....it is turning in a never ending story. With the help of a community (this means you) it could be a world wide educational project. Working on this project is a lot of fun. Learning something about the different topics and share it with the world is realy great. Be part of it...

Our four One's welcome you with a short clip...

[<img src="http://img.youtube.com/vi/xEFp4XrQJKs/0.jpg" width="500">](https://www.youtube.com/watch?v=xEFp4XrQJKs)

...keep smiling :)

# Direct link -> [**>>>how to build your robot wiki<<<**](https://github.com/deltarobotone/how_to_build_your_one/wiki) 

# Delta-Robot One

Delta-Robot One is mainly designed for students and makers with an educational thought. Everyone who likes to learn something about robotics can take a look at different fields - electronics, mechanics and informatics.

[<img src="https://raw.githubusercontent.com/deltarobotone/image_database/master/delta_robot_one/delta_robot_one%20(35).png" width="500">](https://raw.githubusercontent.com/deltarobotone/image_database/master/delta_robot_one/delta_robot_one%20(35).png)

Let's introduce this smart little robot. His name is „One“ because he combines a lot of technical topics in one single system. This kind of robot is called delta and it belongs to the family of parallel robots.

# Social Media

Instagram: @deltarobotone #deltarobotone

Facebook: Deltarobotone

Youtube: [deltarobotone](https://www.youtube.com/channel/UCeqy13LiwtQ1QQTYZzzyFRA)

# Arduino Library

The arduino based system helps you to do the first steps easily. It is quite easy to start, so everyone is invited to have some time with this smart robot. If you would like to go more into detail you can do this without any problem because the software is open source.

Sourcecode: [>>>One System Library<<<](https://github.com/deltarobotone/one_system_library)

Install the library usingArduino IDE library manager and choose -> ***OneSystemLibrary***

This library comes with 20 examples to provide functions of the interface

[<img src="https://raw.githubusercontent.com/deltarobotone/image_database/master/circuit_board_assembly/circuit_board_assembly%20(33).PNG" width="500">](https://raw.githubusercontent.com/deltarobotone/image_database/master/circuit_board_assembly/circuit_board_assembly%20(33).PNG)

A full system demo (found in examples) is integrated. If you start the robot at the first time use this example to check out how Delta-Robot One works. It provides a lot of functions and you can use the robot like a stand alone system and check out the mobile and dektop application first.

If you want to use arduino code directly check out the examples. Here a short example how easy the programming interface is:

Move robot -> move.ptp(position x, position y, position z)

```c
//Create the DeltaRobotOne-Object
DeltaRobotOne robot(0, 0, 0, 0, 0, 0, 0x27);
void setup()
{ 
//Robot setup
robot.setup(); 
//Power main circuit
robot.power.mainOn();
//Move the robot to the home position (X=0.0,Y=0.0,Z=85.0)  
robot.move.ptp(home);
}
void loop()
{
//Move Z-Axis up
robot.move.ptp(0.0,0.0,70.0);  
//Move Z-Axis
robot.move.ptp(0.0,0.0,100.0);  
//Wait for 2 seconds  
robot.functions.waitFor(2000);
}
```

# Python package
Delta-Robot One recieves data using a very simple structure. This structure is called the one easy protocol. Have a look at this easy protocol to understand how it works. A Python package provides this communication protocol with a high level interface to control Delta-Robot One from other systems. So you can control your robot easily from a system like a Raspberry Pi via USB. Use python package manager to install one-easy-protocol on your system:

Python 2 -> ***pip install one-easy-protocol***

Python 3 -> ***pip3 install one-easy-protocol***

Sourcecode, Tutorials and Documentation of One Easy Protocol:

[>>>One Easy Protocol Python<<<](https://github.com/deltarobotone/one-easy-protocol)

For C++ version of One Easy Protocol have a look at:

[>>>One Easy Protocol C++<<<](https://github.com/deltarobotone/one_easy_protocol)

[<img src="https://raw.githubusercontent.com/deltarobotone/image_database/master/delta_robot_one/delta_robot_one%20(20).PNG" width="500">](https://raw.githubusercontent.com/deltarobotone/image_database/master/delta_robot_one/delta_robot_one%20(20).PNG)

# Robot assembly

Delta-Robot One is designed as a Kit. The layer system of the body and a clickable mechanical solution make the assembly fast and easy. A structured circuit board makes the soldering more comfortable. Choose the colour of some parts to give the robot an individual look. All in all building the robot provides you with a short practical, educational and interesting experience. Now it‘s time to build your own One!

***How to build your robot?*** No worrys we create a wiki...

Wiki: [>>>How to build you robot<<<](https://github.com/deltarobotone/how_to_build_your_robot)

[<img src="https://raw.githubusercontent.com/deltarobotone/image_database/master/delta_robot_one/delta_robot_one%20(36).jpg" width="500">](https://raw.githubusercontent.com/deltarobotone/image_database/master/delta_robot_one/delta_robot_one%20(36).jpg)

# Robot assembly video clip

[<img src="http://img.youtube.com/vi/3GcX2WYTDjQ/0.jpg" width="500">](https://www.youtube.com/watch?v=3GcX2WYTDjQ)

# Layers

[>>>Documentation<<<](https://github.com/deltarobotone/how_to_build_your_robot/wiki/Layers-parts)

[>>>Files<<<](https://github.com/deltarobotone/hardware_parts/tree/master/Lasercut)

***How to get the layers?*** There are many ways...

- You can use a lasercutter in a Techshop/Makerspace or your School/University
- We ordered from [cutcraft](http://cutcraft.de/) a few times so we can recommend this service
- We don't try it but with a 3D-Printer it has to be possible to create the layers too

[<img src="https://raw.githubusercontent.com/deltarobotone/image_database/master/layers_colors/layers_colors%20(7).PNG" width="500">](https://raw.githubusercontent.com/deltarobotone/image_database/master/layers_colors/layers_colors%20(7).PNG)

Be creative and choose your own design to build an individual robot. Make the world of robots more colourful...

[<img src="https://raw.githubusercontent.com/deltarobotone/image_database/master/layers_colors/layers_colors%20(4).PNG" width="500">](https://raw.githubusercontent.com/deltarobotone/image_database/master/layers_colors/layers_colors%20(4).PNG)

All drawings of the layer system are availible...

[>>>Drawings<<<](https://github.com/deltarobotone/hardware_parts/wiki/Layers-Drawings)

[<img src="https://github.com/deltarobotone/image_database/blob/master/layers_drawings/layers_drawings%20(1).png" width="500">](https://raw.githubusercontent.com/deltarobotone/image_database/master/layers_drawings/layers_drawings%20(1).png)

# Electronics

[>>>Partlist<<<](https://github.com/deltarobotone/hardware_parts/wiki/Electronic-parts)

[>>>Files<<<](https://github.com/deltarobotone/hardware_parts/tree/master/Circuit_Board)

***How to get the board?*** No problem...

...we uploaded our board to the aisler.com page. So you only have to follow this link and create an account to order the board for a good price.

Shop link: [>>>One Circuit Board<<<](https://aisler.net/p/DTEIKQWW)

***How to get the parts?*** All of this are standard parts...

- You can check your own maker stock first ;)
- Use the partlist on the link above and check the recommended shops
- A lot of shops and maybe your school or university have this parts availible

[<img src="https://raw.githubusercontent.com/deltarobotone/image_database/master/circuit_board_assembly/circuit_board_assembly%20(2).PNG" width="500">](https://raw.githubusercontent.com/deltarobotone/image_database/master/circuit_board_assembly/circuit_board_assembly%20(2).PNG)

All Schematics are availible also in a fritzing version...

[>>>Schematics<<<](https://github.com/deltarobotone/hardware_parts/wiki/Circuitboard-Schematics)

[<img src="https://github.com/deltarobotone/image_database/blob/master/circuit_board_schematics/circuit_board_schematics%20(4).png" width="500">](https://raw.githubusercontent.com/deltarobotone/image_database/master/circuit_board_schematics/circuit_board_schematics%20(4).png)

# Mechanics

[>>>Documentation<<<](https://github.com/deltarobotone/how_to_build_your_robot/wiki/Mechanic-parts)

[>>>Files<<<](https://github.com/deltarobotone/hardware_parts/tree/master/3D_Print)

***How to get the parts?*** No problem...

...we tested [i.materialise.com](http://i.materialise.com/) and created some shop items so you can easily order the required parts using this links:

[>>>Kinematics Package<<<](https://i.materialise.com/de/shop/item/one-kinematics-package)

[>>>Pillar Package<<<](https://i.materialise.com/de/shop/item/pillar-package)

[<img src="https://raw.githubusercontent.com/deltarobotone/image_database/master/mechanic_parts/mechanic_parts%20(7).PNG" width="500">](https://raw.githubusercontent.com/deltarobotone/image_database/master/mechanic_parts/mechanic_parts%20(7).PNG)

All drawings of the mechanics are availible...

[>>>Drawings<<<](https://github.com/deltarobotone/hardware_parts/wiki/Mechanic-Drawings)

[<img src="https://github.com/deltarobotone/image_database/blob/master/mechanic_drawings/mechanic_drawings%20(1).png" width="500">](https://raw.githubusercontent.com/deltarobotone/image_database/master/mechanic_drawings/mechanic_drawings%20(1).png)

# Robot is moving like this...

[<img src="http://img.youtube.com/vi/8iWXzC4VD2A/0.jpg" width="500">](https://www.youtube.com/watch?v=8iWXzC4VD2A)


# Pick and place with magnet gripper

[<img src="http://img.youtube.com/vi/m6nE2A7ZUi0/0.jpg" width="500">](https://www.youtube.com/watch?v=m6nE2A7ZUi0)

# Servo Motor

We change the servo motor from Tower Pro MG91 to MG92B because of the availibility. Adafruit Industries provide this motor and so you can easily get this part from providers like mouser, conrad and so on. The form factor is the same and the torque a little bit higher so all in all it is an advantage to use this servo motor. Thanks to Adafruit to provide this part. A few more parts of this robot are provided by Adafruit like the magnet gripper, leds and in the future it is planned to integrate the bluefruit module.

Tower Pro MG92B

- Gear: Metal
- Dimension: 22.8x12x31 mm
- Torque: 3.1kg/cm (4.8v)
- Speed: 0.13sec/60degree (4.8v)
- Voltage: 4.8~6.6v

[<img src="https://github.com/deltarobotone/image_database/blob/master/servo_assembly/servo_assembly%20(26).PNG" width="500">](https://raw.githubusercontent.com/deltarobotone/image_database/master/servo_assembly/servo_assembly%20(26).PNG)

# Windows 10 Application: One Smart Control Desktop

For all those who want to control the robot from a notebook we developed an application for windows based systems. The One Smart Control application is written in C++ using the Qt-Creator IDE and Qt-Framework.

The robot has to be connected via USB. The app provides basic functions of the robot like moving, changing the light and the gripper state. A visualisation of the workingspace helps you to understand the limits of the robot.

The main advantage of this application is the integrated flowchart. It is a tool to create robot programs and start them. Save your flowcharts as flowchart files (.fc). Load and start flowcharts using One Smart Control Desktop, One Smart Control Mobile, One Easy Protocol Python, One Easy Protocol C++.

This application is based of One Easy Protocol C++ extended with signal and slots as a QObject. So it is possible to use it in your own Qt based project.

Sourcecode: [One Smart Control Desktop](https://github.com/deltarobotone/one_smart_control_desktop)

Download: [Direct Link](https://github.com/deltarobotone/one_smart_control_desktop/archive/v0.3-install.zip)

Wiki: [One Smart Control Desktop](https://github.com/deltarobotone/one_smart_control_desktop/wiki)

[<img src="https://raw.githubusercontent.com/deltarobotone/image_database/master/smart_control/smart_control%20(2).png" width="800">](https://raw.githubusercontent.com/deltarobotone/image_database/master/smart_control/smart_control%20(2).png)

[<img src="http://img.youtube.com/vi/YD9djV_gC4c/0.jpg" width="500">](https://youtu.be/YD9djV_gC4c)

# Android Application: One Smart Control Mobile

For all those who want to control the robot from a mobile device we developed an application for android based systems. The One Smart Control application is written in C++ using the Qt-Creator IDE and Qt-Framework.

The robot has to be connected via Bluettooh BLE (Bluetooth module HM-10 needed). The app provides basic functions of the robot like moving, changing the light and the gripper state.

The main advantage of this application is the integrated flowchart. It is a tool to create robot programs and start them. Save your flowcharts as flowchart files (.fc). Load and start flowcharts using One Smart Control Desktop, One Smart Control Mobile, One Easy Protocol Python, One Easy Protocol C++.

This application is based of One Easy Protocol C++ extended with signals and slots as a QObject. In this version the One Easy Protocol is mapped to a Bluetooth device using a QT-Framework bluetooth BLE example. So it is possible to use it in your own Qt based project.

Sourcecode: [One Smart Control Mobile](https://github.com/deltarobotone/one_smart_control_mobile)

Download: [Google Play Store](https://play.google.com/store/apps/details?id=one.smart.control.mobile&gl=DE)

Wiki: [One Smart Control Mobile](https://github.com/deltarobotone/one_smart_control_mobile/wiki)

[<img src="https://github.com/deltarobotone/image_database/blob/master/smart_control_mobile_screenshots/smart_control_mobile_screenshots%20(8).png" width="175">](https://raw.githubusercontent.com/deltarobotone/image_database/master/smart_control_mobile_screenshots/smart_control_mobile_screenshots%20(8).png)
[<img src="https://github.com/deltarobotone/image_database/blob/master/smart_control_mobile_screenshots/smart_control_mobile_screenshots%20(10).png" width="175">](https://raw.githubusercontent.com/deltarobotone/image_database/master/smart_control_mobile_screenshots/smart_control_mobile_screenshots%20(10).png)
[<img src="https://github.com/deltarobotone/image_database/blob/master/smart_control_mobile_screenshots/smart_control_mobile_screenshots%20(13).png" width="175">](https://raw.githubusercontent.com/deltarobotone/image_database/master/smart_control_mobile_screenshots/smart_control_mobile_screenshots%20(13).png)
[<img src="https://github.com/deltarobotone/image_database/blob/master/smart_control_mobile_screenshots/smart_control_mobile_screenshots%20(16).png" width="175">](https://raw.githubusercontent.com/deltarobotone/image_database/master/smart_control_mobile_screenshots/smart_control_mobile_screenshots%20(16).png)

[<img src="http://img.youtube.com/vi/ch6Thpv_J9k/0.jpg" width="500">](https://youtu.be/ch6Thpv_J9k)

# Grasp some metal chips with Delta-Robot One

This video clip show a Delta-Robot One with long pillars (found at hardware_parts) and a conveyor system. This system would be shared soon in another project.

[<img src="http://img.youtube.com/vi/MGw2fCCIe-g/0.jpg" width="500">](https://www.youtube.com/watch?v=MGw2fCCIe-g)

We used a system like this to grasp some chips at the image processing lab of our university. We detect the chips, the colour and the velocity. In the following video you can see a simple system with no image processing. The chip is only detected by a time of flight sensor. The motor of the conveyor system and the sensor are both connected to the robots interface. This shows the possibility to extend yout robot.

There are interfaces provided for:

- Gripper/GND (ON/OFF)
- Motor/GND (PWM max. 4A)
- I2C Bus (SCL/SDA)
- Power/GND (5V/max. 4A)

[<img src="https://raw.githubusercontent.com/deltarobotone/image_database/master/gripper/gripper%20(3).PNG" width="500">](https://raw.githubusercontent.com/deltarobotone/image_database/master/gripper/gripper%20(3).PNG)

# Robotics

This is about the kinematics of Delta-Robot One. If you want to know something about the robot movement check out the explanations on following page:

[>>>Kinematics<<<](https://github.com/deltarobotone/how_to_build_your_robot/wiki/Kinematics)

There you get all the informations to calculate the servo angles to control a delta robot like this. No worrys this is not complicated mathematics. The main advantage of this robot is that all things we have to know are basic geometric functions.

[<img src="https://github.com/deltarobotone/image_database/blob/master/mechanic_drawings/mechanic_drawings%20(6).png" width="500">](https://raw.githubusercontent.com/deltarobotone/image_database/master/mechanic_drawings/mechanic_drawings%20(6).png)

# Hardware parts and documentation! 

For everyone who like to build Delta-Robot One there is a way to do this. In this repository you get all information and files to produce this smart little robot by yourself. 

[>>> Hardware parts wiki<<<](https://github.com/deltarobotone/hardware_parts/wiki)


# Video gallery 
[<img src="http://img.youtube.com/vi/NdPv1pEZnJw/0.jpg" width="250">](https://youtu.be/NdPv1pEZnJw)
[<img src="http://img.youtube.com/vi/xEFp4XrQJKs/0.jpg" width="250">](https://youtu.be/xEFp4XrQJKs)
[<img src="http://img.youtube.com/vi/m6nE2A7ZUi0/0.jpg" width="250">](http://www.youtube.com/watch?v=m6nE2A7ZUi0 "")
[<img src="http://img.youtube.com/vi/MGw2fCCIe-g/0.jpg" width="250">](http://www.youtube.com/watch?v=MGw2fCCIe-g "")
[<img src="http://img.youtube.com/vi/rs2U6MSEfQM/0.jpg" width="250">](http://www.youtube.com/watch?v=rs2U6MSEfQM "")
[<img src="http://img.youtube.com/vi/hkPoAHTrr7U/0.jpg" width="250">](http://www.youtube.com/watch?v=hkPoAHTrr7U "")
[<img src="http://img.youtube.com/vi/ntK9TCerEtc/0.jpg" width="250">](http://www.youtube.com/watch?v=ntK9TCerEtc "")
[<img src="http://img.youtube.com/vi/1ZWHZ4IDjtM/0.jpg" width="250">](http://www.youtube.com/watch?v=1ZWHZ4IDjtM "")
[<img src="http://img.youtube.com/vi/2g2lItaFIQA/0.jpg" width="250">](https://youtu.be/2g2lItaFIQA)
[<img src="http://img.youtube.com/vi/DNDTJoYWN9E/0.jpg" width="250">](https://youtu.be/DNDTJoYWN9E)
[<img src="http://img.youtube.com/vi/ch6Thpv_J9k/0.jpg" width="250">](https://youtu.be/ch6Thpv_J9k)
[<img src="http://img.youtube.com/vi/YD9djV_gC4c/0.jpg" width="250">](https://youtu.be/YD9djV_gC4c)

# Image gallery
[<img src="https://raw.githubusercontent.com/deltarobotone/image_database/master/delta_robot_one/delta_robot_one%20(2).PNG" width="250">](https://raw.githubusercontent.com/deltarobotone/image_database/master/delta_robot_one/delta_robot_one%20(2).PNG)
[<img src="https://raw.githubusercontent.com/deltarobotone/image_database/master/delta_robot_one/delta_robot_one%20(4).PNG" width="250">](https://raw.githubusercontent.com/deltarobotone/image_database/master/delta_robot_one/delta_robot_one%20(4).PNG)
[<img src="https://raw.githubusercontent.com/deltarobotone/image_database/master/delta_robot_one/delta_robot_one%20(3).PNG" width="250">](https://raw.githubusercontent.com/deltarobotone/image_database/master/delta_robot_one/delta_robot_one%20(3).PNG)
[<img src="https://raw.githubusercontent.com/deltarobotone/image_database/master/delta_robot_one/delta_robot_one%20(5).PNG" width="250">](https://raw.githubusercontent.com/deltarobotone/image_database/master/delta_robot_one/delta_robot_one%20(5).PNG)
[<img src="https://github.com/deltarobotone/image_database/blob/master/delta_robot_one/delta_robot_one%20%20(8).PNG" width="250">](https://raw.githubusercontent.com/deltarobotone/image_database/master/delta_robot_one/delta_robot_one%20%20(8).PNG)
[<img src="https://github.com/deltarobotone/image_database/blob/master/delta_robot_one/delta_robot_one%20%20(9).PNG" width="250">](https://raw.githubusercontent.com/deltarobotone/image_database/master/delta_robot_one/delta_robot_one%20%20(9).PNG)
[<img src="https://raw.githubusercontent.com/deltarobotone/image_database/master/delta_robot_one/delta_robot_one%20(6).PNG" width="250">](https://raw.githubusercontent.com/deltarobotone/image_database/master/delta_robot_one/delta_robot_one%20(6).PNG)
[<img src="https://raw.githubusercontent.com/deltarobotone/image_database/master/delta_robot_one/delta_robot_one%20(7).PNG" width="250">](https://raw.githubusercontent.com/deltarobotone/image_database/master/delta_robot_one/delta_robot_one%20(7).PNG)
[<img src="https://github.com/deltarobotone/image_database/blob/master/black_edition/black_edition%20(1).PNG" width="250">](https://raw.githubusercontent.com/deltarobotone/image_database/master/black_edition/black_edition%20(1).PNG)
[<img src="https://github.com/deltarobotone/image_database/blob/master/black_edition/black_edition%20(2).PNG" width="250">](https://raw.githubusercontent.com/deltarobotone/image_database/master/black_edition/black_edition%20(2).PNG)
[<img src="https://github.com/deltarobotone/image_database/blob/master/black_edition/black_edition%20(3).PNG" width="250">](https://raw.githubusercontent.com/deltarobotone/image_database/master/black_edition/black_edition%20(3).PNG)
[<img src="https://github.com/deltarobotone/image_database/blob/master/black_edition/black_edition%20(4).PNG" width="250">](https://raw.githubusercontent.com/deltarobotone/image_database/master/black_edition/black_edition%20(4).PNG)
[<img src="https://github.com/deltarobotone/image_database/blob/master/black_edition/black_edition%20(5).PNG" width="250">](https://raw.githubusercontent.com/deltarobotone/image_database/master/black_edition/black_edition%20(5).PNG)
[<img src="https://github.com/deltarobotone/image_database/blob/master/black_edition/black_edition%20(6).PNG" width="250">](https://raw.githubusercontent.com/deltarobotone/image_database/master/black_edition/black_edition%20(6).PNG)
[<img src="https://github.com/deltarobotone/image_database/blob/master/black_edition/black_edition%20(7).PNG" width="250">](https://raw.githubusercontent.com/deltarobotone/image_database/master/black_edition/black_edition%20(7).PNG)

[<img src="https://raw.githubusercontent.com/deltarobotone/image_database/master/delta_robot_one/delta_robot_one%20(8).PNG" width="250">](https://raw.githubusercontent.com/deltarobotone/image_database/master/delta_robot_one/delta_robot_one%20(8).PNG)
[<img src="https://raw.githubusercontent.com/deltarobotone/image_database/master/delta_robot_one/delta_robot_one%20(12).PNG" width="250">](https://raw.githubusercontent.com/deltarobotone/image_database/master/delta_robot_one/delta_robot_one%20(12).PNG)
[<img src="https://raw.githubusercontent.com/deltarobotone/image_database/master/delta_robot_one/delta_robot_one%20(14).PNG" width="250">](https://raw.githubusercontent.com/deltarobotone/image_database/master/delta_robot_one/delta_robot_one%20(14).PNG)
[<img src="https://raw.githubusercontent.com/deltarobotone/image_database/master/delta_robot_one/delta_robot_one%20(17).PNG" width="250">](https://raw.githubusercontent.com/deltarobotone/image_database/master/delta_robot_one/delta_robot_one%20(17).PNG)
[<img src="https://raw.githubusercontent.com/deltarobotone/image_database/master/delta_robot_one/delta_robot_one%20(20).PNG" width="250">](https://raw.githubusercontent.com/deltarobotone/image_database/master/delta_robot_one/delta_robot_one%20(20).PNG)
[<img src="https://raw.githubusercontent.com/deltarobotone/image_database/master/delta_robot_one/delta_robot_one%20(22).PNG" width="250">](https://raw.githubusercontent.com/deltarobotone/image_database/master/delta_robot_one/delta_robot_one%20(22).PNG)
[<img src="https://raw.githubusercontent.com/deltarobotone/image_database/master/delta_robot_one/delta_robot_one%20(23).PNG" width="250">](https://raw.githubusercontent.com/deltarobotone/image_database/master/delta_robot_one/delta_robot_one%20(23).PNG)
[<img src="https://raw.githubusercontent.com/deltarobotone/image_database/master/delta_robot_one/delta_robot_one%20(27).PNG" width="250">](https://raw.githubusercontent.com/deltarobotone/image_database/master/delta_robot_one/delta_robot_one%20(27).PNG)
[<img src="https://raw.githubusercontent.com/deltarobotone/image_database/master/delta_robot_one/delta_robot_one%20(30).PNG" width="250">](https://raw.githubusercontent.com/deltarobotone/image_database/master/delta_robot_one/delta_robot_one%20(30).PNG)

# Copyright Notice

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.
