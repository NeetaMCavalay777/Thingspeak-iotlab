# ESP32 Weather Monitor (DHT11 + ThingSpeak)

This repository holds the code and dataset for an IoT lab project (expmt_5.1). 

The goal was to hook up a DHT11 sensor to an ESP32, gather room temperature and humidity readings, and stream that telemetry directly to a ThingSpeak cloud dashboard in real-time.

---

## Live Dashboard

If the ESP32 is powered on and transmitting data, these charts update automatically:

### Temperature (°C)
![Temperature Chart](https://api.thingspeak.com/channels/3498467/charts/1?width=450&height=260&results=60&dynamic=true)

### Humidity (%)
![Humidity Chart](https://api.thingspeak.com/channels/3498467/charts/2?width=450&height=260&results=60&dynamic=true)

You can also check out the full dashboard on [ThingSpeak Channel 3498467](https://thingspeak.com/channels/3498467).

---

## Hardware Used
* Microcontroller: DOIT ESP32 DevKit V1
* Sensor: DHT11 Temperature & Humidity Sensor (Connected to GPIO 4)
* Misc: Breadboard, jumper wires, and a Micro-USB cable

---

## What's in this Repo?
* feed.json — A raw snapshot of the telemetry feed exported straight from ThingSpeak.
* README.md — Project notes, circuit specs, and live data charts. 
