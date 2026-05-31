# IoT-Enabled Smoke Detection System Using Arduino

## 📌 Project Overview

An IoT-enabled smoke detection system developed using the MQ-135 gas sensor and Arduino UNO to monitor air quality in real-time and provide immediate warning alerts whenever hazardous smoke levels are detected. The system is designed to be cost-effective, reliable, and easily adaptable for both residential and industrial safety applications.

## 🎯 Project Highlights

* ✅ Designed and implemented an Arduino-based smoke detection system utilizing the MQ-135 gas sensor for real-time air quality monitoring.
* ✅ Developed a threshold-based alert mechanism where the system activates a buzzer module whenever smoke levels exceed the predefined safety limit.
* ✅ Performed sensor calibration and sensitivity adjustments to improve detection accuracy and reduce false alerts.
* ✅ Implemented real-time data acquisition and processing using Arduino UNO for fast response and reliable performance.
* ✅ Designed a compact and low-power monitoring system suitable for indoor safety and environmental applications.

## 🛠️ Components Used

* Arduino UNO
* MQ-135 Gas Sensor
* Buzzer Module
* LED Indicators (Red, Blue)
* Resistors (220Ω, 390Ω)
* Breadboard & Jumper Wires

## 📐 Specifications

### 📌 MQ-135 Gas Sensor

* *Operating Voltage:* 5V DC
* *Detectable Gases:* Ammonia (NH3), Benzene, Alcohol, Smoke, CO2, and other harmful gases
* *Analog Output Range:* 0 – 5V
* *Preheat Time:* ~24 hours for optimal accuracy
* *Typical Applications:* Air quality monitoring, gas leakage detection, and pollution monitoring

### 📌 Active Buzzer Module

* *Operating Voltage:* 3.3V to 5V DC
* *Signal Type:* Active buzzer with built-in oscillator
* *Sound Level:* ~85dB at 10 cm distance
* *Current Consumption:* ~30mA
* *Usage:* Generates audio alerts during hazardous smoke conditions

### 📌 Arduino UNO

* *Microcontroller:* ATmega328P
* *Operating Voltage:* 5V
* *Digital I/O Pins:* 14 (6 PWM outputs)
* *Analog Input Pins:* 6
* *Flash Memory:* 32 KB
* *SRAM:* 2 KB
* *EEPROM:* 1 KB
* *Clock Speed:* 16 MHz
* *Power Supply Options:* USB or external (7V-12V recommended)

## ⚙️ Circuit Setup

## 🖼️ Final Project Output

### 📸 Final Project Setup

### 📽️ Live Demo Video

[📺 Watch Project Demo](<https://drive.google.com/file/d/1-LtoPbkFNdaP8aBU3fNWMOKZSOjF61os/view?usp=drivesdk" />
)

You can also find the demo video inside this repository:

* Project-Demo.mp4

## 🖥️ Code Files

All code files are available inside the Smoke_Detector/ directory:

* [Smoke_Detector.ino](Smoke_Detector/Smoke_Detector.ino) — Arduino sketch for uploading to the board.
* [Smoke_Detector.txt](Smoke_Detector/Smoke_Detector.txt) — Code in text format for quick viewing.

## 📄 How to Use

1. ✅ Connect the components according to the circuit diagram.
2. ✅ Upload the Arduino code using Arduino IDE.
3. ✅ Power up the circuit using USB or external battery supply.
4. ✅ The system continuously monitors air quality and smoke concentration levels.
5. ✅ When smoke concentration crosses the threshold limit, the buzzer and LEDs generate immediate warning alerts.

## 🚀 Future Scope

* ✅ Integration of Bluetooth (HC-05) or Wi-Fi (ESP8266/ESP32) modules for remote monitoring and mobile notifications.
* ✅ Addition of GSM modules (SIM800L/SIM900A) for SMS-based emergency alerts.
* ✅ Incorporation of temperature and humidity sensors (DHT11/DHT22) for advanced environmental monitoring.
* ✅ Development of a mobile application or web dashboard for real-time data visualization.
* ✅ Implementation of cloud-based data logging for long-term monitoring and analysis.
