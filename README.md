# IoT-Implementation-of-DHT11-Temperature-and-Humidity-sensor-using-NodeMCU-and-Thingspeak
Implementing a Temperature and Humidity Sensor using IoT so that the data can be handled remotely over the Network.

DHT11: A sensor used to measure temperature and relative humidity in the range of 0℃-50℃ and 20%-90% RH respectively. It has either 3 pins or 4 pins. For 3 pins, the pins are Vcc(Input), Data Pin and GND(Ground) respectively. For 4 pins, the pins are Vcc(Input), Data Pin, useless pin and GND(Ground) respectively.

![DHT11 Sensor](https://www.electronicwings.com/public/images/user_images/images/NodeMCU/NodeMCU%20Interfaces/NodeMCU%20DHT11/DHT11.png)

NodeMCU ESP8266: It is an open-source Lua based microcontroller running on the ESP8266 WiFi SoC and a hardware based on the ESP12 module. NodeMCU is widely used for IoT projects.

![NodeMCU](https://components101.com/asset/sites/default/files/component_pin/NodeMCU-ESP8266-Pinout.jpg)

## Connection Diagram

![Connection Digram]https://www.electronicwings.com/public/images/user_images/images/NodeMCU/NodeMCU%20Interfaces/NodeMCU%20DHT11/NodeMCU_DHT11_Interfacing.png)

ThingSpeak: It is an IoT Analytics Platform used to analyze data collected from sensors connected over a WiFi network through any microcontroller or even a microprocessor.

## Steps to use ThingSpeak:

Step 1: Open and create an account.
Step 2: Click on New Channel. Give a name to the channel with Field 1 as Temperature and Field 2 as Humidity. Save the channel.

Step 3: Click on API Keys and copy the Write API Key. Paste the key in the place mentioned in the code within quotes(“”).


## Coding

For the coding part, we will be using C Programming Language in the Arduino IDE.
Download the DHT11 sensor library ZIP file from this link:

Add this library to the Arduino IDE. Make sure that there is no other DHT11 sensor library already installed and added to the Arduino IDE. If there is present, delete those and install the one from the link I have provided.


