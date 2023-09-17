# LiyaT_23
# Flood Detection and Management System

## Project Description
Floods have created a devastating impact on communities worldwide, causing extensive damage to homes, infrastructure, and critical resources such as clean water and food supplies. The lack of early warning systems and flood prediction capabilities has been a major contributing factor to these tragic outcomes, resulting in a significant loss of human life and economic costs. To address this critical issue, an innovative IoT framework has been proposed to monitor water bodies using IoT devices. These devices will transmit frequent updates on temperature, humidity, rainfall, and water levels, which will be used to carry out a range of essential functions such as forecasting flood risks and implementing timely emergency responses. As soon as abnormal water levels are detected, an alert system will be activated, and relevant information will be transmitted to local residents to help them make informed decisions and take prompt action. By providing real-time information and guidance, this framework has the potential to save countless lives and reduce the devastating impact of floods on communities around the world.

 ## Key Features
-**Real-time Monitoring:** The system continuously monitors water bodies using IoT devices that collect data on temperature, humidity, rainfall, and water levels in real-time.

-**Flood Risk Forecasting:** Utilizing the gathered data, the system employs forecasts flood risks, enabling proactive flood management.

-**Emergency Response:** When abnormal water levels are detected, an alert system is automatically activated. 

## Hardware
- Arduino Uno
- NodeMCU
- DHT11 Sensor
- Ultrasonic Sensor
- Water Level Sensor
- GSM Module

## Software
- [Arduino IDE](https://www.arduino.cc/en/software)
- [Proteus](https://www.labcenter.com/)
- [Tinkercad](https://www.tinkercad.com/)
- [ThingSpeak™](https://thingspeak.com/)
- [Google Colab](https://colab.research.google.com/)

## Project Implementation
Our project has mainly focused on designing a system that can accurately predict flood situations in riverine areas. The system comprises a transmitter section that is deployed under a bridge and a receiver section that receives data transmitted through the ESP NOW protocol. Since ESP NOW does not require WiFi, it can be used in areas where connectivity is limited. From the receiver section, the data is transmitted to a third NodeMCU, which then transfers it to the cloud and ultimately to the webpage.

Our system has the potential to be deployed at multiple points along the riverbank to provide real-time data, which can be combined to give a more accurate flood prediction. This could prove to be an essential tool for disaster management agencies to take timely and appropriate action to mitigate the effects of floods.

## Outputs
- **GSM Module Alert:** The system can trigger alerts using the GSM module to notify relevant authorities and residents in case of flood risk.
  
- **ThingSpeak Data Visualization:** Data collected by the system can be visualized on ThingSpeak for real-time monitoring and analysis.

- **Webpage:** The system provides a webpage interface for users to access flood-related information and alerts.

- **ML Prediction Using Regression [Accuracy: 93.09%]:** The system incorporated machine learning algorithm for flood risk prediction, achieving an accuracy rate of 93.09%.

## Other Contributors

- Teus A
- Denssal Francis
- Nandana Ramesh
- Aswin

  
