# Firmware Description

This firmware is developed using Arduino IDE for NodeMCU (ESP8266).

## Functionality:

* Reads data from DHT11, Soil Moisture, DS18B20, and LDR sensors
* Sends real-time data to Blynk app
* Automatically turns ON water pump when soil moisture is low
* Controls LED based on light intensity

## Logic:

* If soil moisture < threshold → Pump ON
* Else → Pump OFF
* Sensor data continuously updated to Blynk
