# GSM-based-Home-Security-System
Home Security System - To alert the owner or a person in danger if any gas leak or intrusion detection takes place using the PIR sensor and Gas Leakage sensor GSM module.

This GitHub repository contains the code for a Home Security System that utilizes Arduino along with GSM integration for enhanced monitoring and immediate alerting capabilities. The system is designed to monitor intruders and respond to emergency situations such as fire or gas leaks by sending SMS alerts to homeowners through a GSM modem.

Hardware Requirements:

Arduino Board 328P: The core component of the system, featuring 14 digital input/output pins, 6 analog inputs, USB connection, power jack, ICSP header, and a reset button. This board serves as the brain of the system and is the interface for connecting various sensors and modules.

GSM 800A Module: This module provides GSM/GPRS connectivity and features an RS232 interface. It operates on dual-band GSM/GPRS frequencies (900/1800MHz) and allows for voice calls, SMS, and internet access. It connects to the Arduino via a serial cable and enables communication with homeowners.

PIR Sensor: The Passive Infrared Sensor (PIR) is used to detect motion within its field of vision. It plays a crucial role in detecting intruders and can trigger alerts when motion is detected.

MQ 6 Gas Leakage Sensor: This sensor is designed to detect the presence of flammable gases, including propane, butane, and methane. It's essential for identifying gas leaks and ensuring the safety of the home.

Functionality:

The main purpose of this home security system is to monitor the premises for intrusions and respond to emergencies, ensuring homeowners' safety. The system can:

Detect intruders through the use of PIR sensors. Identify gas leaks using the MQ-6 Gas Leakage Sensor. Send immediate SMS alerts to homeowners through the GSM modem in case of any detected anomalies. Enable homeowners to take appropriate actions in response to alerts, such as contacting authorities or addressing the situation remotely.
