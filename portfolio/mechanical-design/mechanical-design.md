## Tethered Quadcopter

![tethered-quadcopter-overview](/portfolio/mechanical-design/tethered-quadcopter/tethered-quadcopter-overview.png "Tethered Quadcopter Overview")

![tethered-quadcopter-full-exploded-view](/portfolio/mechanical-design/tethered-quadcopter/tethered-quadcopter-full-exploded-view.png "Tethered Quadcopter Full Exploded View")

![tethered-quadcopter-main-stack](/portfolio/mechanical-design/tethered-quadcopter/tethered-quadcopter-main-stack.png "Tethered Quadcopter Main Stack")

![tethered-quadcopter-nav-stack](/portfolio/mechanical-design/tethered-quadcopter/tethered-quadcopter-nav-stack.png "Tethered Quadcopter Navigation Stack")

![tethered-quadcopter-arm](/portfolio/mechanical-design/tethered-quadcopter/tethered-quadcopter-arm.png "Tethered Quadcopter Arm")

![tethered-quadcopter-propulsion](/portfolio/mechanical-design/tethered-quadcopter/tethered-quadcopter-propulsion.png "Tethered Quadcopter Propulsion")

![tethered-quadcopter-fcu-stack](/portfolio/mechanical-design/tethered-quadcopter/tethered-quadcopter-fcu-stack.png "Tethered Quadcopter FCU Stack")

![tethered-quadcopter-pdb-esc-stack](/portfolio/mechanical-design/tethered-quadcopter/tethered-quadcopter-pdb-esc-stack.png "Tethered Quadcopter PDB ESC Stack")

![tethered-quadcopter-rpi-stack](/portfolio/mechanical-design/tethered-quadcopter/tethered-quadcopter-rpi-stack.png "Tethered Quadcopter RPi Stack")

**Full document of this design is available upon request.**

This UAV is designed to perform fly-by- wire flight in GPS-denied environment with a tether cable. 

This UAV is a proof-of-concept done to demonstrate UAV flight with its dynamics altered by a tether 
cable.

Control of this UAV is achieved mainly through Raspberry Pi and Matek H743 Mini as flight controllers, ROS and ArduCopter as firmware, and brushless DC motor controlled by electronic speed controller as actuators. 

Telemetry data is transmission from the UAV to the ground station is transmitted through RF
and WiFi. Power is transmitted from ground station to UAV through the tether cable.

The frame is built with combination of plywood as the plates, aluminium as spar, PLA (polylactide) as structural load part, and nuts, bolts, and washers of various sizes as joiner. 

## Aerial Mapping Quadcopter

![aerial-mapping-quadcopter-isometric-view](/portfolio/mechanical-design/aerial-mapping-quadcopter/aerial-mapping-quadcopter-isometric-view.png "Aerial Mapping Quadcopter Isometric View")

![aerial-mapping-quadcopter-exploded-view](/portfolio/mechanical-design/aerial-mapping-quadcopter/aerial-mapping-quadcopter-exploded-view.png "Aerial Mapping Quadcopter Exploded View")

**Full document of this design can be accessed [here](https://github.com/Sibernetika-Teknologi-Industri/uav-cad).**

This UAV is designed to perform aerial mapping in outdoor environment.

The main idea behind this design is to produce a UAV for aerial mapping. 

Quadcopter configuration is chosen as it was deemed the best tradeoff between stability and power efficiency.

Control of this UAV is achieved mainly through Raspberry Pi and Pixhawk as flight controllers, ROS and ArduCopter as firmware, and brushless DC motor controlled by electronic speed controller as actuators.

The camera used is Logitech C310 and image processing is done with ROS and OpenCV. 

Telemetry data transmission from the UAV to the ground station is transmitted through RF and WiFi. 

A LiPO battery, which is attached to the UAV acts as energy source. 

The frame is built with combination of plywood as the plates, aluminium as spar, PLA (polylactide) as structural load part, and nuts, bolts, and washers of various sizes as joiner. 

## Ornicopter Propulsion Mechanism

![ornicopter-propulsion-mechanism-isometric-view](/portfolio/mechanical-design/ornicopter-propulsion-mechanism/ornicopter-propulsion-mechanism-isometric-view.png "Ornicopter Propulsion Mechanism Isometric View")

![ornicopter-propulsion-mechanism-exploded-view](/portfolio/mechanical-design/ornicopter-propulsion-mechanism/ornicopter-propulsion-mechanism-exploded-view.png "Ornicopter Propulsion Mechanism Exploded View")

This mechanism is designed for proof-of-concept of a helicopter propulsion system without tail-rotor.

The main idea behind this mechanism is replacing yaw control of the tail-rotor with flapping motion on each blade. 

This flapping motion will induce torque on the mechanism, which is usually done by tail-rotor. 

One swashplate controls the pitch on each blade and the other one controls the flapping motion.

Actuation is achieved through a motor and 3 servomotors. 

The motor controls the RPM and the servos control the swashplates, which controls the pitch and flapping motions. 