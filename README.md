# ESP32 Web-Controlled LED

## Project Overview

This project uses an ESP32 web server to control an LED through a webpage. Users can turn the LED ON or OFF by clicking buttons in a browser.

## Components

* ESP32 DevKit V1
* LED
* 220-ohm resistor
* Jumper wires

## Technologies

* Arduino C++
* HTML and CSS
* ESP32 Wi-Fi
* HTTP Web Server
* Wokwi Simulator

## Circuit Connections

* ESP32 GPIO 23 → 220-ohm resistor → LED anode
* LED cathode → GND

## Features

* Webpage hosted on the ESP32
* LED ON and OFF controls
* Displays the current LED state
* Simple browser-based interface

## Working Principle

The ESP32 connects to Wi-Fi and starts an HTTP web server. When a user clicks an ON or OFF button, the browser sends an HTTP request to the ESP32. The ESP32 updates the LED output and returns the webpage.

## Expected Result

The LED can be switched ON and OFF through the web interface.

## Simulation

Add your Wokwi project link here.

## Result

The web-controlled LED system is implemented using an ESP32 web server and browser-based controls.
