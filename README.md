<h1 align="center">JC3248W535C – EspHome – NTP – Clock</h1>




[![Watch the video](https://img.youtube.com/vi/KXD6XMGUkCg/maxresdefault.jpg)](https://youtu.be/KXD6XMGUkCg?si=G9tBf9vHF6RZ90qc)


## Description

This project showcases an NTP‑synchronized clock built using the JC3248W535C display module and fully powered by **ESPHome**. The device retrieves accurate time from NTP servers, renders it on a 3.5" TFT display, and integrates seamlessly with **Home Assistant** for monitoring and automation.

The firmware is written entirely in YAML and includes:
- real‑time NTP synchronization
- custom layout for time, date, and weekday
- support for custom fonts and image assets
- smooth visual transitions and clean UI elements
- optional Home Assistant sensors and data integration

This repository contains all required resources: ESPHome configuration, display assets, fonts and setup instructions. The project is designed to be easy to reproduce, customize, and extend.


<p align="center"> <img src="assets/22.png" width="300"/> <img src="assets/11.png" width="300"/> </p>


## Features

- **Accurate NTP time synchronization**  
  Retrieves time from reliable NTP servers with automatic periodic updates.

- **Custom UI layout**  
  Displays time, date, weekday, and additional visual elements using a clean, modern design.

- **High‑quality JC3248W535C TFT display**  
  Utilizes the 3.2" IPS panel with crisp rendering and smooth transitions.

- **ESPHome‑based firmware**  
  Fully configurable in YAML, easy to modify, extend, and integrate with other devices.

- **Home Assistant integration**  
  Exposes sensors, states, and optional controls directly to Home Assistant.

- **Custom fonts and image assets**  
  Supports embedded PNGs, icons, and multiple font weights for a polished UI.

- **Low power consumption**  
  Efficient ESP32 operation suitable for 24/7 uptime.

- **Easy to reproduce**  
  Includes wiring diagrams, assets, and configuration files for straightforward assembly.

