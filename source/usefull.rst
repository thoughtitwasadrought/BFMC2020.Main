Usage and Usefull link
======================

In this section, you can find some useful links and some documentations for basic
raspberry usage and image processing. 

Usage of Raspberry Pi 
-----------------------------

Getting started with Raspberry Pi
`````````````````````````````````````
In this tutorial you will find out the way in which you can **start up** your 
system and use it as a **standalone** computer. Links: 

    - `Setting up your Raspberry Pi`_

.. _`Setting up your Raspberry Pi`: https://projects.raspberrypi.org/en/projects/raspberry-pi-setting-up 

Accessing the terminal using a serial cable	
````````````````````````````````````````````
This option for connecting to your Raspberry Pi is useful in the case in which 
you want to connect to its terminal. By using the serial cable (e.g. https://www.ftdichip.com/Products/Cables/USBTTLSerial.htm) 
you can connect to your system for performing initial setup, such as WLAN SSID 
and password. You should have the Serial Console enabled for being able to 
connect to the Raspberry Pi in this way. This can be done easily by editing 
the config.txt file of the system (point a below). Below you can find some 
useful resources that describe the steps required for connecting to the terminal in this way.

    a. https://learn.sparkfun.com/tutorials/headless-raspberry-pi-setup/serial-terminal
    #. https://makezine.com/2014/02/28/talking-to-the-raspberry-pis-serial-console-with-an-ftdi-breakout-board/
    #. https://www.thepolyglotdeveloper.com/2017/02/connect-raspberry-pi-pi-zero-usb-ttl-serial-cable/

Configuring your Raspberry Pi
``````````````````````````````
The Raspberry Pi’s default operating system uses a range of configuration parameters 
that are read when the computer boots from the microSD card. These are stored in the 
**config.txt** document, found in the /boot/ folder. By editing this document one could, 
for example, adjust the way the display is detected and the desktop displayed or overclock 
the Raspberry Pi (or return to default clock settings). A useful setting is the enabling 
of the Serial Console so that the Raspberry Pi’s terminal can be accessed using a serial 
connection. There is also the possibility to use the **raspi-config** application, in case 
one has already established a connection with the system (system operating either as a 
standalone computer or as a remote device).

    a. Editing the **config.txt** file:
        - https://www.makeuseof.com/tag/edit-boot-config-file-raspberry-pi 
        - https://elinux.org/R-Pi_configuration_file
    b. Console based **raspi-config** application:
        - https://www.raspberrypi.org/documentation/configuration/raspi-config.md 

Setting up WLAN
```````````````
For a more facile way of connecting to the Raspberry Pi, one could access its terminal 
or Desktop wirelessly, provided that both the systems (Raspberry Pi and remote computer) 
are connected to the same network. Therefore, a wireless connection has to be set up for 
the Raspberry Pi. The tutorial given here helps the user to perform this action.

    - `Setting up WLAN in command line`_ 

.. _`Setting up WLAN in command line`: https://www.raspberrypi.org/documentation/configuration/wireless/wireless-cli.md


Getting your Raspberry Pi IP address
`````````````````````````````````````

The Raspberry Pi will receive an IP address when it is connected to a network, 
either wirelessly or using an internet cable. In both cases, for connecting to 
the system, its IP address has to be known. The links below specify the way in 
which this address can be retrieved.

    - https://www.raspberrypi.org/documentation/remote-access/ip-address.md
    - Using the terminal (connected over serial) - https://raspberrypi.stackexchange.com/questions/1409/easiest-way-to-show-my-ip-address


Connect to Raspberry Pi using VNC
``````````````````````````````````
VNC is a graphical desktop sharing system that allows you to remotely control 
the desktop interface of one computer (running VNC Server, in our case Raspberry Pi) 
from another computer or mobile device (running VNC Viewer). Sometimes it is 
not convenient to work directly on the Raspberry Pi, and the tutorial below 
describes how work on it from another device by remote control.

    - https://www.raspberrypi.org/documentation/remote-access/vnc

Connect to Raspberry Pi using WinSCP
````````````````````````````````````
WinSCP is a free SFTP, SCP and FTP client for Windows. WinSCP is a convenient 
way to present, copy and manage files and folders on a Raspberry Pi from a 
remote device. The links below describe the way in which one can connect to 
a Raspberry Pi using WinSCP.

    - https://www.behind-the-scenes.co.za/using-winscp-to-connect-to-a-raspberry-pi
    - https://rasspberrypi.wordpress.com/2012/09/03/enabling-ssh-on-raspberry-pi-and-using-putty-and-winscp    
    - https://raspberry-projects.com/pi/software_utilities/file-sharing/transfering-files-from-windows-pcs

Running Python scripts on Raspberry Pi
`````````````````````````````````````````
Python is programming language that can be used for developing applications 
on the Raspberry Pi. The links below represent a good starting point for this 
type of applications.

    - https://www.raspberrypi.org/documentation/usage/python
    - https://www.digikey.com/en/maker/blogs/2018/how-to-run-python-programs-on-a-raspberry-pi




Linux Images for Raspberry Pi 
------------------------------

Here you can find some operating system images. Each images are Rapbian Buster, only the installed packages differs.
We prepared four version:
    - `Raspberry Buster Lite Basic  <https://mega.nz/#!8SY3hIyR!Q18c3AUF50h8X6EQOMOBicS5rYtMA0wpBWMqCcwMdpI>`_
        It's a **minimal** image based on Debian Buster with some python libraries: PiCamera, PySerial. 
    - `Raspberry Buster Desktop Basic  <https://mega.nz/#!1XJXgahS!1pJK0r6ocunz4_EpSWVgSmedBuQIEO92xYwS4QQD3VQ>`_
        It's a **desktop** version based on Debian Buster with same python libraries installed: PiCamera, PySerial.
    - `Raspberry Buster Lite ROS <https://mega.nz/#!FKAjEIST!-ojWoB3Fg0t6GY0ouhhrbUia0DfWRoO7VE566u_6eUc>`_
        It's based the above mentioned **minimal** image. We installed **ROS** Kinetic version 1.12.14. 
        We added a new user with name 'ros' and password 'raspberry', where the ros environment is initialized. 
    - `Raspberry Buster Desktop ROS  <https://mega.nz/#!ELZhgKDB!sqhzVtXrpXuBw4pB9AiVWRCJ9PrS7vh74KRFrChwNq4>`_
        It's based the above mentioned **desktop** image. We installed **ROS** Kinetic version 1.12.14. 
        We added a new user with name 'ros' and password 'raspberry', where the ros environment is initialized.

    



Image processing links
------------------------
In this part, you can find some useful link for image processing on Raspberry pi.

Our records: 
    - Video on the old test track in 2019 `[link] <https://mega.nz/#!IPIVwAbK!fi66mVUr7g0ghC0e7_Ly-ApgCeO6QZopkvaqKtnHL58>`_ 

Basic Python libraries:

    - `PiCamera Python Library`_ 
    - `Opencv Official Documentation`_

Articles for Road Sign Recognition:

    - A. Mogelmose, M. M. Trivedi and T. B. Moeslund, "Vision-Based Traffic Sign Detection and Analysis for Intelligent Driver Assistance Systems: Perspectives and Survey," 
      in IEEE Transactions on Intelligent Transportation Systems, vol. 13, no. 4, pp. 1484-1497, Dec. 2012. [`link <https://ieeexplore.ieee.org/document/6335478/>`_]
    - S. Maldonado-Bascon, S. Lafuente-Arroyo, P. Gil-Jimenez, H. Gomez-Moreno and F. Lopez-Ferreras, "Road-Sign Detection and Recognition Based on Support Vector Machines," 
      in IEEE Transactions on Intelligent Transportation Systems, vol. 8, no. 2, pp. 264-278, June 2007. [`link <https://ieeexplore.ieee.org/document/4220659>`_]
    - Y. Han and E. Oruklu, "Traffic sign recognition based on the NVIDIA Jetson TX1 embedded system using convolutional neural networks," 
      2017 IEEE 60th International Midwest Symposium on Circuits and Systems (MWSCAS), Boston, MA, 2017, pp. 184-187. [`link <https://ieeexplore.ieee.org/document/8052891>`_]

Articles for Lane detection and tracking:
    - R. Danescu, S. Nedevschi, M. M. Meinecke and T. B. To, "Lane Geometry Estimation in Urban Environments Using a Stereovision System," 
      2007 IEEE Intelligent Transportation Systems Conference, Seattle, WA, 2007, pp. 271-276. [`link <https://ieeexplore.ieee.org/document/4357686>`_]
    - R. Labayrade, J. Douret and D. Aubert, "A multi-model lane detector that handles road singularities," 
      2006 IEEE Intelligent Transportation Systems Conference, Toronto, Ont., 2006, pp. 1143-1148. [`link <https://ieeexplore.ieee.org/document/1707376>`_]
    - Yue Dong, Jintao Xiong, Liangchao Li and Jianyu Yang, "Robust lane detection and tracking for lane departure warning," 
      2012 International Conference on Computational Problem-Solving (ICCP), Leshan, 2012, pp. 461-464. [`link <https://ieeexplore.ieee.org/document/6384266>`_]

.. _`PiCamera Python Library`: https://picamera.readthedocs.io/en/release-1.13
.. _`Opencv Official Documentation`: https://docs.opencv.org/4.1.2