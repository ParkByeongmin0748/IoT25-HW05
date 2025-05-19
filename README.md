# IoT25-HW05
Reads temperature and humidity from the DHT11 sensor and sends the data via BLE notify.

1. ESP32 Server
Function: Reads temperature and humidity from the DHT11 sensor and sends the data via BLE notify.

Sensor Connection Pin: DHT11 data pin → GPIO 26

BLE Service

Service UUID: 12345678-1234-1234-1234-1234567890ab

Temperature Characteristic UUID: ...90ac

Humidity Characteristic UUID: ...90ad

2. ESP32 Client
Function: Connects to the BLE server and receives temperature/humidity data. Displays the data on an OLED screen in real time.

[DEMO Video](https://youtube.com/shorts/aruCSPtUC9o?si=ItyAlmKAU516Gw3d)
