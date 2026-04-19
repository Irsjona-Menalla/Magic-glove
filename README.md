# Magic-glove
A wearable environmental sensing glove that provides real-time proximity and ambient condition feedback for interactive or assistive use.. I will show you how I made my glove and how you can also. It combines proximity detection and ambient sensing (temperature and humidity) to create an interactive and extensible platform.
This project can be used as:
A basic assistive tool for obstacle awareness
A wearable environmental monitoring device
A foundation for gesture-based control systems

Components:
Arduino (Uno/Nano)
Proximity sensor (e.g., ultrasonic or IR)
Temperature & humidity sensor (e.g., DHT11/DHT22)
Wires, resistors, glove base
Breadboard(unless you solder)
Glove (thick glove )
Button

How It Works

Each sensor is placed on the glove (fingertips or back of the hand).
The Arduino collects data continuously:

Proximity sensor detects objects within a certain range
Temperature & humidity sensor measures environmental conditions

The data can be:

Sent to Serial Monitor
Displayed on an external interface (optional)
Setup
Connect all sensors to the Arduino
Upload the code using Arduino IDE
Open Serial Monitor to view data

Future Improvements
Gesture recognition system
Wireless communication (Bluetooth/WiFi)
Mobile or web dashboard
AI-based interpretation of sensor data 

SIMPLE DESIGN DEMO :
<img width="739" height="627" alt="image" src="https://github.com/user-attachments/assets/d19c3774-f55f-425f-9d97-4546976dfd45" />

This is my personal project and how it looks like 

<img width="497" height="628" alt="image" src="https://github.com/user-attachments/assets/56dd80aa-8912-4b13-81d3-17cf7490a9b0" />

Clear picture of the wiring:

<img width="548" height="740" alt="image" src="https://github.com/user-attachments/assets/51fcf056-da9d-4a48-ac62-1d8e58a2bb9c" />
Check out the code for the spcific pins I used , but you can use any pins you want.


