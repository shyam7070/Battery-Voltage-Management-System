# Battery-Voltage-Management-System

# Overview
This project is a Battery Voltage Monitoring System designed using an Arduino Uno. It measures the voltage of a 4.2V (2-cell) battery using a voltage divider circuit and displays the real-time voltage on an LCD/OLED screen. The system also features a low battery warning through a buzzer or LED when the voltage drops below 3.8V.

# Features

Real-time Voltage Measurement: Monitors and displays battery voltage continuously.
Voltage Divider Circuit: Safely steps down the battery voltage to a range compatible with the Arduino’s ADC.
Low Battery Alert: Activates a buzzer/LED when voltage falls below 3.8V.
Display Output: Supports 16x2 LCD or OLED display via I2C or parallel interface.
Optional Serial Output: Logs voltage data to the serial monitor for debugging.

# Technical Details
Microcontroller: Arduino Uno
Voltage Measurement Range: Up to 5V (stepped down to 3.3V)

# Components:
Voltage Divider (two resistors)
16x2 LCD or OLED Display
Buzzer/LED for low battery alert
Battery Connector (XT60, DC Jack, or Screw Terminal)
PCB Design: Developed using KiCad with proper routing, ground planes, and component spacing.

# Project Structure
Circuit_Schematic.pdf: Circuit design schematic created in KiCad.
Firmware_Code.ino: Arduino code for reading voltage, displaying it, and triggering low battery alerts.
PCB_Layout: PCB design files including Gerber files for fabrication.

# How to Use
1. Upload the Firmware: Flash the provided Arduino .ino file to your Arduino Uno
2. Assemble the Circuit: Connect all components as per the provided schematic.
3. Power Up: Connect the 4.2V battery to the system.
4. Monitor Voltage: View real-time voltage on the display.
5. Low Battery Alert: Buzzer/LED will activate if the voltage is below 3.8V.

# Tools Used
Arduino IDE: For firmware development.
KiCad: For circuit schematic and PCB design.

# Future Enhancements
Add data logging via serial monitor.
Integrate a charging module (optional).

# Acknowledgments
This project was developed as part of an Embedded Electronics & Hardware Internship Screening Test.
