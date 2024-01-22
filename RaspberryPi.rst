.. toctree::
    :glob:

Interacting with the Raspberry pi
#########################


Requirements
============

- Raspberry pi with the provided image
- common internet connection

Interacting with the ROS node
=============================

To interact with the microcontroller on the drone, and run programs on it, you will need to ssh into it. For this you will need a ethernet cable. Connect the microcontroller via an ethernet cable to your computer and open your terminal. Now you will need to find the IP-address, username and password of your microcontroller.
The IP-address can be found via scanning the network, that you share with the microcontroller this can be done in both linux and windows using the command.

`arp -a`

The username and password was chosen when you flashed the image onto the microcontroller.
The command to SSH into the raspberry pi is:
`ssh username@microcontroller-IP`

where username is exchanged with the username of your microcontroller and microcontroller-IP is replaced with the IP that you found.
