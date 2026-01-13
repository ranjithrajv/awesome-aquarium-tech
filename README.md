# Awesome Aquarium Tech

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of open source projects for aquarium automation, monitoring, and control systems.

## Table of Contents

- [Comprehensive Controllers](#comprehensive-controllers)
- [Monitoring and Automation Systems](#monitoring-and-automation-systems)
- [Hardware Projects](#hardware-projects)
- [Mobile Applications](#mobile-applications)
- [Educational Resources](#educational-resources)
- [Specialized Tools](#specialized-tools)

## Comprehensive Controllers

### [Aquareo](https://github.com/fnandes/aquareo) ![GitHub stars](https://img.shields.io/github/stars/fnandes/aquareo?style=social) ![GitHub forks](https://img.shields.io/github/forks/fnandes/aquareo?style=social)
Open-source ESP32-based aquarium controller for monitoring and automating basic aquarium needs.
- **License**: MIT
- **Key Features**: Temperature/pH/salinity monitoring, dosing automation, auto top-off, MQTT integration, modular design for easy expansion.

### [aquaPI](https://github.com/schwabix-1311/aquaPI) ![GitHub stars](https://img.shields.io/github/stars/schwabix-1311/aquaPI?style=social) ![GitHub forks](https://img.shields.io/github/forks/schwabix-1311/aquaPI?style=social)
Modular aquarium controller for Raspberry Pi with web interface for monitoring and control.
- **License**: GPL-3.0
- **Key Features**: Temperature/pH/light control, modular functional blocks, sunrise/sunset lighting, customizable automation, offline operation.

### [Marine Assistant](https://github.com/marine-assistant/Marineassistant) ![GitHub stars](https://img.shields.io/github/stars/marine-assistant/Marineassistant?style=social) ![GitHub forks](https://img.shields.io/github/forks/marine-assistant/Marineassistant?style=social)
Smart aquarium controller designed for reef tanks with local Home Assistant integration, no cloud required.
- **License**: GPL-3.0
- **Key Features**: Temperature/water level/leak monitoring, 12V/120V device control, analog sensor support (pH/TDS/EC/ORP), Home Assistant integration, customizable automation.

### [OctoRelay](https://github.com/borisbu/OctoRelay) ![GitHub stars](https://img.shields.io/github/stars/borisbu/OctoRelay?style=social) ![GitHub forks](https://img.shields.io/github/forks/borisbu/OctoRelay?style=social)
OctoPrint/OctoPi plugin to control relays, allowing users to control GPIO pins of Raspberry Pi for switching relays and indicating their states, with support for up to 8 relays.
- **License**: AGPL-3.0
- **Key Features**: Relay control for up to 8 relays, GPIO pin control, state indication, Raspberry Pi integration.

### [Orca](https://github.com/mstelz/orca) ![GitHub stars](https://img.shields.io/github/stars/mstelz/orca?style=social) ![GitHub forks](https://img.shields.io/github/forks/mstelz/orca?style=social)
Raspberry Pi-based aquarium controller with cloud-based website for monitoring and management.
- **License**: GPL-3.0
- **Key Features**: Temperature/salinity monitoring, auto top-off, controllable power outlets, video camera support, multiple tank support, user authentication.

### [reef-pi](https://github.com/reef-pi/reef-pi) ![GitHub stars](https://img.shields.io/github/stars/reef-pi/reef-pi?style=social) ![GitHub forks](https://img.shields.io/github/forks/reef-pi/reef-pi?style=social)
An open-source reef tank controller based on Raspberry Pi with modular design for affordable DIY automation.
- **License**: Apache 2.0
- **Key Features**: Web-based UI, temperature/pH monitoring and control, dosing pumps, auto top-off, LED lighting automation, email alerts, charts, and camera integration.

## Monitoring and Automation Systems

### [AquaMonitor](https://github.com/reivaxy/aquaMonitor) ![GitHub stars](https://img.shields.io/github/stars/reivaxy/aquaMonitor?style=social) ![GitHub forks](https://img.shields.io/github/forks/reivaxy/aquaMonitor?style=social)
Recifal aquarium monitoring with Arduino, alerts and settings by SMS and webApp, and statistics database. Monitors light level, temperature, water level, main power failure, and sends SMS alerts when configurable thresholds are reached.
- **License**: Creative Commons Attribution-NonCommercial 4.0 International License
- **Key Features**: Light level monitoring, temperature monitoring, water level monitoring, power failure detection, SMS alerts, web app interface, statistics database.

### [AquaPi (aquapi)](https://github.com/TheRealFalseReality/aquapi) ![GitHub stars](https://img.shields.io/github/stars/TheRealFalseReality/aquapi?style=social) ![GitHub forks](https://img.shields.io/github/forks/TheRealFalseReality/aquapi?style=social)
Aquarium monitoring and automation system using ESPHome and Home Assistant for smart home integration.
- **License**: GPL-3.0
- **Key Features**: Temperature/water level/pH/salinity monitoring, dissolved oxygen, peristaltic dosing pumps, CO2 control, modular sensor support, Home Assistant integration, customizable dashboards.

### [Domoticz](https://github.com/domoticz/domoticz) ![GitHub stars](https://img.shields.io/github/stars/domoticz/domoticz?style=social) ![GitHub forks](https://img.shields.io/github/forks/domoticz/domoticz?style=social)
Open source Home Automation System that monitors and configures various devices like lights, switches, sensors/meters (Temperature, Rain, Wind, UV, Electricity, Gas, Water, etc.) with notifications, cross-platform support, HTML5 web frontend, and extended logging.
- **License**: GPL-3.0
- **Key Features**: Home automation system, sensor monitoring, cross-platform support, HTML5 web frontend, notifications, extended logging.

### [Fish Tank Monitor and Control](https://github.com/rjsears/Fish_Tank_Monitor_and_Control) ![GitHub stars](https://img.shields.io/github/stars/rjsears/Fish_Tank_Monitor_and_Control?style=social) ![GitHub forks](https://img.shields.io/github/forks/rjsears/Fish_Tank_Monitor_and_Control?style=social)
Comprehensive monitoring and management system for fish tanks using Python/Flask with sensor integration.
- **License**: MIT
- **Key Features**: Temperature/pH/ammonia/EC/TDS monitoring, notifications (email/SMS), smart power strip control, CO2 injection management, historical data with Grafana.

### [OpenHAB](https://github.com/openhab/openhab-core) ![GitHub stars](https://img.shields.io/github/stars/openhab/openhab-core?style=social) ![GitHub forks](https://img.shields.io/github/forks/openhab/openhab-core?style=social)
Core framework of openHAB - Contains core bundles of the openHAB runtime. Not a product itself, but a framework to build solutions on top of, serving as the foundation for the main openHAB distribution.
- **License**: EPL-2.0 (Eclipse Public License 2.0)
- **Key Features**: Home automation framework, extensible platform, cross-platform compatibility, extensive addon ecosystem.

## Hardware Projects

### [Aqua-Controller](https://github.com/atanasyanew/aqua-app) ![GitHub stars](https://img.shields.io/github/stars/atanasyanew/aqua-app?style=social) ![GitHub forks](https://img.shields.io/github/forks/atanasyanew/aqua-app?style=social)
ESP8266-based fish tank automation using Mongoose OS and Node-RED for remote monitoring and control.
- **License**: MIT
- **Key Features**: Remote control via Node-RED dashboard, ESP8266-based design, MQTT communication, mobile app integration, real-time monitoring.

### [Aquaero](https://github.com/shred/pyquaero) ![GitHub stars](https://img.shields.io/github/stars/shred/pyquaero?style=social) ![GitHub forks](https://img.shields.io/github/forks/shred/pyquaero?style=social)
Python library and web service for accessing Aquaero fan and pump controllers by Aqua Computer GmbH & Co. KG. Community open source project not endorsed by or affiliated with Aqua Computer. Based on reverse engineering.
- **License**: LGPL-3.0
- **Key Features**: Python library for Aquaero controllers, web service interface, fan and pump control, community-driven reverse engineering.

### [Aquariumduino](https://github.com/FernandoGarcia/FerduinoAquariumController) ![GitHub stars](https://img.shields.io/github/stars/FernandoGarcia/FerduinoAquariumController?style=social) ![GitHub forks](https://img.shields.io/github/forks/FernandoGarcia/FerduinoAquariumController?style=social)
Open-source aquarium controller project based on the Arduino platform, featuring temperature, pH, ORP, and density monitoring/control, automatic top-off, partial water change automation, LED light control, cloud/lightning simulation, and automatic feeder with web interface.
- **License**: LGPL-3.0
- **Key Features**: Temperature/pH/ORP/density monitoring and control, automatic top-off, partial water change automation, LED light control with cloud/lightning simulation, automatic feeder, web interface.

### [Buce LED Controller](https://github.com/buce-led-controller/) ![GitHub stars](https://img.shields.io/github/stars/buce-led-controller/controller?style=social) ![GitHub forks](https://img.shields.io/github/forks/buce-led-controller/controller?style=social)
Compact ESP32-C3 based controller supporting 6 independent PWM channels for aquarium lighting.
- **License**: GPL-3.0
- **Key Features**: 6 independent PWM channels, high-resolution dimming, flexible dimming curves, compact design, programmable lighting schedules.

### [EcolibriumReef](https://github.com/EcolibriumReef/ecolibriumreef) ![GitHub stars](https://img.shields.io/github/stars/EcolibriumReef/ecolibriumreef?style=social) ![GitHub forks](https://img.shields.io/github/forks/EcolibriumReef/ecolibriumreef?style=social)
DIY Arduino-based aquarium controller with Android companion app.
- **License**: GPL-3.0
- **Key Features**: Basic monitoring functions, Android app integration, customizable automation routines, sensor support for temperature, pH, and water levels.

### [JeeLabs](https://github.com/jeelabs) ![GitHub stars](https://img.shields.io/github/stars/jeelabs?style=social) ![GitHub forks](https://img.shields.io/github/forks/jeelabs?style=social)
Organization focused on embedded systems, IoT, and Arduino-related projects. Most popular repository is esp-link (esp8266 wifi-serial bridge) with nearly 3,000 stars, followed by jeelib (Arduino library) with 507 stars.
- **License**: Various (Unlicense, BSD-2-Clause, etc.)
- **Key Features**: Embedded systems projects, IoT solutions, Arduino libraries, esp8266 support, wireless communication modules.

### [OpenAquarium](https://github.com/balub/open-aquarium-project) ![GitHub stars](https://img.shields.io/github/stars/balub/open-aquarium-project?style=social) ![GitHub forks](https://img.shields.io/github/forks/balub/open-aquarium-project?style=social)
Collection of FOSS tools/configs along with hardware and software for aquarium management. Contains configs/guides to FOSS tools and software and hardware developed for managing aquariums.
- **License**: Not explicitly specified in repository
- **Key Features**: Collection of FOSS tools, configuration guides, hardware designs, software for aquarium management.

### [OpenSprinkler](https://github.com/OpenSprinkler/OpenSprinkler-Firmware) ![GitHub stars](https://img.shields.io/github/stars/OpenSprinkler/OpenSprinkler-Firmware?style=social) ![GitHub forks](https://img.shields.io/github/forks/OpenSprinkler/OpenSprinkler-Firmware?style=social)
OpenSprinkler Unified Firmware for OpenSprinkler, OpenSprinkler Pi, and Linux-based OpenSprinkler. Supports multiple platforms and is actively maintained with substantial community following.
- **License**: GPL-3.0
- **Key Features**: Unified firmware for multiple platforms, sprinkler automation, timer controls, weather-based adjustments, community support.

### [Reef Angel](https://reefangel.com/) ![GitHub stars](https://img.shields.io/github/stars/ReefAngel/reefangel?style=social) ![GitHub forks](https://img.shields.io/github/forks/ReefAngel/reefangel?style=social)
Open-source aquarium controller built on the Arduino platform, designed for reef aquariums.
- **License**: GPL-3.0
- **Key Features**: Real-time monitoring of pH, temperature, water level, customizable relay control, expandable modules, user-friendly interface.

### [Smart Aquarium Project](https://github.com/yashkurkure/Smart-Aquarium-Project) ![GitHub stars](https://img.shields.io/github/stars/yashkurkure/Smart-Aquarium-Project?style=social) ![GitHub forks](https://img.shields.io/github/forks/yashkurkure/Smart-Aquarium-Project?style=social)
IoT-based aquarium automation with timed feeding, temperature monitoring, water level detection, and light control.
- **License**: MIT
- **Key Features**: Timed fish feeding with RTC, temperature monitoring, water level monitoring, automated light control, mobile connectivity.

### [TankBuilder](https://github.com/awitwicki/openTank) ![GitHub stars](https://img.shields.io/github/stars/awitwicki/openTank?style=social) ![GitHub forks](https://img.shields.io/github/forks/awitwicki/openTank?style=social)
Open source tank platform that includes implementations for ESP32, Raspberry Pi, and Arduino. Uses 3D printed parts, plastic tracks, DC motors, L298N motor driver, and supports various microcontrollers.
- **License**: Apache-2.0
- **Key Features**: Platform implementations for ESP32/Raspberry Pi/Arduino, 3D printed parts, motorized platform, track-based movement, multiple microcontroller support.

## Mobile Applications

### [Aquarium Log - Tank Manager](https://apps.apple.com/us/app/aquarium-log-tank-manager/id1621042664)
Powerful mobile app for aquarists to maintain and monitor aquarium information.
- **Platform**: iOS
- **Features**: Centralized aquarium information, fish details tracking, water measurement logging, maintenance scheduling, health monitoring.

### [Aquarium Manager](https://play.google.com/store/apps/details?id=com.aquarium.manager)
Free app for iOS and Android that centralizes all aquarium information.
- **Platform**: iOS, Android
- **Features**: Fish details and water measurements, maintenance logs, equipment tracking, reminder notifications.

### [Smart Aquarium Mobile App](https://github.com/SmartAquarium/mobile-app) ![GitHub stars](https://img.shields.io/github/stars/SmartAquarium/mobile-app?style=social) ![GitHub forks](https://img.shields.io/github/forks/SmartAquarium/mobile-app?style=social)
Phone app to monitor and control vitals of fish in a home aquarium via ESP32.
- **Platform**: iOS, Android
- **Features**: Real-time monitoring of aquarium parameters, remote control of equipment, data logging, alert notifications.

## Educational Resources

### [Arduino Aquarium Automation Tutorials](https://www.arduino.cc/en/tutorial/homePage)
Official Arduino tutorials including aquarium automation projects.
- **Content**: Step-by-step guides, code examples, circuit diagrams, sensor integration techniques.

### [Home Assistant Aquarium Configuration Examples](https://community.home-assistant.io/t/aquarium-automation-examples/234567)
Community forum with examples of aquarium automation setups using Home Assistant.
- **Content**: YAML configuration examples, integration guides, automation scripts, dashboard designs.

### [Open Source Aquarium Control System Guide](https://www.reef2reef.com/threads/open-source-aquarium-control-system.1142751/)
Community discussion thread documenting the development of an open-source aquarium control system using Raspberry Pi and Arduino components.
- **Content**: Hardware selection guides, wiring diagrams, programming tutorials, troubleshooting tips.

### [Using Technology for Aquarium Maintenance: A Scientific Approach](TECH_FOR_AQUARIUM_MAINTENANCE.md)
A comprehensive guide explaining how technology can be applied to aquarium maintenance from a scientific perspective, covering parameters to monitor, automation strategies, sensing technologies, and best practices.
- **Content**: Water quality parameters, automation solutions, sensing technologies, data management, safety considerations, emerging technologies, and implementation best practices.

## Specialized Tools

### [AQUASIM](https://github.com/jsta/AQUASIM) ![GitHub stars](https://img.shields.io/github/stars/jsta/AQUASIM?style=social) ![GitHub forks](https://img.shields.io/github/forks/jsta/AQUASIM?style=social)
Computer Program for the Identification and Simulation of Aquatic Systems. This is a mirror of the original AQUASIM software from EAWAG (Swiss Federal Institute of Aquatic Science and Technology).
- **License**: Not explicitly specified in repository
- **Key Features**: Aquatic system simulation, water quality modeling, environmental analysis tools.

### [FishPi](https://github.com/alicegodden/fishpi) ![GitHub stars](https://img.shields.io/github/stars/alicegodden/fishpi?style=social) ![GitHub forks](https://img.shields.io/github/forks/alicegodden/fishpi?style=social)
piRNA TE analysis tool - A Python-powered solution for piRNA sequence analysis that identifies complementary transposable element (TE) sequences, with focus on fish genomics.
- **License**: GPL-3.0
- **Key Features**: piRNA sequence analysis, transposable element identification, fish genomics research, Python-based analysis tools.

### [HYDROS App Framework](https://github.com/hydros-project/framework) ![GitHub stars](https://img.shields.io/github/stars/hydros-project/framework?style=social) ![GitHub forks](https://img.shields.io/github/forks/hydros-project/framework?style=social)
Open-source framework for connecting aquarium equipment to cloud services for remote monitoring.
- **License**: MIT
- **Key Features**: Cloud connectivity, remote monitoring and control, modular plugin architecture, data visualization tools.

### [Rabdomante](https://github.com/molok/rabdomante) ![GitHub stars](https://img.shields.io/github/stars/molok/rabdomante?style=social) ![GitHub forks](https://img.shields.io/github/forks/molok/rabdomante?style=social)
Brewing Water Chemistry Calculator that helps users find the optimal mix of waters and salts to match a target water profile. Calculates the distance from the target profile based on Calcium (Ca), Magnesium (Mg), Sodium (Na), Sulfate (SO4), Chloride (Cl), and Bicarbonates (HCO3).
- **License**: AGPL-3.0
- **Key Features**: Water chemistry calculation, optimal water profile matching, salt mixing calculator, brewing-focused water analysis.

### [Water Quality Analysis Tool](https://github.com/aquatic-research/water-quality-analyzer) ![GitHub stars](https://img.shields.io/github/stars/aquatic-research/water-quality-analyzer?style=social) ![GitHub forks](https://img.shields.io/github/forks/aquatic-research/water-quality-analyzer?style=social)
Python-based tool for analyzing water quality parameters and trends in aquarium environments.
- **License**: GPL-3.0
- **Key Features**: Water parameter tracking, trend analysis, predictive modeling, report generation, API integration.

### [aqua-simulation](https://github.com/ranjithrajv/aqua-simulation) ![GitHub stars](https://img.shields.io/github/stars/ranjithrajv/aqua-simulation?style=social) ![GitHub forks](https://img.shields.io/github/forks/ranjithrajv/aqua-simulation?style=social)
Aquarium Tank Simulator - A web-based tool that provides 3D visualization of aquarium tanks and calculates glass thickness recommendations based on tank dimensions.
- **License**: Unknown
- **Key Features**: 3D tank visualization using Three.js, flexible unit system (inches/cm for dimensions, gallons/liters for volume), real-time volume calculations with automatic unit conversion, smart glass thickness recommendations based on tank dimensions, responsive design for desktop and mobile.

## Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md). If you have an awesome project to add, feel free to open an issue or submit a pull request.

## License

This list is licensed under the [CC0 1.0 Universal](LICENSE).

## Related

- [Awesome Home Assistant](https://github.com/frenck/awesome-home-assistant) - A curated list of awesome things related to Home Assistant
- [Awesome IoT](https://github.com/phodal/awesome-iot) - A curated list of awesome Internet of Things projects