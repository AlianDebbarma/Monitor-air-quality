# Monitor-air-quality
Developed an air quality monitoring system using Arduino IDE with the following components: NodeMCU ESP8266, MQ135 Sensor, DHT11 Sensor, LCD Display, and I2C Converter

🌫️ Air Quality Monitoring System
This project is a real-time Air Quality Monitoring System built using NodeMCU ESP8266, MQ135 Gas Sensor, DHT11 Temperature & Humidity Sensor, and an LCD Display with I2C converter. It monitors CO2 levels, temperature, and humidity, displaying the data locally and optionally supporting Wi-Fi for remote monitoring.

📦 Components Used
NodeMCU ESP8266 (Wi-Fi module & microcontroller)

MQ135 Gas Sensor (Air quality detection – CO2, NH3, etc.)

DHT11 Sensor (Temperature and humidity sensing)

16x2 LCD Display

I2C Converter (for LCD)

Jumper Wires / Connecting Cables

⚙️ Features
Real-time monitoring of air quality, temperature, and humidity

Data displayed on LCD using I2C interface

Coded in Arduino IDE

Compact and cost-effective setup

Optional Wi-Fi connectivity for remote monitoring (via ESP8266)

🖥️ How It Works
The MQ135 sensor detects air pollutants like CO2 and sends analog signals to the NodeMCU.

The DHT11 measures temperature and humidity.

All sensor data is processed by the NodeMCU, and results are shown on a 16x2 LCD via I2C.

With Wi-Fi, the system can be enhanced to log or transmit data to a server or IoT dashboard (optional).

🔌 Circuit Diagram
(Add image here using ![alt text](image_link) once uploaded)

💻 Code
The Arduino code is available in the code folder.
Make sure to install the following libraries in Arduino IDE:

DHT sensor library by Adafruit

LiquidCrystal_I2C

🛠️ Setup Instructions
Connect the components as per the circuit diagram.

Open the code in Arduino IDE.

Select NodeMCU 1.0 (ESP-12E Module) as the board.

Upload the code to the board via USB.

Power the NodeMCU and observe data on the LCD.

📷 Demo
(Insert a GIF/video or image of working project)

📌 Future Improvements
Send data to cloud platforms like ThingSpeak or Blynk

Add alerts or buzzer for unsafe air quality levels

Display data on a mobile/web dashboard
