# Awesome Aquarium Tech

[![Awesome](https://awesome.re/badge.svg)](https://github.com/sindresorhus/awesome)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/ranjithrajv/awesome-aquarium-tech/blob/main/docs/CONTRIBUTING.md)
[![GitHub contributors](https://img.shields.io/github/contributors/ranjithrajv/awesome-aquarium-tech)](https://github.com/ranjithrajv/awesome-aquarium-tech/graphs/contributors)
[![GitHub last commit](https://img.shields.io/github/last-commit/ranjithrajv/awesome-aquarium-tech)](https://github.com/ranjithrajv/awesome-aquarium-tech/commits/main)
[![License: CC0 1.0](https://img.shields.io/badge/License-CC0%201.0-lightgrey.svg)](LICENSE)

A curated list of open source projects for aquarium automation, monitoring, and control systems.

## Table of Contents

### By Function
- [Comprehensive Control Systems](#comprehensive-controllers)
- [Monitoring & Data Collection](#monitoring-and-automation-systems)
- [Automated Control Systems](#comprehensive-controllers)
- [Safety & Emergency Systems](#emergency-and-safety-systems)
- [Water Quality Management](#water-chemistry-management)
- [Life Support Systems](#aquarium-lighting-control)
- [Infrastructure](#energy-management)
- [Specialized Tools & Utilities](#specialized-tools)

### By Category
- [Educational Resources & Learning Pathways](#educational-resources)
- [Enhanced Searchability Features](#enhanced-searchability-features)

## Standardized Project Information

To improve consistency and help users make informed decisions, all project entries in this list follow a [standardized format](docs/PROJECT_TEMPLATE.md) that includes essential information like platform requirements, difficulty level, hardware requirements, and key features. This makes it easier to compare projects and understand what's involved before starting implementation.

## Quick Index by Function

### Water Quality Management
- [Water Chemistry Management](#water-chemistry-management)
- [Biological Filtration Systems](#biological-filtration-systems)
- [Water Testing & Analysis Tools](#water-testing-&-analysis-tools)
- [Aquatic Plant Care Systems](#aquatic-plant-care-systems)

### Life Support Systems
- [Aquarium Lighting Control](#aquarium-lighting-control)
- [Feeding Automation](#feeding-automation)
- [Aquascaping Tools](#aquascaping-tools)

### Safety & Emergency Systems
- [Emergency and Safety Systems](#emergency-and-safety-systems)

### Infrastructure
- [Energy Management](#energy-management)
- [Hardware Projects](#hardware-projects)

### Specialized Tools & Utilities
- [Specialized Tools](#specialized-tools)
- [Mobile Applications](#mobile-applications)
- [AI/ML-Powered Solutions](#ai/ml-powered-solutions)

## AI/ML-Powered Solutions

### [Smart Fish Tank Monitoring System](https://github.com/IT21179280/SMART-FISH-TANK-MONITORING-SYSTEM) ![GitHub stars](https://img.shields.io/github/stars/IT21179280/SMART-FISH-TANK-MONITORING-SYSTEM?style=social) ![GitHub forks](https://img.shields.io/github/forks/IT21179280/SMART-FISH-TANK-MONITORING-SYSTEM?style=social) ![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
IoT-based system using ESP32-CAM with custom-trained YOLOv8 models for fish species identification, pregnant fish detection, and automated environment control.
- **Hardware**: ESP32, ESP32-CAM, sensors
- **Key Features**: Fish species identification, pregnant fish detection, real-time monitoring, automated environment control, live camera feed.

### [Smart Aquarium IoT Analytics Platform](https://github.com/YasinduKaveesha/smart-aquarium-iot-analytics-platform) ![GitHub stars](https://img.shields.io/github/stars/YasinduKaveesha/smart-aquarium-iot-analytics-platform?style=social) ![GitHub forks](https://img.shields.io/github/forks/YasinduKaveesha/smart-aquarium-iot-analytics-platform?style=social) ![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
Adaptive AI-driven IoT monitoring platform with SARIMA forecasting, Isolation Forest anomaly detection, and fuzzy Water Quality Index scoring.
- **Hardware**: ESP32, pH/TDS/turbidity/temperature sensors
- **Key Features**: Predictive water quality modeling, anomaly detection, 24h forecasts, React dashboard, MQTT pipeline.

## Aquarium Lighting Control

### [DeepGlow](https://github.com/kabroxiko/DeepGlow) ![GitHub stars](https://img.shields.io/github/stars/kabroxiko/DeepGlow?style=social) ![GitHub forks](https://img.shields.io/github/forks/kabroxiko/DeepGlow?style=social) ![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
Standalone ESP-IDF based aquarium LED controller for ESP32-family boards with real-time control and smooth transitions.
- **Hardware**: ESP32-family board, LED drivers, power supply
- **Key Features**: Real-time LED control, sunrise/sunset scheduling, embedded web UI, REST API, WebSocket updates, OTA updates, safety limits.

### [AquaControl32](https://github.com/CelliesProjects/aquacontrol32-pio) ![GitHub stars](https://img.shields.io/github/stars/CelliesProjects/aquacontrol32-pio?style=social) ![GitHub forks](https://img.shields.io/github/forks/CelliesProjects/aquacontrol32-pio?style=social) ![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
5-channel LED aquarium controller with gradual sunrise/sunset simulation, moon phase cycle, and web interface.
- **Hardware**: ESP32 with SD card slot, LED dimming board, optional DS18B20 sensor
- **Key Features**: 5-channel PWM control, sunrise/sunset simulation, moon phase cycle, web interface, SD card storage.

## Aquascaping Tools

### [Maya's Aquarium Maker 3D](https://github.com/m4ym4y/mayas-aquarium-3d) ![GitHub stars](https://img.shields.io/github/stars/m4ym4y/mayas-aquarium-3d?style=social) ![GitHub forks](https://img.shields.io/github/forks/m4ym4y/mayas-aquarium-3d?style=social) ![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
Virtual fish tank editor built with Three.js and react-three-fiber for designing aquarium layouts in 3D.
- **Hardware**: Standard computer system
- **Key Features**: 3D layout editor, multiple fish types, plant placement, water shader, embeddable widget, undo/redo.

### [Aquarium Builder](https://github.com/randomnewb/aquarium-builder) ![GitHub stars](https://img.shields.io/github/stars/randomnewb/aquarium-builder?style=social) ![GitHub forks](https://img.shields.io/github/forks/randomnewb/aquarium-builder?style=social) ![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
Tool for hobbyists to plan and organize aquarium components — create, view, and modify tank setups before building.
- **Hardware**: Standard computer system
- **Key Features**: Component organization, tank viability checking, equipment planning, real-world setup mapping.

## Aquatic Plant Care Systems

### [ESP-aqua-CO2](https://github.com/Jbsco/ESP-aqua-CO2) ![GitHub stars](https://img.shields.io/github/stars/Jbsco/ESP-aqua-CO2?style=social) ![GitHub forks](https://img.shields.io/github/forks/Jbsco/ESP-aqua-CO2?style=social) ![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
Low-cost CO2 control system for automated aquariums using LilyGO T-Display-S3 ESP32, maintaining target pH levels.
- **Hardware**: LilyGO T-Display-S3 ESP32, pH sensor, solenoid valve, CO2 regulator
- **Key Features**: pH-based CO2 control, target pH maintenance, safety monitoring, display interface.

### [DIY my Dose](https://github.com/diymoica/DmDose) ![GitHub stars](https://img.shields.io/github/stars/diymoica/DmDose?style=social) ![GitHub forks](https://img.shields.io/github/forks/diymoica/DmDose?style=social) ![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
Universal smart dosing controller for reef aquariums — controls up to 4 peristaltic pumps with Home Assistant + ESP32 (ESPHome).
- **Hardware**: ESP32, 4 peristaltic pumps, Home Assistant
- **Key Features**: Automatic dosing, precise calibration, safety watchdog, alerts, statistics, no cloud dependency.

## Biological Filtration Systems

### [THIR Aquarium Roll Filter](https://github.com/DeeEmm/Thir) ![GitHub stars](https://img.shields.io/github/stars/DeeEmm/Thir?style=social) ![GitHub forks](https://img.shields.io/github/forks/DeeEmm/Thir?style=social) ![License: GPL-3.0](https://img.shields.io/badge/License-GPLv3-blue.svg)
Open source DIY automatic roll filter for mechanical filtration — build-it-yourself with laser-cut perspex and off-the-shelf filter media.
- **Hardware**: Laser-cut perspex, drive motor, filter media roll, 3D printed parts
- **Key Features**: Automatic filter media advance, DIY-friendly build, media source guide, DXG cut files included.

## Detailed Comparison Tables

For comprehensive comparison tables across different categories, see [docs/COMPARISON_TABLES.md](docs/COMPARISON_TABLES.md).

This document includes detailed comparisons of:
- Comprehensive Controllers
- Water Quality Monitoring Systems
- Feeding Automation Systems
- Lighting Control Systems
- AI/ML Solutions
- 3D Printing Projects
- Mobile Apps
- Hardware Projects
- Specialized Tools
- Water Chemistry Management
- Biological Filtration Systems
- Aquatic Plant Care Systems
- Emergency and Safety Systems
- Energy Management

## Emergency and Safety Systems

### [ESPHome Water Leak Detector](https://github.com/mrahmadt/ESPHome-Water-Leak-Detector) ![GitHub stars](https://img.shields.io/github/stars/mrahmadt/ESPHome-Water-Leak-Detector?style=social) ![GitHub forks](https://img.shields.io/github/forks/mrahmadt/ESPHome-Water-Leak-Detector?style=social) ![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
DIY water leak detection system built with ESPHome and Home Assistant for detecting water leaks around aquariums.
- **Hardware**: ESP32/ESP8266, water leak sensors, Home Assistant
- **Key Features**: Leak detection, Home Assistant integration, mobile alerts, customizable sensitivity.

### [AquariumController](https://github.com/disgustipated/AquariumController) ![GitHub stars](https://img.shields.io/github/stars/disgustipated/AquariumController?style=social) ![GitHub forks](https://img.shields.io/github/forks/disgustipated/AquariumController?style=social) ![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
ESP8266-based aquarium overflow prevention using ultrasonic sensors (JSN-SR04T) and DS18B20 temperature probe for water level and temperature monitoring.
- **Hardware**: ESP8266 Feather Huzzah, JSN-SR04T ultrasonic sensors, DS18B20 temperature probe
- **Key Features**: Water level monitoring, temperature monitoring, sump level monitoring, top-off reservoir monitoring.

### [reefbeatEnergyBackup](https://github.com/Elwinmage/reefbeatEnergyBackup) ![GitHub stars](https://img.shields.io/github/stars/Elwinmage/reefbeatEnergyBackup?style=social) ![GitHub forks](https://img.shields.io/github/forks/Elwinmage/reefbeatEnergyBackup?style=social) ![License: Apache-2.0](https://img.shields.io/badge/License-Apache%202.0-red.svg)
Control Reefbeat devices during power outages with automated backup system management.
- **Hardware**: Reefbeat devices, power monitoring circuits
- **Key Features**: Power outage detection, Reefbeat device control, backup automation.

## Energy Management

### [ESP32 Power Monitor](https://github.com/Maxim-szh/ESP32-Power-Monitor-WebServer) ![GitHub stars](https://img.shields.io/github/stars/Maxim-szh/ESP32-Power-Monitor-WebServer?style=social) ![GitHub forks](https://img.shields.io/github/forks/Maxim-szh/ESP32-Power-Monitor-WebServer?style=social) ![License: GPL-3.0](https://img.shields.io/badge/License-GPLv3-blue.svg)
ESP32-based power monitoring using SCT-013 current sensors with real-time data visualization via web interface.
- **Hardware**: ESP32, SCT-013-000 current sensors
- **Key Features**: Real-time power consumption monitoring, device status tracking, web dashboard.

### [Smart Aquarium V3.1](https://github.com/desiFish/Smart-Aquarium-V3.1) ![GitHub stars](https://img.shields.io/github/stars/desiFish/Smart-Aquarium-V3.1?style=social) ![GitHub forks](https://img.shields.io/github/forks/desiFish/Smart-Aquarium-V3.1?style=social) ![License: GPL-3.0](https://img.shields.io/badge/License-GPLv3-blue.svg)
ESP8266-based aquarium controller for managing 4 relay outputs with manual, scheduled, timer, and toggle modes.
- **Hardware**: ESP8266 NodeMCU, 4-channel relay module, DS1307/DS3231 RTC
- **Key Features**: 4 relay control, multiple control modes, OTA updates, RESTful API, responsive web UI, NTP sync.

## Comprehensive Controllers

### [Aquareo](https://github.com/fnandes/aquareo) ![GitHub stars](https://img.shields.io/github/stars/fnandes/aquareo?style=social) ![GitHub forks](https://img.shields.io/github/forks/fnandes/aquareo?style=social) ![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
Open-source ESP32-based aquarium controller for monitoring and automating basic aquarium needs.
- **Hardware**: ESP32 microcontroller, various sensors (temperature, pH, etc.)
- **Key Features**: Temperature/pH/salinity monitoring, dosing automation, auto top-off, MQTT integration, modular design for easy expansion.

### [aquaPI](https://github.com/schwabix-1311/aquaPI) ![GitHub stars](https://img.shields.io/github/stars/schwabix-1311/aquaPI?style=social) ![GitHub forks](https://img.shields.io/github/forks/schwabix-1311/aquaPI?style=social) ![License: GPL-3.0](https://img.shields.io/badge/License-GPLv3-blue.svg)
Modular aquarium controller for Raspberry Pi with web interface for monitoring and control.
- **Hardware**: Raspberry Pi (3 or 4), relay board, sensor modules
- **Key Features**: Temperature/pH/light control, modular functional blocks, sunrise/sunset lighting, customizable automation, offline operation.

### [Marine Assistant](https://github.com/marine-assistant/Marineassistant) ![GitHub stars](https://img.shields.io/github/stars/marine-assistant/Marineassistant?style=social) ![GitHub forks](https://img.shields.io/github/forks/marine-assistant/Marineassistant?style=social) ![License: GPL-3.0](https://img.shields.io/badge/License-GPLv3-blue.svg)
Smart aquarium controller designed for reef tanks with local Home Assistant integration, no cloud required.
- **Hardware**: Raspberry Pi, various analog/digital sensors, 12V/120V control relays
- **Key Features**: Temperature/water level/leak monitoring, 12V/120V device control, analog sensor support (pH/TDS/EC/ORP), Home Assistant integration, customizable automation.

### [OctoRelay](https://github.com/borisbu/OctoRelay) ![GitHub stars](https://img.shields.io/github/stars/borisbu/OctoRelay?style=social) ![GitHub forks](https://img.shields.io/github/forks/borisbu/OctoRelay?style=social) ![License: AGPL-3.0](https://img.shields.io/badge/License-AGPLv3-blue.svg)
OctoPrint/OctoPi plugin to control relays, allowing users to control GPIO pins of Raspberry Pi for switching relays and indicating their states, with support for up to 8 relays.
- **Hardware**: Raspberry Pi with GPIO-compatible relays, up to 8 relay channels
- **Key Features**: Relay control for up to 8 relays, GPIO pin control, state indication, Raspberry Pi integration.

### [Orca](https://github.com/mstelz/orca) ![GitHub stars](https://img.shields.io/github/stars/mstelz/orca?style=social) ![GitHub forks](https://img.shields.io/github/forks/mstelz/orca?style=social) ![License: GPL-3.0](https://img.shields.io/badge/License-GPLv3-blue.svg)
Raspberry Pi-based aquarium controller with cloud-based website for monitoring and management.
- **Hardware**: Raspberry Pi, various sensors, internet connection
- **Key Features**: Temperature/salinity monitoring, auto top-off, controllable power outlets, video camera support, multiple tank support, user authentication.

### [reef-pi](https://github.com/reef-pi/reef-pi) ![GitHub stars](https://img.shields.io/github/stars/reef-pi/reef-pi?style=social) ![GitHub forks](https://img.shields.io/github/forks/reef-pi/reef-pi?style=social) ![License: Apache 2.0](https://img.shields.io/badge/License-Apache%202.0-red.svg)
An open-source reef tank controller based on Raspberry Pi with modular design for affordable DIY automation.
- **Hardware**: Raspberry Pi, relay board, various sensors, webcam
- **Key Features**: Web-based UI, temperature/pH monitoring and control, dosing pumps, auto top-off, LED lighting automation, email alerts, charts, and camera integration.

## Feeding Automation

### [fishfeeder](https://github.com/ColoMAX/fishfeeder) ![GitHub stars](https://img.shields.io/github/stars/ColoMAX/fishfeeder?style=social) ![GitHub forks](https://img.shields.io/github/forks/ColoMAX/fishfeeder?style=social) ![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
Standalone automatic fish feeder based on ESP8266 with ESPHome, featuring 3D-printed Archimedes screw dispenser.
- **Hardware**: ESP8266/ESP32, modified servo motor, 3D printed dispenser, vibration motor
- **Key Features**: Scheduled feeding, portion control via Archimedes screw, Home Assistant integration, web interface, manual button control.

### [iotFeeder](https://github.com/reivaxy/iotFeeder) ![GitHub stars](https://img.shields.io/github/stars/reivaxy/iotFeeder?style=social) ![GitHub forks](https://img.shields.io/github/forks/reivaxy/iotFeeder?style=social) ![License: GPL-3.0](https://img.shields.io/badge/License-GPLv3-blue.svg)
WiFi-enabled fish feeder using ESP8266 and stepper motor with notifications when empty or on power failure.
- **Hardware**: ESP8266, stepper motor, OLED screen, 3D printed parts
- **Key Features**: Stepper motor precision, food level detection, push notifications, Firebase logging, OTA updates, manual feed button.

## Getting Started with Aquarium Tech

For comprehensive getting started guides organized by skill level, see [docs/GETTING_STARTED.md](docs/GETTING_STARTED.md).

This document provides:
- Beginner pathway (weeks 1-6)
- Intermediate pathway (months 1-3)
- Advanced pathway (months 1-6)
- Essential skills checklist
- Recommended learning resources
- Safety considerations
- Troubleshooting guide
- Cost planning

## Hardware Projects

### [Aqua-Controller](https://github.com/atanasyanew/aqua-app) ![GitHub stars](https://img.shields.io/github/stars/atanasyanew/aqua-app?style=social) ![GitHub forks](https://img.shields.io/github/forks/atanasyanew/aqua-app?style=social) ![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
ESP8266-based fish tank automation using Mongoose OS and Node-RED for remote monitoring and control.
- **Hardware**: ESP8266, Mongoose OS, Node-RED
- **Key Features**: Remote control via Node-RED dashboard, ESP8266-based design, MQTT communication, mobile app integration, real-time monitoring.

### [Aquaero](https://github.com/shred/pyquaero) ![GitHub stars](https://img.shields.io/github/stars/shred/pyquaero?style=social) ![GitHub forks](https://img.shields.io/github/forks/shred/pyquaero?style=social) ![License: LGPL-3.0](https://img.shields.io/badge/License-LGPL%20v3-blue.svg)
Python library and web service for accessing Aquaero fan and pump controllers by Aqua Computer GmbH & Co. KG. Community open source project not endorsed by or affiliated with Aqua Computer. Based on reverse engineering.
- **Hardware**: Aquaero controllers, PC/Raspberry Pi
- **Key Features**: Python library for Aquaero controllers, web service interface, fan and pump control, community-driven reverse engineering.

### [Aquariumduino](https://github.com/FernandoGarcia/FerduinoAquariumController) ![GitHub stars](https://img.shields.io/github/stars/FernandoGarcia/FerduinoAquariumController?style=social) ![GitHub forks](https://img.shields.io/github/forks/FernandoGarcia/FerduinoAquariumController?style=social) ![License: LGPL-3.0](https://img.shields.io/badge/License-LGPL%20v3-blue.svg)
Open-source aquarium controller project based on the Arduino platform, featuring temperature, pH, ORP, and density monitoring/control, automatic top-off, partial water change automation, LED light control, cloud/lightning simulation, and automatic feeder with web interface.
- **Hardware**: Arduino board, various sensors, relays, pumps
- **Key Features**: Temperature/pH/ORP/density monitoring and control, automatic top-off, partial water change automation, LED light control with cloud/lightning simulation, automatic feeder, web interface.

### [Buce LED Controller](https://github.com/borneo-iot/borneo) ![GitHub stars](https://img.shields.io/github/stars/borneo-iot/borneo?style=social) ![GitHub forks](https://img.shields.io/github/forks/borneo-iot/borneo?style=social) ![License: GPL-3.0](https://img.shields.io/badge/License-GPLv3-blue.svg)
Compact ESP32-C3 based controller supporting 6 independent PWM channels for aquarium lighting.
- **Hardware**: ESP32-C3, PWM drivers, power supply
- **Key Features**: 6 independent PWM channels, high-resolution dimming, flexible dimming curves, compact design, programmable lighting schedules.

### [EcolibriumReef](https://github.com/PracticalHomeApp/EcolibriumReef-Arduino) ![GitHub stars](https://img.shields.io/github/stars/PracticalHomeApp/EcolibriumReef-Arduino?style=social) ![GitHub forks](https://img.shields.io/github/forks/PracticalHomeApp/EcolibriumReef-Arduino?style=social) ![License: GPL-3.0](https://img.shields.io/badge/License-GPLv3-blue.svg)
DIY Arduino-based aquarium controller with Android companion app.
- **Hardware**: Arduino, various sensors, Android device
- **Key Features**: Basic monitoring functions, Android app integration, customizable automation routines, sensor support for temperature, pH, and water levels.

### [JeeLabs](https://github.com/jeelabs) ![GitHub stars](https://img.shields.io/github/stars/jeelabs?style=social) ![GitHub forks](https://img.shields.io/github/forks/jeelabs?style=social) ![License: Various](https://img.shields.io/badge/License-Variety-informational.svg)
Organization focused on embedded systems, IoT, and Arduino-related projects. Most popular repository is esp-link (esp8266 wifi-serial bridge) with nearly 3,000 stars, followed by jeelib (Arduino library) with 507 stars.
- **Hardware**: Various Arduino and ESP modules
- **Key Features**: Embedded systems projects, IoT solutions, Arduino libraries, esp8266 support, wireless communication modules.

### [OpenAquarium](https://github.com/balub/open-aquarium-project) ![GitHub stars](https://img.shields.io/github/stars/balub/open-aquarium-project?style=social) ![GitHub forks](https://img.shields.io/github/forks/balub/open-aquarium-project?style=social) ![License: Unspecified](https://img.shields.io/badge/License-Unspecified-lightgrey.svg)
Collection of FOSS tools/configs along with hardware and software for aquarium management. Contains configs/guides to FOSS tools and software and hardware developed for managing aquariums.
- **Hardware**: Various components depending on implementation
- **Key Features**: Collection of FOSS tools, configuration guides, hardware designs, software for aquarium management.

### [OpenSprinkler](https://github.com/OpenSprinkler/OpenSprinkler-Firmware) ![GitHub stars](https://img.shields.io/github/stars/OpenSprinkler/OpenSprinkler-Firmware?style=social) ![GitHub forks](https://img.shields.io/github/forks/OpenSprinkler/OpenSprinkler-Firmware?style=social) ![License: GPL-3.0](https://img.shields.io/badge/License-GPLv3-blue.svg)
OpenSprinkler Unified Firmware for OpenSprinkler, OpenSprinkler Pi, and Linux-based OpenSprinkler. Supports multiple platforms and is actively maintained with substantial community following.
- **Hardware**: OpenSprinkler hardware, Raspberry Pi, Linux systems
- **Key Features**: Unified firmware for multiple platforms, sprinkler automation, timer controls, weather-based adjustments, community support.

### [Reef Angel](https://reefangel.com/) ![License: GPL-3.0](https://img.shields.io/badge/License-GPLv3-blue.svg)
Open-source aquarium controller built on the Arduino platform, designed for reef aquariums.
- **Hardware**: Arduino-based controller, various sensors
- **Key Features**: Real-time monitoring of pH, temperature, water level, customizable relay control, expandable modules, user-friendly interface.

### [Smart Aquarium Project](https://github.com/yashkurkure/Smart-Aquarium-Project) ![GitHub stars](https://img.shields.io/github/stars/yashkurkure/Smart-Aquarium-Project?style=social) ![GitHub forks](https://img.shields.io/github/forks/yashkurkure/Smart-Aquarium-Project?style=social) ![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
IoT-based aquarium automation with timed feeding, temperature monitoring, water level detection, and light control.
- **Hardware**: IoT board (likely ESP32), sensors, actuators
- **Key Features**: Timed fish feeding with RTC, temperature monitoring, water level monitoring, automated light control, mobile connectivity.

### [TankBuilder](https://github.com/awitwicki/openTank) ![GitHub stars](https://img.shields.io/github/stars/awitwicki/openTank?style=social) ![GitHub forks](https://img.shields.io/github/forks/awitwicki/openTank?style=social) ![License: Apache-2.0](https://img.shields.io/badge/License-Apache%202.0-red.svg)
Open source tank platform that includes implementations for ESP32, Raspberry Pi, and Arduino. Uses 3D printed parts, plastic tracks, DC motors, L298N motor driver, and supports various microcontrollers.
- **Hardware**: ESP32/Raspberry Pi/Arduino, 3D printed parts, DC motors, L298N motor driver
- **Key Features**: Platform implementations for ESP32/Raspberry Pi/Arduino, 3D printed parts, motorized platform, track-based movement, multiple microcontroller support.

## Integration Guides

For comprehensive integration guides and compatibility matrices, see [docs/INTEGRATION_GUIDES.md](docs/INTEGRATION_GUIDES.md).

This document includes:
- Controller integration matrix
- Home automation integration guides
- Sensor integration guide
- Actuator integration guide
- Network integration options
- Troubleshooting integration issues
- Best practices for integration

## Mobile Applications

### [Aquarium Log - Tank Manager](https://apps.apple.com/us/app/aquarium-log-tank-manager/id1621042664)
Powerful mobile app for aquarists to maintain and monitor aquarium information.
- **Platform**: iOS
- **Features**: Centralized aquarium information, fish details tracking, water measurement logging, maintenance scheduling, health monitoring.

## Monitoring and Automation Systems

### [AquaMonitor](https://github.com/reivaxy/aquaMonitor) ![GitHub stars](https://img.shields.io/github/stars/reivaxy/aquaMonitor?style=social) ![GitHub forks](https://img.shields.io/github/forks/reivaxy/aquaMonitor?style=social) ![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)
Recifal aquarium monitoring with Arduino, alerts and settings by SMS and webApp, and statistics database. Monitors light level, temperature, water level, main power failure, and sends SMS alerts when configurable thresholds are reached.
- **Hardware**: Arduino, various sensors, GSM module
- **Key Features**: Light level monitoring, temperature monitoring, water level monitoring, power failure detection, SMS alerts, web app interface, statistics database.

### [AquaPi (aquapi)](https://github.com/TheRealFalseReality/aquapi) ![GitHub stars](https://img.shields.io/github/stars/TheRealFalseReality/aquapi?style=social) ![GitHub forks](https://img.shields.io/github/forks/TheRealFalseReality/aquapi?style=social) ![License: GPL-3.0](https://img.shields.io/badge/License-GPLv3-blue.svg)
Aquarium monitoring and automation system using ESPHome and Home Assistant for smart home integration.
- **Hardware**: ESP32/ESP8266, various sensors
- **Key Features**: Temperature/water level/pH/salinity monitoring, dissolved oxygen, peristaltic dosing pumps, CO2 control, modular sensor support, Home Assistant integration, customizable dashboards.

### [Domoticz](https://github.com/domoticz/domoticz) ![GitHub stars](https://img.shields.io/github/stars/domoticz/domoticz?style=social) ![GitHub forks](https://img.shields.io/github/forks/domoticz/domoticz?style=social) ![License: GPL-3.0](https://img.shields.io/badge/License-GPLv3-blue.svg)
Open source Home Automation System that monitors and configures various devices like lights, switches, sensors/meters (Temperature, Rain, Wind, UV, Electricity, Gas, Water, etc.) with notifications, cross-platform support, HTML5 web frontend, and extended logging.
- **Hardware**: Various sensors and controllers
- **Key Features**: Home automation system, sensor monitoring, cross-platform support, HTML5 web frontend, notifications, extended logging.

### [Fish Tank Monitor and Control](https://github.com/rjsears/Fish_Tank_Monitor_and_Control) ![GitHub stars](https://img.shields.io/github/stars/rjsears/Fish_Tank_Monitor_and_Control?style=social) ![GitHub forks](https://img.shields.io/github/forks/rjsears/Fish_Tank_Monitor_and_Control?style=social) ![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
Comprehensive monitoring and management system for fish tanks using Python/Flask with sensor integration.
- **Hardware**: Raspberry Pi or similar, various sensors
- **Key Features**: Temperature/pH/ammonia/EC/TDS monitoring, notifications (email/SMS), smart power strip control, CO2 injection management, historical data with Grafana.

### [OpenHAB](https://github.com/openhab/openhab-core) ![GitHub stars](https://img.shields.io/github/stars/openhab/openhab-core?style=social) ![GitHub forks](https://img.shields.io/github/forks/openhab/openhab-core?style=social) ![License: EPL-2.0](https://img.shields.io/badge/License-EPL%202.0-red.svg)
Core framework of openHAB - Contains core bundles of the openHAB runtime. Not a product itself, but a framework to build solutions on top of, serving as the foundation for the main openHAB distribution.
- **Hardware**: Various hardware platforms supported
- **Key Features**: Home automation framework, extensible platform, cross-platform compatibility, extensive addon ecosystem.

## Educational Resources

### [Advanced Educational Resources for Aquarium Technology](docs/ADVANCED_EDUCATIONAL_RESOURCES.md)
An extensive collection of learning pathways, practical projects, technical reference materials, troubleshooting guides, safety resources, and community learning resources to deepen understanding of aquarium technology.
- **Content**: Learning tracks from beginner to advanced, practical project ideas, technical reference materials, troubleshooting procedures, safety guidelines, and community resources.

### [Aquarium Technology Learning Pathways](docs/LEARNING_PATHWAYS.md)
Structured learning tracks designed to guide users from beginner to expert levels in aquarium technology.
- **Content**: Subject-specific learning tracks, prerequisite knowledge mapping, skill progression ladders, and certification pathways.

### [Research & Academic Resources](docs/RESEARCH_ACADEMIA.md)
Collection of academic papers, research institutions, scientific studies, and university projects related to aquarium technology.
- **Content**: Academic papers, research institutions, scientific studies, university projects, and scientific methodologies.

### [Community Resources](docs/COMMUNITY_RESOURCES.md)
Information about local meetups, maker spaces, educational institutions, and collaborative development efforts.
- **Content**: Local meetups and groups, maker space projects, educational institution projects, collaborative development efforts.

## Enhanced Searchability Features

### [Tagging System](docs/TAGGING_SYSTEM.md)
A comprehensive tagging system to categorize projects by multiple attributes for easier discovery.
- **Features**: Multi-dimensional tags, keyword search, filter by platform, difficulty, function, and more.

### [Filter Options](docs/FILTER_OPTIONS.md)
Advanced filtering capabilities to narrow down projects based on specific requirements.
- **Features**: Platform-based filtering, difficulty level, cost range, feature-based filters, compatibility options.

### [Cross-Referencing Guide](docs/CROSS_REFERENCING.md)
Systematic cross-referencing between related projects and concepts for comprehensive understanding.
- **Features**: Related project suggestions, technology overlaps, integration possibilities, upgrade paths.

### [Quick Comparison Tools](docs/COMPARISON_TOOLS.md)
Tools for rapidly comparing multiple projects side-by-side based on key attributes.
- **Features**: Side-by-side comparisons, feature matrices, decision trees, recommendation engines.

### [Open Source Aquarium Control System Guide](https://www.reef2reef.com/forums/aquarium-controllers.15/)
Community discussion thread documenting the development of an open-source aquarium control system using Raspberry Pi and Arduino components.
- **Content**: Hardware selection guides, wiring diagrams, programming tutorials, troubleshooting tips.

### [Using Technology for Aquarium Maintenance: A Scientific Approach](docs/TECH_FOR_AQUARIUM_MAINTENANCE.md)
A comprehensive guide explaining how technology can be applied to aquarium maintenance from a scientific perspective, covering parameters to monitor, automation strategies, sensing technologies, and best practices.
- **Content**: Water quality parameters, automation solutions, sensing technologies, data management, safety considerations, emerging technologies, and implementation best practices.

## Specialized Tools

### [AQUASIM](https://github.com/jsta/AQUASIM) ![GitHub stars](https://img.shields.io/github/stars/jsta/AQUASIM?style=social) ![GitHub forks](https://img.shields.io/github/forks/jsta/AQUASIM?style=social) ![License: Unspecified](https://img.shields.io/badge/License-Unspecified-lightgrey.svg)
Computer Program for the Identification and Simulation of Aquatic Systems. This is a mirror of the original AQUASIM software from EAWAG (Swiss Federal Institute of Aquatic Science and Technology).
- **Hardware**: Standard computer system
- **Key Features**: Aquatic system simulation, water quality modeling, environmental analysis tools.

### [FishPi](https://github.com/alicegodden/fishpi) ![GitHub stars](https://img.shields.io/github/stars/alicegodden/fishpi?style=social) ![GitHub forks](https://img.shields.io/github/forks/alicegodden/fishpi?style=social) ![License: GPL-3.0](https://img.shields.io/badge/License-GPLv3-blue.svg)
piRNA TE analysis tool - A Python-powered solution for piRNA sequence analysis that identifies complementary transposable element (TE) sequences, with focus on fish genomics.
- **Hardware**: Standard computer system
- **Key Features**: piRNA sequence analysis, transposable element identification, fish genomics research, Python-based analysis tools.

### [HYDROS App Framework](Available through commercial vendors) ![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
Open-source framework for connecting aquarium equipment to cloud services for remote monitoring.
- **Hardware**: Various microcontrollers and sensors
- **Key Features**: Cloud connectivity, remote monitoring and control, modular plugin architecture, data visualization tools.

### [Rabdomante](https://github.com/molok/rabdomante) ![GitHub stars](https://img.shields.io/github/stars/molok/rabdomante?style=social) ![GitHub forks](https://img.shields.io/github/forks/molok/rabdomante?style=social) ![License: AGPL-3.0](https://img.shields.io/badge/License-AGPLv3-blue.svg)
Brewing Water Chemistry Calculator that helps users find the optimal mix of waters and salts to match a target water profile. Calculates the distance from the target profile based on Calcium (Ca), Magnesium (Mg), Sodium (Na), Sulfate (SO4), Chloride (Cl), and Bicarbonates (HCO3).
- **Hardware**: Standard computer system
- **Key Features**: Water chemistry calculation, optimal water profile matching, salt mixing calculator, brewing-focused water analysis.

### [Aquarium Tank Monitoring System](https://github.com/jsramesh1990/Aquarium-Tank-Monitoring) ![GitHub stars](https://img.shields.io/github/stars/jsramesh1990/Aquarium-Tank-Monitoring?style=social) ![GitHub forks](https://img.shields.io/github/forks/jsramesh1990/Aquarium-Tank-Monitoring?style=social) ![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
Multi-board embedded project for monitoring critical water parameters (temperature, pH, TDS) supporting Arduino UNO, Mega, ESP32, ESP8266, STM32, and Pi Pico.
- **Hardware**: Arduino/ESP32/STM32/Pi Pico, pH/TDS/temperature sensors
- **Key Features**: Multi-platform support, PlatformIO + Arduino CLI, Makefile build system, real-time serial monitoring, extensible IoT architecture.

### [aqua-simulation](https://github.com/ranjithrajv/aqua-simulation) ![GitHub stars](https://img.shields.io/github/stars/ranjithrajv/aqua-simulation?style=social) ![GitHub forks](https://img.shields.io/github/forks/ranjithrajv/aqua-simulation?style=social) ![License: Unspecified](https://img.shields.io/badge/License-Unspecified-lightgrey.svg)
Aquarium Tank Simulator - A web-based tool that provides 3D visualization of aquarium tanks and calculates glass thickness recommendations based on tank dimensions.
- **Hardware**: Web browser capable system
- **Key Features**: 3D tank visualization using Three.js, flexible unit system (inches/cm for dimensions, gallons/liters for volume), real-time volume calculations with automatic unit conversion, smart glass thickness recommendations based on tank dimensions, responsive design for desktop and mobile.

## Water Chemistry Management

### [Open Dosing Pump](https://github.com/inventmarine/open-dosing-pump) ![GitHub stars](https://img.shields.io/github/stars/inventmarine/open-dosing-pump?style=social) ![GitHub forks](https://img.shields.io/github/forks/inventmarine/open-dosing-pump?style=social) ![License: GPL-3.0](https://img.shields.io/badge/License-GPLv3-blue.svg)
Open source, DIY, easy-to-assemble peristaltic dosing pump for precise chemical addition — no soldering required, 4 pumps with Bluetooth or USB.
- **Hardware**: 4 peristaltic pumps, Bluetooth/USB module, power supply
- **Key Features**: 4-pump design, no-solder assembly, Bluetooth/USB communication, precise dosing, calibration support.

### [Aquamonitor](https://github.com/aquamonitor/Aquamonitor) ![GitHub stars](https://img.shields.io/github/stars/aquamonitor/Aquamonitor?style=social) ![GitHub forks](https://img.shields.io/github/forks/aquamonitor/Aquamonitor?style=social) ![License: LGPL-3.0](https://img.shields.io/badge/License-LGPL%20v3-blue.svg)
Automated RO/DI auto top-off (ATO) and auto water change system for reef tanks using Raspberry Pi — under $200.
- **Hardware**: Raspberry Pi, electrovalves, float switches, water level sensors
- **Key Features**: Automated ATO refill, automatic water changes, leak detection, visual/LED/sound/mail/push alerts, corrective actions.

## Water Testing & Analysis Tools

### [Smart Fish Tank](https://github.com/Spenc3rB/Smart-Fish-Tank) ![GitHub stars](https://img.shields.io/github/stars/Spenc3rB/Smart-Fish-Tank?style=social) ![GitHub forks](https://img.shields.io/github/forks/Spenc3rB/Smart-Fish-Tank?style=social) ![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
ESP32-based environmental monitoring system for TDS, temperature, RGB LED control, stepper motor feeder, and email alerts.
- **Hardware**: ESP32, TDS sensor, DS18B20 temperature sensor, stepper motor, RGB LED
- **Key Features**: Real-time TDS/temperature monitoring, customizable threshold alerts, email notifications, RGB LED control, web interface.

### [Web-Based Aquarium Automation](https://github.com/akhdanfarrosrenoldi/web-realtime-aquarium-automation) ![GitHub stars](https://img.shields.io/github/stars/akhdanfarrosrenoldi/web-realtime-aquarium-automation?style=social) ![GitHub forks](https://img.shields.io/github/forks/akhdanfarrosrenoldi/web-realtime-aquarium-automation?style=social) ![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
ESP32-based real-time aquarium monitoring system tracking temperature and TDS/EC with ThingSpeak integration.
- **Hardware**: ESP32, analog TDS sensor, DS18B20 temperature sensor
- **Key Features**: Real-time EC/TDS monitoring, temperature-compensated readings, ThingSpeak cloud logging, web dashboard.

## Spread the Word

- Share on [Twitter](https://twitter.com/intent/tweet?text=Awesome%20Aquarium%20Tech%20-%20Open%20source%20aquarium%20automation%20projects&url=https://github.com/ranjithrajv/awesome-aquarium-tech)
- [Reddit r/aquariums](https://www.reddit.com/r/aquariums/)
- [Reddit r/reeftank](https://www.reddit.com/r/ReefTank/)
- [Hackaday](https://hackaday.io/submit)

## Contributing

Contributions are welcome! Please read the [contribution guidelines](docs/CONTRIBUTING.md). If you have an awesome project to add, please [open a project suggestion](https://github.com/ranjithrajv/awesome-aquarium-tech/issues/new?labels=project-suggestion&template=add_project.yml).

## License

This list is licensed under the [CC0 1.0 Universal](LICENSE).

## Related

- [Awesome Home Assistant](https://github.com/frenck/awesome-home-assistant) - A curated list of awesome things related to Home Assistant
