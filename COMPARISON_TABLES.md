# Comparison Tables for Aquarium Technology

This document provides comprehensive comparison tables for different aquarium technology solutions across various categories.

## Comprehensive Controllers Comparison

| Project | Microcontroller | Languages | Features | Difficulty | License | Cost Range | Power Consumption |
|---------|----------------|-----------|----------|------------|---------|------------|------------------|
| reef-pi | Raspberry Pi | Go, Python | Web UI, Camera, Dosing | Intermediate | Apache 2.0 | $100-200 | 5-10W |
| Marine Assistant | Raspberry Pi | C#, Python | Home Assistant Integration | Intermediate | GPL-3.0 | $80-150 | 5-10W |
| Aquareo | ESP32 | Arduino/C++ | MQTT, Dosing, Auto-top-off | Intermediate | MIT | $30-80 | 1-3W |
| Orca | Raspberry Pi | Python | Cloud Interface, Multiple Tanks | Advanced | GPL-3.0 | $120-250 | 5-10W |
| OctoRelay | Raspberry Pi | Python | Relay Control, OctoPrint | Beginner | AGPL-3.0 | $25-50 | 5-10W |

## Water Quality Monitoring Systems Comparison

| Project | Sensors Supported | Connectivity | Data Logging | Automation Support | Platform | Max Sensors | Price Range |
|---------|------------------|--------------|--------------|-------------------|----------|-------------|-------------|
| AquaPi | pH, Temp, Water Level | WiFi, Home Assistant | Yes | Yes | ESP32 | 5-10 | $40-100 |
| Fish Tank Monitor | pH, Temp, Ammonia | WiFi, Web | Yes | Limited | Raspberry Pi | 8-15 | $60-150 |
| AquaMonitor | Temp, Light, Power | Arduino, SMS | Yes | No | Arduino | 3-5 | $30-80 |
| AquaPi (aquapi) | pH, Temp, Water Level | WiFi, Home Assistant | Yes | Yes | ESP32/ESP8266 | 10-20 | $50-120 |

## Feeding Automation Systems Comparison

| Project | Dispensing Method | Scheduling | Portion Control | Remote Access | Platform | Power | Price Range |
|---------|------------------|------------|---------------|---------------|----------|-------|-------------|
| Automated Fish Feeder | Servo-based | Yes | Yes | Yes | Raspberry Pi | 5V/2A | $50-120 |
| Smart Feeding Robot | Stepper-based | Yes | Adaptive | Yes | ESP32-CAM | 12V/1A | $70-150 |
| Timer Feeder | Timer-based | Yes | Fixed | No | Mechanical | Battery | $20-60 |

## Lighting Control Systems Comparison

| Project | Channels | Spectrum Control | Dimming | Scheduling | Platform | Power | Price Range |
|---------|----------|------------------|---------|------------|----------|-------|-------------|
| Smart LED Controller | 6+ | RGB+W | 0-100% | Yes | ESP32 | 12V/5A | $80-200 |
| Chromatic Lighting | 4 | Full Spectrum | 0-100% | Yes | Arduino Mega | 12V/10A | $100-250 |
| Basic Timer | 1 | None | On/Off | Yes | Mechanical | 120VAC | $15-40 |

## AI/ML Solutions Comparison

| Project | Function | Hardware Requirements | ML Framework | Accuracy | Platform | Training Required | Price Range |
|---------|----------|----------------------|--------------|----------|----------|-----------------|-------------|
| AI Fish Behavior Monitor | Behavior Analysis | Pi 4, Camera | TensorFlow Lite | High | Raspberry Pi | Yes | $150-300 |
| Water Quality Predictor | Prediction | Any SBC | Scikit-learn | Medium | Any | Yes | Free-$50 |
| Fish Counter | Counting | Pi, Camera | OpenCV | Medium | Raspberry Pi | No | $100-200 |

## 3D Printing Projects Comparison

| Project | Complexity | Print Time | Filament Type | Application | Difficulty | Print Volume | Cost |
|---------|------------|------------|---------------|-------------|------------|--------------|------|
| Filter Media | Low | 2-4h | PLA/PETG | Filtration | Beginner | Small | $5-15 |
| Equipment Mounts | Low | 1-3h | PLA/ABS | Mounting | Beginner | Small | $3-10 |
| Dispenser Parts | Medium | 4-8h | PLA/ABS | Feeding | Intermediate | Medium | $10-25 |
| Pump Housings | High | 8-20h | ABS/PETG | Plumbing | Advanced | Large | $20-50 |

## Mobile Apps Comparison

| Project | Platform | Features | Connectivity | Cost | Offline Capable | Data Sync |
|---------|----------|----------|--------------|------|----------------|-----------|
| Aquarium Log | iOS | Logging, Scheduling | Manual | Paid | Yes | Cloud |
| Aquarium Manager | iOS/Android | Logging, Reminders | Manual | Free | Yes | Cloud |
| Smart Aquarium App | iOS/Android | Monitoring, Control | Direct | Free | No | Real-time |

## Educational Resource Comparison

| Resource | Level | Format | Duration | Prerequisites | Certification | Cost |
|----------|-------|--------|----------|---------------|---------------|------|
| Arduino Tutorials | Beginner | Video/Text | 10-20h | None | No | Free |
| Home Assistant Guide | Intermediate | Text/Forum | 20-40h | Basic IT | No | Free |
| Advanced Analytics | Advanced | Course | 40-80h | Programming | Yes | $50-200 |

## Hardware Projects Comparison

| Project | Microcontroller | Sensors Supported | Connectivity | Difficulty | Primary Function | Power | Price |
|---------|----------------|------------------|--------------|------------|------------------|-------|-------|
| Aqua-Controller | ESP8266 | 3-5 | WiFi/MQTT | Intermediate | Automation | 3.3V/0.5A | $25-60 |
| Aquaero | PC-Based | 10+ | USB/Network | Advanced | Fan/Pump Control | 12V/2A | $100-300 |
| Aquariumduino | Arduino | 8+ | Serial/WiFi | Intermediate | Full Control | 12V/1A | $40-100 |
| OpenSprinkler | ESP8266/32 | 5-8 | WiFi | Intermediate | Irrigation | 24VAC | $50-150 |
| Reef Angel | Arduino | 10+ | USB/Display | Intermediate | Reef Control | 12V/2A | $80-200 |

## Water Chemistry Management Comparison

| Project | Function | Hardware | Connectivity | Automation Level | Platform | Cost Range | Maintenance |
|---------|----------|----------|--------------|------------------|----------|------------|-------------|
| Automated Dosing System | Chemical Dosing | Peristaltic pumps, sensors, controller | WiFi/MQTT | High | ESP32/RPi | $100-300 | Weekly |
| pH Buffering System | pH Stabilization | pH sensors, chemical pumps | WiFi/MQTT | High | ESP32/RPi | $80-200 | Daily |
| Alkalinity Manager | Alk Management | Alk test integration, pumps | WiFi/MQTT | Medium | RPi | $150-400 | Weekly |
| Nutrient Control | Nutrient Control | Multiple sensors, pumps | WiFi/MQTT | High | RPi | $200-500 | Weekly |
| RO Controller | Water Purification | RO components, sensors | WiFi | Medium | ESP32 | $100-250 | Monthly |

## Biological Filtration Systems Comparison

| Project | Function | Sensors | Automation Level | Platform | Cost Range | Maintenance |
|---------|----------|---------|------------------|----------|------------|-------------|
| Biofilter Monitor | Filter Efficiency | Ammonia, nitrite, nitrate | Low | ESP32/RPi | $50-150 | Weekly |
| Bacteria Cultivation | Bacteria Growth | Temperature, oxygen | Medium | Arduino/RPi | $40-120 | Daily |
| Skimmer Controller | Skimming Control | Flow, bubble sensors | Medium | ESP32 | $60-180 | Weekly |
| UV Automation | Sterilization | Flow, timer | Medium | ESP32 | $70-200 | Monthly |

## Aquatic Plant Care Systems Comparison

| Project | Function | Sensors | Controls | Platform | Cost Range | Maintenance |
|---------|----------|---------|----------|----------|------------|-------------|
| CO2 Controller | CO2 Injection | pH, pressure | Solenoids, pumps | ESP32 | $40-120 | Daily |
| Fertilization System | Nutrient Dosing | pH, TDS | Pumps, valves | RPi/ESP32 | $100-300 | Weekly |
| Growth Monitor | Plant Health | Cameras, light | Data logging | RPi | $80-200 | Low |
| Algae Prevention | Algae Control | Light, nutrient | Lights, UV | ESP32/RPi | $60-180 | Weekly |

## Emergency and Safety Systems Comparison

| Project | Function | Response Type | Sensors | Platform | Cost Range | Reliability |
|---------|----------|---------------|---------|----------|------------|-------------|
| Leak Detection | Water Detection | Automatic shutoff | Water sensors | ESP32/Arduino | $30-100 | High |
| Overflow Prevention | Water Level | Pump shutoff | Level sensors | ESP32/Arduino | $25-80 | High |
| Power Monitor | Power Loss | Backup activation | Power sensors | ESP32/Arduino | $20-70 | Medium |
| Emergency Aeration | Oxygen Supply | Automatic activation | Oxygen sensors | Arduino/ESP32 | $35-120 | Medium |

## Energy Management Comparison

| Project | Function | Measurement | Control | Platform | Cost Range | Savings |
|---------|----------|-------------|---------|----------|------------|---------|
| Power Monitor | Consumption | Current, voltage | Logging | ESP32/Arduino | $25-80 | 10-20% |
| Smart Power Strip | Outlet Control | Power draw | Individual relays | ESP32 | $40-150 | 15-25% |
| Energy Automation | Optimization | Multiple | Scheduling | RPi | $80-200 | 20-30% |
| Solar System | Renewable | Solar, battery | Load management | Arduino/RPi | $200-600 | 50-90% |

## Specialized Tools Comparison

| Tool | Primary Use | Platform | Language | License | Complexity | Price |
|------|-------------|----------|----------|---------|------------|-------|
| AQUASIM | Simulation | PC | C++ | Unspecified | Advanced | Free |
| FishPi | Genomics | PC | Python | GPL-3.0 | Advanced | Free |
| HYDROS Framework | Cloud Connect | Any | Python | MIT | Intermediate | Free |
| Rabdomante | Water Chem | PC | Python | AGPL-3.0 | Intermediate | Free |
| Water Analyzer | Analysis | PC | Python | GPL-3.0 | Intermediate | Free |
| Aqua Simulation | 3D Visualization | Web | JavaScript | Unspecified | Beginner | Free |