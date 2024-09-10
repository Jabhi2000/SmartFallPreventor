# SmartFallPreventor

This project aims to develop a smart wearable system that integrates Artificial Intelligence (AI) and various sensors to help prevent falls in elderly individuals. Falls are a leading cause of injury and disability among the elderly, and this device seeks to minimize these risks by providing real-time monitoring and alerts. The wearable utilizes motion sensors like the **MPU6050** (accelerometer and gyroscope) and physiological sensors like the **MAX30102** (heart rate and SpO2 monitor) to track the user's movements and vital signs, ensuring both balance and health data are constantly monitored.

### Key Features:

- **Fall Detection**: The MPU6050 sensor continuously measures acceleration and gyroscopic data. When deviations from baseline values are detected, indicating a fall, the system triggers an alert.
  
- **Fall Direction Detection**: After detecting a fall, the system identifies the direction of the fall (e.g., forward, backward, left, or right). This information can help caregivers understand the circumstances surrounding the fall.

- **Heart Rate & SpO2 Monitoring**: The MAX30102 sensor tracks vital signs such as heart rate and oxygen saturation. This feature provides additional safety by monitoring the wearer's health and detecting potential emergencies related to cardiovascular health.

- **Emergency Alerts**: In case of a fall, the system sends a text message via a GSM module (SIM800L) to a caregiver or family member. The alert includes the user's heart rate and notifies the contact of the fall. Additionally, the system can automatically initiate a phone call to the designated contact person.

### Benefits:
This device addresses one of the leading causes of injury among the elderly by using a combination of advanced sensor technology and AI for fall detection and health monitoring. By delivering real-time feedback and automated alerts, the system not only improves the safety of elderly individuals but also provides peace of mind for caregivers and family members. This wearable technology can significantly reduce the incidence of fall-related injuries, prevent further complications, and enhance the quality of life for elderly users


.![Schematic_SIH2024_circuit_diagram_2024-09-10](https://github.com/user-attachments/assets/536f4a44-82a7-47be-9b04-d242bd812b96)


