![](https://proptronix.co.uk/GitHub/GitHub_Logo.jpg)


------------

##### *Table of Contents*
- [Arduino Class-A Thermal Detonator](#arduino-class-a-thermal-detonator)
- [Video of the Prototype](#video-of-the-prototype)
- [Parts Required](#parts-required)
- [Software Required](#software-required)
- [Wiring Schematics](#wiring-schematics)
- [Programming Instructions](#programming-instructions)
- [3D Print STL Files](#3d-print-stl-files)
- [Licence](#licence)
- [Donation Button](#donation-button)

### Arduino Class-A Thermal Detonator

Arduino code and STL files for a Star Wars Class-A Thermal Detonator. 
This is a very basic build just to add some functionality to your Star Wars Thermal Detonator.
Easy to build with only minimal wiring required using cheap and readily available parts. 
The 3D STL files to print the Class-A Thermal Detonator to fit these electronics are included in the Download.

If you looking for for a more Screen Accurate Thermal Detonator with more Sounds check out my - [Thermal Detonator V2.10 Kit]([https://proptronix.co.uk/prop-electronics/td-electronics-kit-v2-10](https://proptronix.co.uk/product/thermal-detonator-electronics-kit/) "Thermal Detonator V2 Kit")

![](https://proptronix.co.uk/GitHub/Thermal_Detonator/TD-V1_GitHub_1.jpg)

![](https://proptronix.co.uk/GitHub/Thermal_Detonator/TD-V1_GitHub_2.jpg)

### Video of the Prototype

Check out my Videos of a 3D Printed Prototype with the Electronics Installed

YouTube Video 1- [Thermal Detonator V1.0 - Painted](https://youtu.be/5c1n84lufXM "Thermal Detonator V1.0 3D Printed and Painted")
YouTube Video 2- [Thermal Detonator V1.0 - Unpainted](https://youtu.be/FotBfXejvT4 "Thermal Detonator V1.0 - Unpainted")
YouTube Video 3- [Thermal Detonator V1.0 - Quick Build Instructions](https://youtu.be/IPiBrLOkG4U "Thermal Detonator V1.0 - Quick Build Instructions")


###  Parts Required

1 x Set of 3D STLFiles  - For 3D Printing the Class-A Thermal Detonator (Included FREE in the Download)

1 x [Thermal Detonator V1.0 PCB] - PCB for Components

1 x [Seeeduino XIAO] - 32bit 48MHz Microchip USB Type-C 

1 x [DFPlayer Mini MP3] - Mini MP3 Sound Player

1 x[PAM8403 Class-D Amplifier] - 2-channel, 3W, class-D Audio Amplifier

1 x [Micro SD-Card] - Minimum 512K

1 x [Mini Limit Lever Switch] - Used on the Slide Switch to Turn On/Off

1 x [Ball Tilt Sensor SW-520D] - (Activation Switch for Thermal Explosion

1 x [28mm Low Profile Speaker] - (Thermal Detonator Speaker

1 x [5mm Red LED] - Top LED - Power Indicator & LED Functions

1 x [5mm Red Flat Top LED Lens] - Top LED Power Indicator Cover

3 x [3mm LED] - Front 3 LED's - Can be any Colour but I use White or Yellow

7 x [JST PH-2.0 Male Lead] - Used to Connect the Components to the PCB

7 x [JST PH-2.0 Female Sockets] - Used to Connect the JST PH-2.0 Leads to the PCB

1 x [Header Pin Set]( - Used to for Connecting the Seeeduino, DFPlayer & PAM8403 to the PCB

3 x [3mm Metal LED Holder/Bezel]- Used for the Front LED's (Optional)

1 x [Slide Switch Screws] - Used to Secure the Top Slide Switch to the Top Dome

All parts listed above are available from my Online Shop , eBay, Amazon or AliExpress.

I also sell updated [Thermal Detonator V2.10 Electronics](https://proptronix.co.uk/product/thermal-detonator-electronics-kit/ "Thermal Detonator V2.10 Electronics") as a Self Build Kit or Pre-Built in my Shop. Better Screen Accurate STL Design with more functions on the Electronics.

###  Software Required

You will need the following Software & Libraries to install and setup the Thermal Detonator Arduino Code on the Seeeduino XIAO.
- The latest version of Arduino IDE - [Download from the Arduino Site](https://www.arduino.cc/en/Main/Software "Download from the Arduino Site")

**Adding Seeduino XIAO to Arduino IDE :**

Click on File > Preference, and fill Additional Boards Manager URLs with the URL below:
https://files.seeedstudio.com/arduino/package_seeeduino_boards_index.json

**Arduino Libraries Needed:**

- SoftwareSerial - Included in the Download
- DFRobotDFPlayerMini - Included in the download

**TDTroniX V1.0 Arduino Thermal Detonator Code:**

- Arduino-Thermal-Detonator-V1.0.ino - Included in the Download

###  Wiring Schematics

![](https://proptronix.co.uk/GitHub/Thermal_Detonator/TD-V1_GitHub_4.jpg)
![](https://proptronix.co.uk/GitHub/Thermal_Detonator/TD-V1_GitHub_3.jpg)

###  Programming Instructions

1. Copy the Two Included Libraries (SoftwareSerial & DFRobotDFPlayerMini ) into your Arduino Libraries Folder.

2. Run the Arduino IDE Application

3. File Open and locate the Arduino-Thermal-Detonator-V1.0 Directory and open the Load the Arduino-Thermal-Detonator-V1.0.ino file.

4. Select Tools: Board: and select Seeeduino XIAO

5. Select Tools: Port: and Select the COM Port your Seeeduino XIAO board is plugged in to.

6. Select Tools: Programmer: and choose AVRISP mkII.

7. Upload the Thermal-Detonator-V1.0.ino code to the board

You should now have a functioning Thermal Detonator

### 3D Print STL Files
The download also includes a set of Thermal Detonator V1.0 3D Printable STL Files. These are adapted from the Free Files that are available from [Thingiverse](https://www.thingiverse.com/thing:809004 "Thingiverse") by Oubliette. I changed some of the design and added the Electronics Holder.

![](https://galacticprops.co.uk/GitHub/Thermal_Detonator/TD-V1_GitHub_5.jpg)

###  Licence

This work is licensed under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License.
To view a copy of this license, visit https://creativecommons.org/licenses/by-nc/4.0/


### Donation Button
[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.com/donate/?hosted_button_id=PEK9F5JV4Q6NL) Please feel free to donate a cup of coffee if you find this code useful. Thank You
