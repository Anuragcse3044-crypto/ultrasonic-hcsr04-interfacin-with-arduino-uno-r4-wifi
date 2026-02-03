# Ultrasonic Distance Sensor — Arduino Uno R4 WiFi

## Project overview
A simple project that measures distance using an ultrasonic sensor (e.g., HC-SR04) with an Arduino Uno R4 WiFi board. The project files are `main.cpp` and `platformio.ini`.

## Files
1. `main.cpp` — Arduino sketch that triggers the ultrasonic sensor and prints distance to the Serial monitor.  
2. `platformio.ini` — PlatformIO project configuration (set your board and framework here).

## Hardware required
1. Arduino Uno R4 WiFi  
2. Ultrasonic sensor (HC-SR04 or equivalent)  
3. Jumper wires  
4. Breadboard (optional)

## Wiring
1. `VCC` -> `5V` on the Arduino  
2. `GND` -> `GND` on the Arduino  
3. `TRIG` -> Arduino digital pin `9` (matches `trigPin`)  
4. `ECHO` -> Arduino digital pin `10` (matches `echoPin`)

## Software / Setup
1. Install PlatformIO (VS Code extension or CLI).  
2. Open the project in PlatformIO / VS Code.  
3. Edit `platformio.ini` and set the `board` to the PlatformIO board ID for your Arduino Uno R4 WiFi. Example entry:
