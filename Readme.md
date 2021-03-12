# iBBQ-Gateway 

an ESP32 Based iBBQ (Inkbird) BLE to MQTT Gateway

## Requirements

## Usage

After flashing the device you should connect to your WiFi, it should connect to your iBBQ Device and starts to publish data
rename the `credentials.example.h` to `credentials.h` and edit it to your needs

## Features

Fork of runningtoy's InkBird_BLE2MQTT project (https://github.com/runningtoy/InkBird_BLE2MQTT) modified to support Fahrenheit temperatures.

Changes include:
* Sets BLE monitor to Fahrenheit
* Calculate Fahrenheit temperature prior to publishing as MQTT Topics

## ToDO

* Add MQTT input handling to set target temperature via MQTT / Home Assistant

## Protocol description
(https://gist.github.com/uucidl/b9c60b6d36d8080d085a8e3310621d64)
