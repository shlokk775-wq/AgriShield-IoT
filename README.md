# AgriShield: Smart IoT-Based Agricultural Monitoring System 🌾📡

AgriShield is a compact and intelligent IoT-based solution built using the ESP32 board to monitor grain storage and real-time outdoor weather conditions. It sends SMS alerts using the SIM800L GSM module when spoilage conditions or adverse weather is detected.

## 🛠 Features

- **GrainSafe Module:**
  - DHT22 for Temperature & Humidity
  - MQ135 Gas sensor for spoilage gases
  - SMS alerts if temperature, humidity, or gas exceed thresholds

- **KrishiCast Module:**
  - DHT22 for outdoor conditions
  - Rain Sensor
  - Wind Speed Sensor (Anemometer-style pulse counter)

- **Connectivity:**
  - GSM-based SMS via SIM800L
  - Works offline—no WiFi needed!

## 📦 Hardware Used

- ESP32 Dev Board (WROOM-32)
- SIM800L GSM Module
- DHT22 Sensors (x2)
- MQ135 Gas Sensor
- Rain Sensor (Analog)
- Wind Speed Sensor (Pulse)
- 12V Power Supply (with step-down to 3.7V for SIM800L)

## 🧠 Software

- Arduino IDE
- Libraries: `DHT`, `Adafruit_Sensor`, `HardwareSerial`

## 📷 Schematic & Images

Add wiring diagrams or prototype images in the `images/` folder.

## 📨 SMS Alert Format

Example message:
