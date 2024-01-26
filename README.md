Ultrasonic.NodeMCU_Relay
Uploading Video 2024-01-26 at 17.39.34 (1) (1).mp4…
Ultrasonic.NodeMCU_Relay

Overview:This project demonstrates the creation of Ultrasonic.NodeMCU_ relay esp8266.These are the physical objects embedded with sensors, actuators, and connectivity to collect and transmit data,sensors gather data from the environment (e.g., temperature, humidity, motion), while actuators perform actions based on received data.

Features:
   
     1.Easy Electronic ESP8266 NodeMCU Based 4-Channel Relay.
     2.Ultrasonic sensor with a NodeMCU.
     3.The relay is triggered based on the distance measured by the ultrasonic sensor.
     4.Distance-Based Control

Prerequisites:

Before running the project, make sure you have the following installed:

     1. Arduino IDE:
        Install the Arduino IDE on your computer. You can download it from the official Arduino website: Arduino Software.
      2.ESP8266 Board Support:
         Add support for the ESP8266 boards to the Arduino IDE.
          Open the Arduino IDE.
          Go to "File" > "Preferences."
          In the "Additional Boards Manager URLs" field, add the following URL: 
          http://arduino.esp8266.com/stable/package_esp8266com_index.json
          Click "OK" to close the preferences window.
          Go to "Tools" > "Board" > "Boards Manager."
           Search for "esp8266" and install the "esp8266" platform.
           Select your NodeMCU board from the "Tools" > "Board" menu.

Components Needed:

      1.NodeMCU (ESP8266) board
      2.Ultrasonic sensor (e.g., HC-SR04)
      3.Relay module
      4.Jumper wires
      5.Power source (USB power supply for NodeMCU)

Wiring:

      1.Connect the VCC of the ultrasonic sensor to the 5V pin on the NodeMCU.
      2.Connect the GND of the ultrasonic sensor to the GND pin on the NodeMCU.
      3.Connect the Trigger pin of the ultrasonic sensor to a digital pin (e.g., D1) on the NodeMCU.
      4.Connect the Echo pin of the ultrasonic sensor to another digital pin (e.g., D2) on the NodeMCU.
      5.Connect the VCC and GND of the relay module to the 5V and GND pins on the NodeMCU.
      6.Connect the Signal (IN) pin of the relay module to a digital pin (e.g., D3) on the NodeMCU.

