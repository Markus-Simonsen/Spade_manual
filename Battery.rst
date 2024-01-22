.. toctree::
    :glob:

Charging the battery
#######################

Connecting the battery and charger
==================================

To charge the batteries with the charger first connect the battery and charger. The outermost black wire on the battery, should be connected at the minus sign on the charger, the following wires indicate the different cells on the battery.

Setup the Charger
=================

No matter which charger you are using, there are a couple of settings that need to be set up. We will now go through each of these and how to set them up.

Select task
===========

The charger typically has three modes: Charge, discharge and
storage
The charge function is used to charge your batteries
and prepare them for use.
The storage function is used when you want to store
your batteries for an extended period of time and will prolong the lifetime of your batteries
The discharge function is for use before disposing of your batteries???

Battery type
============

The battery type can be found on your battery or with a quick google search, however commonly drones will use LiPo batteries.

Cell voltage
============

The cell voltage can be seen from the table below. The optimal fields to be in here are the grey ones. This means that you should be careful not to charge your batteries too high, and also not to discharge them to a too low level. Discharging you batteries too low can be avoided by using the battery alarm as explained later.
#image("images/image.png", width: 30%)

Cell count
==========

The cell count can also be found on your battery, it is indicated by a number followed by an S.

Current setting
===============

The current setting can be calculated from the battery’s c-charge rating. It is important to note that the C-charge rating and C-discharge rating is not the same. To be safe you can always use a C-charge rating of 1.
The formula for calculating the charge current can be seen in REF.
#set align(center)
$"Chargingrate[A]" = attach(C, br: "charge") · "batterycapacity[Ah]"$
#set align(left)

Example perhaps remove
======================

!["battery_w_specs"](images/Battery_w_specs.jpg)
An example can now be seen of a battery and its settings. Here the C-charge rating
cannot be seen on the battery, so it is just assumed to be 1 for the sake of safety. The
capacity can be found to be 4000 mAh, the number of cells is 4 and the discharge rating is
15 All of this corresponds to the settings seen in ??\*/

Connecting the parts
====================

After having safely charged the battery, the next step is to connect it to the drone and mount it on top as seen in the picture below.
!["dunno"](images/Drone.jpg)
Additionally it is also important to connect the battery alarm. This is connected as seen in picture REF PIC.
#image("images/413262176_1169059137389738_1210822416397961845_n.jpg", width: 10%)
When properly connected the observer will beep and start
showing the battery levels of the cells. The purpose of the battery observer is to alarm you
before the battery cells reach a critically low level, both to avoid damaging the batteries
and to avoid crashing. It does this by starting to beep at you when the battery level is too
low. At this point you should start trying to land the drone. When it starts beeping again,
the drone will soon crash and you should stay clear.
