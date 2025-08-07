 Human Elderly Monitoring System – Smart Wearable Health & Safety Device
 
 OVERVIEW:
The Human Elderly Monitoring System is a compact, chest-wearable IoT-based device designed to monitor the health, safety, and activity of elderly individuals in real time. Inspired by the form factor of a GoPro chest band, this embedded system integrates multiple biomedical and environmental sensors to provide continuous monitoring, fall detection, location tracking, and emergency alerting capabilities.

This system is especially valuable for caregivers and families who want to ensure their elderly loved ones are safe, even when they are alone or in remote locations.

KEY FEATURES:
 1. GPS Tracking – Real-time location monitoring for safety and mobility awareness.

 2. GSM Connectivity (SIM800L) – Sends SMS alerts to caregivers during emergencies.

 3. DHT11 Sensor – Measures environmental temperature and humidity.

 4. MAX30102 Sensor – Monitors heart rate and blood oxygen (SpO2) levels.

 5. MPU6050 – Detects falls and abnormal motion patterns.

 6. IR Obstacle Sensor – Detects nearby obstacles or proximity-based triggering.

 7. Buzzer & LED Alerts – Local alerts for critical situations.

 8. Battery Operated – Portable and rechargeable for wearable use.

 9. Serial Output via ESP32 – Live data output to Serial Monitor for debugging or external system integration.

HARDWARE COMPONENTS:
 
- Component	Description
  
> ESP32 Dev Board	Central controller with Wi-Fi & BLE
> SIM800L Module	GSM module for SMS communication
> GPS Module (e.g., NEO-6M)	For real-time location tracking
> MAX30102	Pulse Oximeter for heart rate and SpO2
> MPU6050	Accelerometer + Gyroscope for fall detection
> DHT11	Temperature & Humidity sensor
> IR Sensor	Obstacle/proximity detection
> Buzzer + LED	Alerting mechanism
> Battery Pack	Rechargeable lithium battery (e.g., 3.7V 18650)

-  System Workflow
  
> When the IR sensor detects a person/object nearby, the system is triggered.
> All sensors (DHT11, MAX30102, MPU6050) take real-time readings.
> If abnormal vitals or motion (fall) are detected:
> An SMS alert is sent to a predefined number using the SIM800L.
> Buzzer and LED are activated for local alert.
 > Location data from the GPS module is sent along with the alert.

-  Wearable Design
  
> The design is compact, inspired by chest-mounted camera bands (like GoPro harnesses), making it:
> Comfortable for long-term wear
> Easily accessible for maintenance or charging
> Stable for accurate motion and vital sign monitoring


FUTURE IMPROVEMENTS:

> Cloud-based dashboard (e.g., Firebase, ThingSpeak)
> Voice alert integration
> Integration with smartwatch or mobile app
> AI-based fall detection and health pattern prediction


USE CASES:
> Monitoring elderly individuals living alone
> Hospital or assisted-living patient tracking
> Remote health diagnostics in rural areas
> General wearable health systems

