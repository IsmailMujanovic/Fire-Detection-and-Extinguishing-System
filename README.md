# Fire-Detection-and-Extinguishing-System

Video demonstration link: https://www.youtube.com/watch?v=-E1TRJzHluY

A smart system for detecting and automatically extinguishing fires created with a RP2040 Raspberry Pi.
- The system uses an LM35 temperature sensor and a flame sensor to detect fires.
- When temperature thresholds are exceeded or flames are detected, a water pump is automatically activated to extinguish the fire.
- The current temperature and corresponding messages are displayed on an LED display, giving the user real-time insight into the surrounding environment.

## Description
- Our smart fire detection and automatic extinguishing system aims to increase safety in enclosed spaces through continuous monitoring of temperature and fire presence, with the possibility of timely response without the need for human intervention. The system uses an LM35 temperature sensor and a flame sensor to detect open flames, thus monitoring the environment in real time.

- In case of exceeding predefined temperature thresholds or flame detection, the system automatically activates the water pump using a relay, in order to carry out a quick and localized fire extinguishing intervention. After the action is completed, the system returns to a passive state and continues monitoring.

- All information about the current state, including temperature, sensor status and warnings, is displayed on the LED display, allowing the user to quickly see the system status. In addition to local data display, the system also allows remote monitoring and control via the MQTT protocol, which sends data about measurements and alarm conditions to the MQTT application on the mobile device.

- Through the application, the user can monitor the system status in real time, view historical data, and manually start or stop the water pump. This manual control option is particularly useful in case of simulation, system testing, or when the user wants to perform additional checks or interventions.
