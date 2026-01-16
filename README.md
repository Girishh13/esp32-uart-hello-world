# ESP32 UART Hello World Project

## Description
This project demonstrates basic UART (serial) communication using the ESP32 microcontroller.  
The ESP32 transmits the string "Hello World" to a computer via USB serial communication, and the output is viewed using serial monitor software.

## Hardware Used
- ESP32 Development Board  
- USB Cable  
- PC / Laptop  

## Software Used
- Arduino IDE  
- ESP32 Board Package  
- Arduino Serial Monitor / PuTTY / Tera Term  

## Working Principle
The ESP32 uses its built-in UART peripheral to send serial data.  
The USB cable transfers this data to the computer using a USB-to-UART converter, where it is displayed on a serial terminal.

## Program Code

void setup()
{
  Serial.begin(9600);
}

void loop()
{
