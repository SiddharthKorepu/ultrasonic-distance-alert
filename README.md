# Ultrasonic Distance Alert

An Arduino project that measures distance with an HC-SR04 ultrasonic sensor and sounds a buzzer when an object comes closer than 20 cm.

## Components
- Arduino Uno
- HC-SR04 ultrasonic sensor
- Piezo buzzer
- Jumper wires

## Languages / Tools
- Arduino C/C++
- Tinkercad Circuits (simulation)

## How it works
The Arduino sends a 10 µs pulse to the TRIG pin. The sensor emits ultrasonic sound and the ECHO pin returns a pulse whose length equals the echo travel time. Distance = time × 0.034 / 2 (in cm). If the distance is below 20 cm, the buzzer turns on.

## Pin connections
- TRIG → pin 9
- ECHO → pin 10
- Buzzer → pin 8
- VCC → 5V, GND → GND

## What I learned
- How ultrasonic sensors measure distance
- Building and testing a circuit in Tinkercad

## Demo

<img width="935" height="1209" alt="1000112905" src="https://github.com/user-attachments/assets/1cf39d97-2336-47eb-8228-5afc5929173c" />
<img width="379" height="279" alt="1000112906" src="https://github.com/user-attachments/assets/9c5b96db-0ba4-4ba1-9626-dc4b29b1e721" />
