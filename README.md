Summary of Idea :

This project presents an innovative approach to automate and optimize plant watering using artificial intelligence (AI) and Internet of Things (IoT) technologies. The system incorporates NodeMCU (ESP8266) as the IoT device, various sensors for monitoring environmental conditions (soil moisture, temperature, humidity, and rainfall), an LCD display for local feedback, and cloud integration through ThingSpeak. Additionally, a machine learning algorithm running on a laptop analyzes historical sensor data from ThingSpeak, predicting optimal watering conditions and controlling the water pump and valves accordingly.
The NodeMCU gathers real-time data from the soil moisture sensor, DHT11 sensor (for temperature and humidity), and a rain sensor. The information is displayed locally on an OLED screen and transmitted to ThingSpeak for cloud storage. The cloud-stored data serves as input for a machine learning model on a laptop. This model, trained on historical patterns, predicts the watering requirements based on environmental conditions.
The machine learning predictions influence the decision-making process regarding the water pump and valve control. The NodeMCU receives commands from the cloud, adjusting watering parameters based on the model's recommendations. This closed-loop system ensures adaptive and efficient plant watering, optimizing resource usage and promoting plant health.
Furthermore, a mobile app provides a user-friendly interface to monitor real-time sensor data, receive alerts, and manually control the watering system. The integration of AI, IoT, and cloud technologies enhances the scalability, flexibility, and intelligence of the plant watering system, contributing to sustainable and automated agricultural practices.


Programming Languages Expertise:

Required knowledge on: Embedded C/ C++, Python Scripting



Software Used :

Arduino IDE
IDLE
MIT APP INVENTOR
ThingSpeak Cloud platform
Hardware / Components Used
NodeMCU
Moisture Sensor
DHT11 Sensor
LCD
Motor Driver
Water Pump
Power Supply 
PCB
Connecting Wires


Flowchart:

![image](https://github.com/abhiram-0301/Agriculture-management/assets/149863256/5f8d3dae-ef52-4be0-a9f5-cca4810da9dd)


