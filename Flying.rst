.. toctree::
    :glob:

Flying
#########

Requirements
============

- Completed previous tutorials
- Installed QGroundControl for PX4
- Remote control

Connecting to the drone
========================
To connect to the drone, you need to plug the telemetry module into your computer's USB port. Connect your drone to your battery and open QGroundControl. Once QGroundControl has connected to your drone it should change from disconnected to connected in the top left corner.

Calibration
===========
After opening QGroundControl, press the Q in the top left corner and enter vehicle setup. Then enter sensors and follow the guides for calibrating the drone’s sensors.

After this enter the radio section and calibrate your Remote Controller (RC).

Then enter the section Flight Modes, and make sure to both set up the flight modes, that you want to use, and also select a channel to use as an emergency kill switch. So that you can shut off your drone if it flies too far away. You can see which channels correspond to which actions on the remote control, by pressing the different buttons on the remote controller, while looking at the Radio section in QGroundControl.

Flying
======
Before flying you should make sure that everything on the drone is fastened, so that it will not interfere with the propellers. After this go outside and arm your drone, then test that the kill switch properly shuts it down. After this you should be ready to fly with your remote controller.

Remeber that you have several flight modes to choose from, where each flight mode changes how the sticks on the RC affect the drone.
