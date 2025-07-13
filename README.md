# 🚦 Traffic Light Simulation using Arduino
This project simulates a traffic light system using an Arduino UNO and three LEDs (red, yellow, green). Each LED represents one of the standard traffic signals, and the Arduino controls the sequence using delays.

## 🔧 Components Used:
- Arduino UNO

- Breadboard

- 3 LEDs (Red, Yellow, Green)

- 3 × 220Ω Resistors

- Jumper wires

## 🔌 Circuit Description:
- Red LED → Digital Pin 13

- Yellow LED → Digital Pin 12

- Green LED → Digital Pin 11
Each LED is connected in series with a 220Ω resistor to limit the current. All cathodes are connected to GND.

## 💡 Working Principle:
The Arduino turns on the LEDs in the following sequence to simulate a traffic light:

1. Red ON – Stop

2.Red OFF, Yellow ON – Get Ready

3. Yellow OFF, Green ON – Go

4. Repeats in a loop

## 🧾 Arduino Code File:
The sketch controlling the traffic light simulation is available in the file:

📂 `Traffic_Light.ino`

📸 Demonstration Snapshot:
<img width="1375" height="773" alt="image" src="https://github.com/user-attachments/assets/09103e69-988c-4e55-8bc2-1b9fb1d26b01" />
