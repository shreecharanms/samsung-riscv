# SeismoGuard: Intelligent Earthquake Detection & Alert System

 Earthquake Detection System Using VSD Squadron Mini
The VSD Squadron Mini is a compact and efficient microcontroller designed for real-time data acquisition and processing. It features multiple digital and analog I/O pins, making it ideal for sensor-based applications. With its low power consumption and fast response time, it is well-suited for embedded systems and IoT projects.

## Project Overview:
This project implements an earthquake detection system using the D7S seismic sensor, which detects ground motion and provides real-time seismic data. When an earthquake is detected, the system triggers a buzzer and a lightbulb for immediate alerting. A 5V relay is used to control the bulb operation. The VSD Squadron Mini reads analog signals from the D7S sensor and activates the necessary output indicators based on seismic intensity.

##Components List

| Component	Specification |  Purpose            |
|------------------------ | ------------------- |
| VSD Squadron Mini | for processing data |
| D7S Seismic Sensor |	Detects earthquake vibrations |
| Buzzer	Audible alert | for earthquake detection |
| LEDs (2x) |	Status indicators (Ready & Shutoff) |
| Lightbulb	| Visual alert |
| 5V Relay Module |	Controls the lightbulb operation |
| Resistors	| Current limiting for LEDs |
| Wires & Connectors |	Circuit connections |
| Power Supply (5V)	| Powers Source |

## Pin Configuration:

| Pin	  | Function	   | Component     |
|-------|------------ |---------------|
| D1	   | utoff LED	  |Indicator LED  |
| D2	   | Ready LED	  |Indicator LED  |
| D3	   | Buzzer	     |Alert System   |
| D4	   | Relay Input |5V Relay (Bulb)| 
| A1	   | Sensor Data |D7S Sensor     |
| A2    | Sensor Data	|D7S Sensor     |

## Key Features:
Real-time seismic detection using the high-precision D7S sensor.
Immediate visual and auditory alerts through an LED, buzzer, and lightbulb.
Reliable relay control for automatic switching of external devices.
Low power consumption for continuous operation in disaster-prone areas.

This cost-effective and efficient system can be integrated into early warning systems, providing real-time alerts to enhance disaster preparedness and safety measures. 
