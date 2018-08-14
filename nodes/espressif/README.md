all the setting up of esp01, esp12 and esp32 goes here.
esp01 is a 3v3 logic chip(/module).esp12 is used from a wemos board.And the "ESP32 DEV KIT" board is used for esp32.These two boards have onboard 5v to 3v3 regulators and can be pwered directly over micro usb cable.
The setting up of the esp01 and esp12 are pretty much the same and easy.The boards must be installed in the boards list in the arduino IDE. 
However, the setting up of esp32 is a bit complicated.follow the video here to do it correctly.

once everything is done, install MQTT libraries like the PubSubClient in the Arduino IDE.MQTT is the main protocol used in this project that links all the nodes to the server.This is because it's a light weight protocol and also reliable.Other protocols like HTTP can also be used based on the application.
