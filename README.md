# GMHS Ejecting Robot
Here is the Arduino code for the ESP32 camera module.


## Items Required:
An ESP32 Camera and Motherboard

USB-C to USB-C cable 

Arduino IDE 2.3.5

## Steps

### 1. Preperations 
Make sure you have the Arduino IDE Software installed. If you don't, you can install it from [Here](https://www.arduino.cc/en/software#ide).
After the Arduino software is installed, find the Boards Manager Tab located [Here](https://github.com/user-attachments/assets/d7533749-8fac-499c-8bce-e588cd6b9164). Click on that and search for [esp32 by Espressif Systems](https://github.com/user-attachments/assets/7aa59023-dd5f-43a7-a2a0-c1d1eeabaea1).

### 2. Setting Up The Personal Hotspot
For this Robot to work, it uses a Personal Hotspot to run. To set it up, open up the Internet settings on your Windows device and find the Personal Hotspot found [here](https://github.com/user-attachments/assets/5973d296-c655-422a-bd56-e67e78dbccd1). After you have opened it up, go to properties and make the name and password your own if you would like, then leave this open for later.

### 3. Installing the Code and Adding your Network
After you have made the Network its time to install the code, go to the [Releases](https://github.com/BroganW25/GMHS-Ejecting-Robot/releases/tag/Release) and download the .ino file and open it up in the IDE software. After that plug in your ESP 32 using a cable and select the Com port and the board you are using [image](https://github.com/user-attachments/assets/ef6b570e-71ca-4484-92ff-d5d810c6b783). After you have selected the Board find the SSID and Password section in the [code](https://github.com/user-attachments/assets/d83e3e88-30f9-42a2-acbf-0114bb3bbc50). And then replace "Your network Name" and "Your Network Password" with your SSID and Password from the Previous step. After you have done t







