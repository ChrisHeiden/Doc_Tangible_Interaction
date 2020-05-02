# Tangible Interaction Project
Experiencing the creation of music often depends on having a professional music instrument and the knowledge of how to interact with it to create music. Analog music instruments like a guitar can be used to create guitar music. The instrument itself cannot adapt to a situation or the player wants to play different instrumental sounds with a guitar, for example. On the other hand, a digital piano can do so, and can stimulate different instruments; however, the digital piano itself does not change. By using the token and constraints approach of tangible user interfaces, it is possible to change the look and sound of instruments by interacting with them. This has been tried to accomplish in this semester project at the Bauhaus University. Therefore, it deals with different approaches of tangible interaction and how it can be designed theoretically and practically to design an interface that can be used to simulate different sounds and instruments. Users’ advice is used to give the group information about how people use different objects and how they think it should sound by interacting with them.

## Installation 
### ESP8266
First of all, you have to enter this
```
http://arduino.esp8266.com/stable/package_esp8266com_index.json
```

to your Preferences. Therefore, click on "File" and search for your
"Preferences". There, enter the link to the "additional board management_URL".
After doing so, click on board managment and search for ESP8266. Install it.
This will take some time. However, then you will find all ESP8266 boards in your 
board lib and many examples for it.
In this project, we use two ESP8266 node Version 1.0 boards.

### Adding libraries 
To upload the code, you have to install following external libraries:

* [VL53L1X](https://github.com/pololu/vl53l1x-arduino) 


After downloading, add these libraries to the Arduino IDE. This
can be done by 

```
sketch >> add library >> add ZIP. library
```

The other libaries like:

* Adafruit_Sensor
* Adafruit_LSM303_U
* Adafruit_L3GD20_U
* Adafruit_9DOF
* MFRC522
* MIDI by Forty Seven Effects


must be added as well. Therfore, go to "sketch" click on "add library" and
then on "manage libraries". There, you can search for all these libs. Please,
download all of them. If the system asks you if you want to download linked 
libaries, you click "yes, all".


## Wiring 
![Image of the wiring](/original_Images/Wirewiring_Soldering/Sketches/Tangible_Interfaces_Project_5.png)

## Process and Images
The process of the project has been documented with images. These can be found in the folder 'original_Images'.

## Coding
The executed code can be found in the folder 'Code'.