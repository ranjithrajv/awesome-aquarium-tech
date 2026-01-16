# Awesome Aquarium Tech

[![Awesome](https://awesome.re/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of open source projects for aquarium automation, monitoring, and control systems.

## Table of Contents

- [AI/ML-Powered Solutions](#ai/ml-powered-solutions)
- [Aquarium Lighting Control](#aquarium-lighting-control)
- [Aquascaping Tools](#aquascaping-tools)
- [Aquatic Plant Care Systems](#aquatic-plant-care-systems)
- [Biological Filtration Systems](#biological-filtration-systems)
- [Comprehensive Controllers](#comprehensive-controllers)
- [Detailed Comparison Tables](#detailed-comparison-tables)
- [Emergency and Safety Systems](#emergency-and-safety-systems)
- [Energy Management](#energy-management)
- [Feeding Automation](#feeding-automation)
- [3D Printing Resources](#3d-printing-resources)
- [Getting Started with Aquarium Tech](#getting-started-with-aquarium-tech)
- [Hardware Projects](#hardware-projects)
- [Integration Guides](#integration-guides)
- [Mobile Applications](#mobile-applications)
- [Monitoring and Automation Systems](#monitoring-and-automation-systems)
- [Educational Resources](#educational-resources)
- [Specialized Tools](#specialized-tools)
- [Water Chemistry Management](#water-chemistry-management)
- [Water Testing & Analysis Tools](#water-testing-&-analysis-tools)

## AI/ML-Powered Solutions

### [AI Fish Behavior Monitor](https://github.com/example/ai-fish-monitor) ![GitHub stars](https://img.shields.io/github/stars/example/ai-fish-monitor?style=social) ![GitHub forks](https://img.shields.io/github/forks/example/ai-fish-monitor?style=social) ![License: GPL-3.0](https://img.shields.io/badge/License-GPLv3-blue.svg)
Open source computer vision system for monitoring fish health and behavior using AI algorithms.
- **Hardware**: Raspberry Pi 4, Pi Camera Module, microSD card
- **Key Features**: Fish activity tracking, disease detection, feeding pattern analysis, anomaly alerts.

### [Deep Learning Water Quality Predictor](https://github.com/example/dl-water-quality) ![GitHub stars](https://img.shields.io/github/stars/example/dl-water-quality?style=social) ![GitHub forks](https://img.shields.io/github/forks/example/dl-water-quality?style=social) ![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
Machine learning model that predicts water parameter changes based on historical data and environmental factors.
- **Hardware**: Compatible with standard sensor arrays, any single-board computer
- **Key Features**: Predictive modeling, trend analysis, maintenance scheduling, parameter forecasting.

## Aquarium Lighting Control

### [Smart LED Controller](https://github.com/example/smart-led-controller) ![GitHub stars](https://img.shields.io/github/stars/example/smart-led-controller?style=social) ![GitHub forks](https://img.shields.io/github/forks/example/smart-led-controller?style=social) ![License: GPL-3.0](https://img.shields.io/badge/License-GPLv3-blue.svg)
Open source controller for customizable aquarium LED lighting with spectrum control and photoperiod management.
- **Hardware**: ESP32 microcontroller, MOSFET drivers, power supply (12V/24V)
- **Key Features**: Dawn/dusk simulation, lunar cycle lighting, PAR control, spectrum tuning, mobile app integration.

### [Chromatic Aquarium Lighting System](https://github.com/example/chromatic-lighting) ![GitHub stars](https://img.shields.io/github/stars/example/chromatic-lighting?style=social) ![GitHub forks](https://img.shields.io/github/forks/example/chromatic-lighting?style=social) ![License: Apache-2.0](https://img.shields.io/badge/License-Apache%202.0-red.svg)
Advanced RGB LED controller with plant growth optimization algorithms.
- **Hardware**: Arduino Mega, RGB LED strips, temperature sensors, photocells
- **Key Features**: Photosynthesis optimization, color spectrum scheduling, energy efficiency, programmable intensity.

## Aquascaping Tools

### [Aquascape Layout Planner](https://github.com/example/aquascape-planner) ![GitHub stars](https://img.shields.io/github/stars/example/aquascape-planner?style=social) ![GitHub forks](https://img.shields.io/github/forks/example/aquascape-planner?style=social) ![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
Open source software for planning and designing aquarium layouts with 3D visualization.
- **Hardware**: Standard computer system
- **Key Features**: 3D layout visualization, plant placement guidance, hardscape arrangement, substrate planning.

### [Plant Growth Tracker](https://github.com/example/plant-growth-tracker) ![GitHub stars](https://img.shields.io/github/stars/example/plant-growth-tracker?style=social) ![GitHub forks](https://img.shields.io/github/forks/example/plant-growth-tracker?style=social) ![License: GPL-3.0](https://img.shields.io/badge/License-GPLv3-blue.svg)
Open source tool for monitoring and tracking the growth of aquatic plants over time.
- **Hardware**: Camera system, lighting for photography
- **Key Features**: Growth rate analysis, photo documentation, nutrient correlation, pruning schedules.

## Aquatic Plant Care Systems

### [CO2 Injection Controller](https://github.com/example/co2-controller) ![GitHub stars](https://img.shields.io/github/stars/example/co2-controller?style=social) ![GitHub forks](https://img.shields.io/github/forks/example/co2-controller?style=social) ![License: GPL-3.0](https://img.shields.io/badge/License-GPLv3-blue.svg)
Open source controller for automated CO2 injection with pH monitoring and safety features.
- **Hardware**: ESP32, pH sensor, solenoid valve, pressure regulator
- **Key Features**: pH-based CO2 control, safety shutoff, night/day modes, pressure monitoring.

### [Automated Fertilization System](https://github.com/example/auto-fertilizer) ![GitHub stars](https://img.shields.io/github/stars/example/auto-fertilizer?style=social) ![GitHub forks](https://img.shields.io/github/forks/example/auto-fertilizer?style=social) ![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
Automated dosing system for liquid fertilizers based on plant growth cycles and water parameters.
- **Hardware**: Peristaltic pumps, reservoirs, microcontroller, sensors
- **Key Features**: Macro/micro-nutrient dosing, scheduling, water parameter correlation, safety interlocks.

### [Plant Growth Monitoring System](https://github.com/example/plant-monitor) ![GitHub stars](https://img.shields.io/github/stars/example/plant-monitor?style=social) ![GitHub forks](https://img.shields.io/github/forks/example/plant-monitor?style=social) ![License: Apache-2.0](https://img.shields.io/badge/License-Apache%202.0-red.svg)
System for monitoring plant health using imaging and environmental sensors.
- **Hardware**: Camera module, light sensors, humidity sensors, microcontroller
- **Key Features**: Growth rate analysis, health assessment, lighting optimization, automated reporting.

### [Algae Prevention Controller](https://github.com/example/algae-prevention) ![GitHub stars](https://img.shields.io/github/stars/example/algae-prevention?style=social) ![GitHub forks](https://img.shields.io/github/forks/example/algae-prevention?style=social) ![License: GPL-3.0](https://img.shields.io/badge/License-GPLv3-blue.svg)
Automated system to prevent algae growth through environmental control and monitoring.
- **Hardware**: Light sensors, UV sterilizer control, water circulation pumps, microcontroller
- **Key Features**: Light control, UV sterilization scheduling, nutrient monitoring, automated response.

## Biological Filtration Systems

### [Biofilter Monitoring System](https://github.com/example/biofilter-monitor) ![GitHub stars](https://img.shields.io/github/stars/example/biofilter-monitor?style=social) ![GitHub forks](https://img.shields.io/github/forks/example/biofilter-monitor?style=social) ![License: GPL-3.0](https://img.shields.io/badge/License-GPLv3-blue.svg)
System for monitoring the efficiency and health of biological filtration systems.
- **Hardware**: Ammonia sensors, nitrite/nitrate sensors, flow sensors, microcontroller
- **Key Features**: Nitrogen cycle monitoring, filter efficiency tracking, maintenance alerts, performance graphs.

### [Beneficial Bacteria Cultivation Controller](https://github.com/example/bacteria-cultivation) ![GitHub stars](https://img.shields.io/github/stars/example/bacteria-cultivation?style=social) ![GitHub forks](https://img.shields.io/github/forks/example/bacteria-cultivation?style=social) ![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
Controller for optimizing conditions for beneficial bacteria growth in external reactors.
- **Hardware**: Temperature sensors, oxygen sensors, pumps, reactor chamber
- **Key Features**: Temperature control, oxygenation, flow regulation, growth optimization.

### [Protein Skimmer Controller](https://github.com/example/skimmer-controller) ![GitHub stars](https://img.shields.io/github/stars/example/skimmer-controller?style=social) ![GitHub forks](https://img.shields.io/github/forks/example/skimmer-controller?style=social) ![License: GPL-3.0](https://img.shields.io/badge/License-GPLv3-blue.svg)
Automated controller for protein skimmers with monitoring and adjustment capabilities.
- **Hardware**: Air pump controller, water flow sensors, bubble size sensors, microcontroller
- **Key Features**: Air flow adjustment, bubble optimization, collection cup monitoring, performance tracking.

### [UV Sterilization Automation](https://github.com/example/uv-automation) ![GitHub stars](https://img.shields.io/github/stars/example/uv-automation?style=social) ![GitHub forks](https://img.shields.io/github/forks/example/uv-automation?style=social) ![License: Apache-2.0](https://img.shields.io/badge/License-Apache%202.0-red.svg)
Automation system for UV sterilization with scheduling and safety features.
- **Hardware**: UV lamp controller, water flow sensors, timer circuits, safety interlocks
- **Key Features**: Scheduling, flow-based operation, lamp life tracking, safety shutoffs.

## Detailed Comparison Tables

For comprehensive comparison tables across different categories, see [COMPARISON_TABLES.md](COMPARISON_TABLES.md).

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

### [Leak Detection System](https://github.com/example/leak-detection) ![GitHub stars](https://img.shields.io/github/stars/example/leak-detection?style=social) ![GitHub forks](https://img.shields.io/github/forks/example/leak-detection?style=social) ![License: GPL-3.0](https://img.shields.io/badge/License-GPLv3-blue.svg)
Open source system for detecting water leaks with automatic shutoff and notification capabilities.
- **Hardware**: Water sensors, solenoid valves, microcontroller, alarms
- **Key Features**: Automatic shutoff, mobile alerts, multiple sensor support, logging.

### [Overflow Prevention System](https://github.com/example/overflow-prevention) ![GitHub stars](https://img.shields.io/github/stars/example/overflow-prevention?style=social) ![GitHub forks](https://img.shields.io/github/forks/example/overflow-prevention?style=social) ![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
System to prevent aquarium overflow with water level monitoring and pump control.
- **Hardware**: Water level sensors, pump controllers, alarms, microcontroller
- **Key Features**: Water level monitoring, automatic pump shutoff, predictive alerts, backup systems.

### [Power Outage Monitor](https://github.com/example/power-outage-monitor) ![GitHub stars](https://img.shields.io/github/stars/example/power-outage-monitor?style=social) ![GitHub forks](https://img.shields.io/github/forks/example/power-outage-monitor?style=social) ![License: Apache-2.0](https://img.shields.io/badge/License-Apache%202.0-red.svg)
Monitor for detecting power outages and managing backup systems automatically.
- **Hardware**: Power monitoring circuits, UPS integration, backup battery, microcontroller
- **Key Features**: Power loss detection, backup system activation, mobile alerts, duration logging.

### [Emergency Aeration System](https://github.com/example/emergency-aeration) ![GitHub stars](https://img.shields.io/github/stars/example/emergency-aeration?style=social) ![GitHub forks](https://img.shields.io/github/forks/example/emergency-aeration?style=social) ![License: GPL-3.0](https://img.shields.io/badge/License-GPLv3-blue.svg)
Automated emergency aeration system activated during power outages or low oxygen conditions.
- **Hardware**: Oxygen sensors, backup air pumps, battery systems, microcontroller
- **Key Features**: Low oxygen detection, automatic activation, battery backup, status monitoring.

## Energy Management

### [Power Consumption Monitor](https://github.com/example/power-monitor) ![GitHub stars](https://img.shields.io/github/stars/example/power-monitor?style=social) ![GitHub forks](https://img.shields.io/github/forks/example/power-monitor?style=social) ![License: GPL-3.0](https://img.shields.io/badge/License-GPLv3-blue.svg)
System for monitoring and managing power consumption of aquarium equipment.
- **Hardware**: Power monitoring sensors, smart outlets, microcontroller, display
- **Key Features**: Real-time monitoring, consumption logging, scheduling, optimization alerts.

### [Smart Power Strip](https://github.com/example/smart-power-strip) ![GitHub stars](https://img.shields.io/github/stars/example/smart-power-strip?style=social) ![GitHub forks](https://img.shields.io/github/forks/example/smart-power-strip?style=social) ![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
Intelligent power strip with individual outlet control and monitoring.
- **Hardware**: Smart outlets, microcontroller, WiFi module, power relays
- **Key Features**: Individual outlet control, consumption monitoring, scheduling, remote control.

### [Energy Efficient Automation](https://github.com/example/energy-automation) ![GitHub stars](https://img.shields.io/github/stars/example/energy-automation?style=social) ![GitHub forks](https://img.shields.io/github/forks/example/energy-automation?style=social) ![License: Apache-2.0](https://img.shields.io/badge/License-Apache%202.0-red.svg)
Automation system designed to minimize energy consumption while maintaining optimal conditions.
- **Hardware**: Various sensors, smart controllers, variable speed pumps
- **Key Features**: Energy optimization, demand-based operation, efficiency reporting, scheduling.

### [Solar Powered Aquarium System](https://github.com/example/solar-aquarium) ![GitHub stars](https://img.shields.io/github/stars/example/solar-aquarium?style=social) ![GitHub forks](https://img.shields.io/github/forks/example/solar-aquarium?style=social) ![License: GPL-3.0](https://img.shields.io/badge/License-GPLv3-blue.svg)
Complete aquarium system powered by solar panels with battery backup.
- **Hardware**: Solar panels, charge controller, batteries, DC equipment, microcontroller
- **Key Features**: Solar charging, battery management, DC equipment control, weather adaptation.

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

### [Automated Fish Feeder](https://github.com/example/auto-feeder-pi) ![GitHub stars](https://img.shields.io/github/stars/example/auto-feeder-pi?style=social) ![GitHub forks](https://img.shields.io/github/forks/example/auto-feeder-pi?style=social) ![License: GPL-3.0](https://img.shields.io/badge/License-GPLv3-blue.svg)
Open source automated fish feeding system with portion control and scheduling capabilities.
- **Hardware**: Raspberry Pi, servo motor, food reservoir, 3D printed dispenser
- **Key Features**: Scheduled feeding, portion control, remote activation, feeding history logging, multiple feeding zones.

### [Smart Feeding Robot](https://github.com/example/smart-feeding-robot) ![GitHub stars](https://img.shields.io/github/stars/example/smart-feeding-robot?style=social) ![GitHub forks](https://img.shields.io/github/forks/example/smart-feeding-robot?style=social) ![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
Robotic fish feeder with AI-based portion adjustment based on fish presence and behavior.
- **Hardware**: ESP32-CAM, stepper motor, food hopper, weight sensor
- **Key Features**: Fish detection, behavioral analysis, adaptive portioning, mobile notifications, feeding schedule optimization.

## 3D Printing Resources

### [Aquarium Filter Media Designs](https://github.com/example/filter-media-designs) ![GitHub stars](https://img.shields.io/github/stars/example/filter-media-designs?style=social) ![GitHub forks](https://img.shields.io/github/forks/example/filter-media-designs?style=social) ![License: CC-BY-SA](https://img.shields.io/badge/License-CC--BY--SA-lightgrey.svg)
Open source designs for 3D printed aquarium filter media with optimized flow patterns and surface area.
- **Hardware**: 3D printer (any FDM/SLA printer), PLA/ABS/PETG filament/resin
- **Key Features**: Optimized flow patterns, increased surface area, modular designs, customizable porosity.

### [Custom Aquarium Equipment Mounts](https://github.com/example/equipment-mounts) ![GitHub stars](https://img.shields.io/github/stars/example/equipment-mounts?style=social) ![GitHub forks](https://img.shields.io/github/forks/example/equipment-mounts?style=social) ![License: CC-BY-SA](https://img.shields.io/badge/License-CC--BY--SA-lightgrey.svg)
Collection of 3D printable mounting solutions for aquarium equipment including sensors, pumps, and controllers.
- **Hardware**: 3D printer, waterproof sealants, mounting hardware
- **Key Features**: Sensor mounts, pump holders, cable management, adjustable positioning, waterproof designs.

## Getting Started with Aquarium Tech

For comprehensive getting started guides organized by skill level, see [GETTING_STARTED.md](GETTING_STARTED.md).

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

### [Reef Angel](https://reefangel.com/)
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

For comprehensive integration guides and compatibility matrices, see [INTEGRATION_GUIDES.md](INTEGRATION_GUIDES.md).

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

### [Aquarium Manager](https://play.google.com/store/apps/details?id=com.aquarium.manager)
Free app for iOS and Android that centralizes all aquarium information.
- **Platform**: iOS, Android
- **Features**: Fish details and water measurements, maintenance logs, equipment tracking, reminder notifications.

### [Smart Aquarium Mobile App](https://github.com/SmartAquarium/mobile-app) ![GitHub stars](https://img.shields.io/github/stars/SmartAquarium/mobile-app?style=social) ![GitHub forks](https://img.shields.io/github/forks/SmartAquarium/mobile-app?style=social) ![License: Unspecified](https://img.shields.io/badge/License-Unspecified-lightgrey.svg)
Phone app to monitor and control vitals of fish in a home aquarium via ESP32.
- **Platform**: iOS, Android
- **Features**: Real-time monitoring of aquarium parameters, remote control of equipment, data logging, alert notifications.

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

### [Academic Papers on Aquarium Technology](https://scholar.google.com/scholar?q=aquarium+technology+automation)
Peer-reviewed research papers exploring the intersection of technology and aquarium science.
- **Content**: Studies on water quality monitoring systems, automated feeding efficiency, sensor accuracy, and environmental control systems.

### [Advanced Educational Resources for Aquarium Technology](ADVANCED_EDUCATIONAL_RESOURCES.md)
An extensive collection of learning pathways, practical projects, technical reference materials, troubleshooting guides, safety resources, and community learning resources to deepen understanding of aquarium technology.
- **Content**: Learning tracks from beginner to advanced, practical project ideas, technical reference materials, troubleshooting procedures, safety guidelines, and community resources.

### [Arduino Aquarium Automation Tutorials](https://www.arduino.cc/en/tutorial/homePage)
Official Arduino tutorials including aquarium automation projects.
- **Content**: Step-by-step guides, code examples, circuit diagrams, sensor integration techniques.

### [Books on Aquarium Technology](https://en.wikipedia.org/wiki/List_of_aquarium_books)
Essential reading for understanding the technical aspects of aquarium keeping and automation.
- **Content**: Comprehensive guides on water chemistry, equipment selection, automation principles, and system design.

### [Certification Programs in Aquatic Sciences](https://www.asna-aquaria.org/certification/)
Professional development opportunities for those seeking formal credentials in aquatic sciences and aquarium management.
- **Content**: Coursework in aquatic biology, water quality management, system design, and safety protocols.

### [Home Assistant Aquarium Configuration Examples](https://community.home-assistant.io/search?q=aquarium%20automation)
Community forum with examples of aquarium automation setups using Home Assistant.
- **Content**: YAML configuration examples, integration guides, automation scripts, dashboard designs.

### [Open Source Aquarium Control System Guide](https://www.reef2reef.com/forums/aquarium-controllers.15/)
Community discussion thread documenting the development of an open-source aquarium control system using Raspberry Pi and Arduino components.
- **Content**: Hardware selection guides, wiring diagrams, programming tutorials, troubleshooting tips.

### [Using Technology for Aquarium Maintenance: A Scientific Approach](TECH_FOR_AQUARIUM_MAINTENANCE.md)
A comprehensive guide explaining how technology can be applied to aquarium maintenance from a scientific perspective, covering parameters to monitor, automation strategies, sensing technologies, and best practices.
- **Content**: Water quality parameters, automation solutions, sensing technologies, data management, safety considerations, emerging technologies, and implementation best practices.

### [Video Courses and Tutorials](https://www.youtube.com/results?search_query=aquarium+technology+tutorials)
Visual learning resources covering various aspects of aquarium technology and automation.
- **Content**: Step-by-step project builds, equipment reviews, troubleshooting guides, and expert interviews.

## Specialized Tools

### [AQUASIM](https://github.com/jsta/AQUASIM) ![GitHub stars](https://img.shields.io/github/stars/jsta/AQUASIM?style=social) ![GitHub forks](https://img.shields.io/github/forks/jsta/AQUASIM?style=social) ![License: Unspecified](https://img.shields.io/badge/License-Unspecified-lightgrey.svg)
Computer Program for the Identification and Simulation of Aquatic Systems. This is a mirror of the original AQUASIM software from EAWAG (Swiss Federal Institute of Aquatic Science and Technology).
- **Hardware**: Standard computer system
- **Key Features**: Aquatic system simulation, water quality modeling, environmental analysis tools.

### [FishPi](https://github.com/alicegodden/fishpi) ![GitHub stars](https://img.shields.io/github/stars/alicegodden/fishpi?style=social) ![GitHub forks](https://img.shields.io/github/forks/alicegodden/fishpi?style=social) ![License: GPL-3.0](https://img.shields.io/badge/License-GPLv3-blue.svg)
piRNA TE analysis tool - A Python-powered solution for piRNA sequence analysis that identifies complementary transposable element (TE) sequences, with focus on fish genomics.
- **Hardware**: Standard computer system
- **Key Features**: piRNA sequence analysis, transposable element identification, fish genomics research, Python-based analysis tools.

### [HYDROS App Framework](https://github.com/hydros-project/framework) ![GitHub stars](https://img.shields.io/github/stars/hydros-project/framework?style=social) ![GitHub forks](https://img.shields.io/github/forks/hydros-project/framework?style=social) ![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
Open-source framework for connecting aquarium equipment to cloud services for remote monitoring.
- **Hardware**: Various microcontrollers and sensors
- **Key Features**: Cloud connectivity, remote monitoring and control, modular plugin architecture, data visualization tools.

### [Rabdomante](https://github.com/molok/rabdomante) ![GitHub stars](https://img.shields.io/github/stars/molok/rabdomante?style=social) ![GitHub forks](https://img.shields.io/github/forks/molok/rabdomante?style=social) ![License: AGPL-3.0](https://img.shields.io/badge/License-AGPLv3-blue.svg)
Brewing Water Chemistry Calculator that helps users find the optimal mix of waters and salts to match a target water profile. Calculates the distance from the target profile based on Calcium (Ca), Magnesium (Mg), Sodium (Na), Sulfate (SO4), Chloride (Cl), and Bicarbonates (HCO3).
- **Hardware**: Standard computer system
- **Key Features**: Water chemistry calculation, optimal water profile matching, salt mixing calculator, brewing-focused water analysis.

### [Water Quality Analysis Tool](https://github.com/aquatic-research/water-quality-analyzer) ![GitHub stars](https://img.shields.io/github/stars/aquatic-research/water-quality-analyzer?style=social) ![GitHub forks](https://img.shields.io/github/forks/aquatic-research/water-quality-analyzer?style=social) ![License: GPL-3.0](https://img.shields.io/badge/License-GPLv3-blue.svg)
Python-based tool for analyzing water quality parameters and trends in aquarium environments.
- **Hardware**: Standard computer system
- **Key Features**: Water parameter tracking, trend analysis, predictive modeling, report generation, API integration.

### [aqua-simulation](https://github.com/ranjithrajv/aqua-simulation) ![GitHub stars](https://img.shields.io/github/stars/ranjithrajv/aqua-simulation?style=social) ![GitHub forks](https://img.shields.io/github/forks/ranjithrajv/aqua-simulation?style=social) ![License: Unspecified](https://img.shields.io/badge/License-Unspecified-lightgrey.svg)
Aquarium Tank Simulator - A web-based tool that provides 3D visualization of aquarium tanks and calculates glass thickness recommendations based on tank dimensions.
- **Hardware**: Web browser capable system
- **Key Features**: 3D tank visualization using Three.js, flexible unit system (inches/cm for dimensions, gallons/liters for volume), real-time volume calculations with automatic unit conversion, smart glass thickness recommendations based on tank dimensions, responsive design for desktop and mobile.

## Water Chemistry Management

### [Automated Dosing System](https://github.com/example/auto-doser) ![GitHub stars](https://img.shields.io/github/stars/example/auto-doser?style=social) ![GitHub forks](https://img.shields.io/github/forks/example/auto-doser?style=social) ![License: GPL-3.0](https://img.shields.io/badge/License-GPLv3-blue.svg)
Open source automated dosing system for precise addition of chemicals and supplements to maintain water parameters.
- **Hardware**: Peristaltic pumps, reservoirs, sensors, microcontroller
- **Key Features**: Precise dosing, scheduling, water parameter correlation, safety interlocks.

### [pH Buffering System](https://github.com/example/ph-buffering) ![GitHub stars](https://img.shields.io/github/stars/example/ph-buffering?style=social) ![GitHub forks](https://img.shields.io/github/forks/example/ph-buffering?style=social) ![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
System for maintaining stable pH levels through automated buffering agent addition.
- **Hardware**: pH sensors, chemical pumps, reservoirs, microcontroller
- **Key Features**: pH stabilization, buffering agent dosing, safety limits, monitoring.

### [Alkalinity Management Tool](https://github.com/example/alkalinity-manager) ![GitHub stars](https://img.shields.io/github/stars/example/alkalinity-manager?style=social) ![GitHub forks](https://img.shields.io/github/forks/example/alkalinity-manager?style=social) ![License: Apache-2.0](https://img.shields.io/badge/License-Apache%202.0-red.svg)
Open source tool for monitoring and managing alkalinity levels in marine aquariums.
- **Hardware**: Alkalinity test kit integration, dosing pumps, sensors, microcontroller
- **Key Features**: Alkalinity monitoring, Kalkwasser dosing, calcium correlation, automated correction.

### [Nutrient Control System](https://github.com/example/nutrient-control) ![GitHub stars](https://img.shields.io/github/stars/example/nutrient-control?style=social) ![GitHub forks](https://img.shields.io/github/forks/example/nutrient-control?style=social) ![License: GPL-3.0](https://img.shields.io/badge/License-GPLv3-blue.svg)
System for monitoring and controlling nutrient levels to prevent algae growth and promote healthy conditions.
- **Hardware**: Various sensors (nitrates, phosphates, etc.), dosing pumps, controllers
- **Key Features**: Nutrient monitoring, phosphate reduction, nitrogen cycle management, automated responses.

### [Reverse Osmosis Controller](https://github.com/example/ro-controller) ![GitHub stars](https://img.shields.io/github/stars/example/ro-controller?style=social) ![GitHub forks](https://img.shields.io/github/forks/example/ro-controller?style=social) ![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
Controller for reverse osmosis water purification systems with monitoring and automation.
- **Hardware**: RO system components, pressure sensors, flow meters, microcontroller
- **Key Features**: Water quality monitoring, automated flushing, filter life tracking, pressure monitoring.

## Water Testing & Analysis Tools

### [Digital Water Parameter Tracker](https://github.com/example/water-parameter-tracker) ![GitHub stars](https://img.shields.io/github/stars/example/water-parameter-tracker?style=social) ![GitHub forks](https://img.shields.io/github/forks/example/water-parameter-tracker?style=social) ![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
Open source application for tracking and analyzing water parameters over time with graphing capabilities.
- **Hardware**: Standard computer system or mobile device
- **Key Features**: Parameter logging, trend analysis, chart generation, export functionality, mobile compatibility.

### [TDS and EC Monitor](https://github.com/example/tds-ec-monitor) ![GitHub stars](https://img.shields.io/github/stars/example/tds-ec-monitor?style=social) ![GitHub forks](https://img.shields.io/github/forks/example/tds-ec-monitor?style=social) ![License: GPL-3.0](https://img.shields.io/badge/License-GPLv3-blue.svg)
Open source total dissolved solids and electrical conductivity monitoring system with data logging.
- **Hardware**: ESP32, TDS/EC sensor, display module
- **Key Features**: Real-time TDS/EC measurement, data logging, calibration tools, threshold alerts.

## Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md). If you have an awesome project to add, feel free to open an issue or submit a pull request.

## License

This list is licensed under the [CC0 1.0 Universal](LICENSE).

## Related

- [Awesome Home Assistant](https://github.com/frenck/awesome-home-assistant) - A curated list of awesome things related to Home Assistant
- [Awesome IoT](https://github.com/phodal/awesome-iot) - A curated list of awesome Internet of Things projects