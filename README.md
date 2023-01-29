# OlyU

The OlyU-V is a variant of the OlyU-Small (which, in turn, is a variant of the Model-U).

The OlyU-V is designed for PhoZL and PhobGCCv2.0.3+ to allow for USB data connection, GCC comms, and PhobVision composite video output over a 24-pin USB C connector. 

To access the PhobVision capability, you will need both a PhobGcc equipped with the OlyU-V breakout board as well as the Phongle board **(add link)** and a superspeed-capable USB C to C cable.

To install the OlyU-V in a standard PhobGcc controller, follow the instructions further down on the page and in addition run a wire from the PhobVision video out pin on the PhobGcc motherboard to the pin on the OlyU-V on the end farthest from the USB port.

![image](https://user-images.githubusercontent.com/95242582/215300712-6a05d7f6-3ab4-4d6f-ae4c-39f524cc35a7.png)


## (The below images are from the OlyU for context and ordering information but are not exactly the same as the OlyU-V)

### Type 1 - OlyU-Small
![image](https://raw.githubusercontent.com/sean44104/OlyU/main/Images/OlyU-Small.png)
### Type 2 - OlyU-Big
![image](https://raw.githubusercontent.com/sean44104/OlyU/main/Images/OlyU-Big.png)

# Overview
Both of these boards feature 8 pads. 6 of these pads connect to the GameCube Controller's standard 6 connections for the main cable. The other 2 pads are for USB Data + and -
The shape and alignment of these pads are designed so that installation is easy and does not require any wire stretching across the board. These boards are compatible with PhobGCC and OEM gamecube controllers, but the USB data pins are specifically designed for the PhobGCC and PhoZL (https://github.com/sean44104/phozl)

### Install
![Small](https://raw.githubusercontent.com/sean44104/OlyU/main/Images/OlyU-Small-Install.png)
![Small](https://raw.githubusercontent.com/sean44104/OlyU/main/Images/OlyU-Small-PadAlign.png)
![Big](https://raw.githubusercontent.com/sean44104/OlyU/main/Images/OlyU-Big-Install.png)
![Big](https://raw.githubusercontent.com/sean44104/OlyU/main/Images/OlyU-Big-PadAlign.png)

# PCB Differences
The OlyU small version is designed to be installed so that the USB-C port is sandwiched between the main pcb and the OlyU pcb. This way, you can use 2mm pin headers for the installation. It has also been reshaped to perfectly fit with the Gamecube Ultimate's shell design
![image](https://raw.githubusercontent.com/sean44104/OlyU/main/Images/OlyU-Small-Shell.png)

The OlyU big version is shaped just like a standard Model-U. Instead of the USB-C port being in between the 2 PCBs, the order goes PCB,PCB,Port. The PCB is designed this way to allow for easy installation into OEM Gamecube Shells with minimal cutting. However, this makes installation slightly more tricky
![image](https://raw.githubusercontent.com/sean44104/OlyU/main/Images/OlyU-Big-Shell.png)

Both boards have their USB Data pads aligned perfectly with the main PhoZL and PhobGCC PCB

# NOTE
When ordering these boards on JLCPCB, make sure that your SMT Assembly is BOTTOM for OlyU-Small and TOP for OlyU-Big. Every other setting can be left default, and the finish can be whatever you prefer

# License
This project is licenced under the GNU GPL Version 3. [See the included LICENSE file for details](LICENSE).


# Crane's Lab

Model-U is a circuit board for adding USB-C to custom controllers originally created by Crane.
Please support him here:
https://www.paypal.com/donate/?hosted_button_id=NFDEML5FKR8N8
