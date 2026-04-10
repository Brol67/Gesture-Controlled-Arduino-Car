\\# Gesture-Controlled Arduino Car







An embedded systems project that demonstrates intuitive human–machine interaction by controlling a 4WD Arduino car using hand gestures. The system integrates accelerometer and gyroscope sensors with wireless communication modules to translate hand movements into car commands.







\\## Overview



\\- \\\*\\\*Objective:\\\*\\\* Build a gesture-controlled robotic car using Arduino microcontrollers.



\\- \\\*\\\*Hardware:\\\*\\\* Arduino Uno, Arduino Nano, MPU6050 accelerometer/gyroscope, NRF24L01 wireless modules, L298 motor driver, 4WD car chassis, Li-ion batteries.



\\- \\\*\\\*Software:\\\*\\\* Arduino IDE, KiCad for schematics.



\\- \\\*\\\*Deliverables:\\\*\\\* Report, source code, schematics, images, and test videos.







\\## Features



\\- Wireless communication between transmitter (hand controller) and receiver (car).



\\- Real-time gesture recognition using MPU6050 sensor.



\\- Control of car movements: forward, backward, left, right, stop.



\\- Modular design with clear separation of transmitter and receiver code.







\\## Folder Structure



\\- `Report.pdf` → Full academic report documenting design, implementation, and results.



\\- `code/`  



\&#x20; - `car\\\_receiver.ino` → Arduino sketch for the car (receiver).  



\&#x20; - `hand\\\_transmitter.ino` → Arduino sketch for the hand gesture controller (transmitter).



\\- `schematics/`  



\&#x20; - `car\\\_diagrams/` → Circuit diagrams for the car.  



\&#x20; - `hand\\\_diagrams/` → Circuit diagrams for the hand controller.



\\- `images/`  



\&#x20; - `car/` → Photos of the car prototype.  



\&#x20; - `hand/` → Photos of the hand controller.



\\- `videos/` → Test videos demonstrating the system in action.







\\## How to Use



1\\. Upload `hand\\\_transmitter.ino` to Arduino Nano (gesture controller).



2\\. Upload `car\\\_receiver.ino` to Arduino Uno (car).



3\\. Connect hardware according to diagrams in `schematics/`.



4\\. Power both units with Li-ion batteries.



5\\. Control the car by tilting/rotating the hand controller.





