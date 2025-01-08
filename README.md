# Voice-Controlled Bluetooth RC Car with Obstacle Detection

This project demonstrates a voice-controlled car controlled via a mobile application using Bluetooth technology. The car also features obstacle detection using an ultrasonic sensor. This versatile system has potential applications in entertainment, delivery systems, and even surveillance tasks with added enhancements.

## Overview

The project revolves around controlling an RC car via a mobile device using voice commands or button controls from a Bluetooth-enabled Android application. Additionally, it incorporates an ultrasonic sensor to measure distances and avoid collisions with objects in its path.

## Applications
- **Entertainment:** An interactive and fun robot car game for children.
- **Surveillance:** With added features like a webcam, it could be used for spying or monitoring purposes.
- **Delivery Systems:** Adaptable for contactless delivery of goods in specialized environments.

## Components
1. **Hardware:**
   - Arduino UNO
   - L298N Motor Driver
   - HC-SR04 Ultrasonic Module
   - HC-05 Bluetooth Module
   - Prototyping board and cables
   - UNO Cable
   - Vehicle Kit (Chassis, wheels, motors)
   
2. **Software:**
   - Arduino IDE for programming the Arduino board.
   - Android application for Bluetooth communication.

## Features
1. **Voice Control:** Control the car's movement using voice commands via the mobile app.
2. **Obstacle Detection:** Measure the distance between the vehicle and obstacles using the ultrasonic sensor.
3. **Bluetooth Communication:** Seamless communication between the mobile application and the Arduino board.
4. **Modular Design:** Easy to add features like a camera for additional functionality.

## Libraries Used
- **Ultrasonic Library:** Reads data from the ultrasonic sensor to measure and print the distance between obstacles and the sensor.
- **Software Serial Library:** Enables serial communication between the Arduino and Bluetooth module for receiving data from the Android application.

## Commands
| **Command**  | **Action**           |
|--------------|----------------------|
| `forward`    | Moves the car forward |
| `backward`   | Moves the car backward |
| `left`       | Turns the car left    |
| `right`      | Turns the car right   |
| `stop`       | Stops the car         |

## How It Works
1. **Control Interface:** The car is controlled via an Android app that sends commands to the HC-05 Bluetooth module.
2. **Obstacle Detection:** The HC-SR04 ultrasonic sensor continuously measures the distance between the car and nearby objects, ensuring collision avoidance.
3. **Motor Control:** The L298N Motor Driver receives instructions from the Arduino to operate the car's DC motors based on commands received via Bluetooth.

## Setup Instructions

### Hardware Setup
1. Connect the Arduino UNO, L298N Motor Driver, HC-05 Bluetooth module, and HC-SR04 ultrasonic sensor according to the circuit diagram.
2. Assemble the vehicle kit with the motors and chassis.

### Software Setup
1. Install the **Arduino IDE** on your PC.
2. Download and install the required libraries:
   - `Ultrasonic.h`
   - `SoftwareSerial.h`
3. Upload the Arduino code (`voice_control_car.ino`) to the Arduino board.

## Future Enhancements
- Add a webcam for live video feed to enable surveillance and monitoring.
- Enhance the car's capabilities for military applications, such as autonomous navigation and real-time data transmission.
- Expand obstacle detection to include dynamic pathfinding algorithms.
- Introduce additional sensors for environmental awareness, such as temperature or gas sensors.

## Project Impact
The knowledge and technology used in this project are stepping stones toward solving more complex problems. By advancing these capabilities, this project opens opportunities for applications in military, logistics, and entertainment sectors.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgements
- **Arduino Community:** For providing comprehensive guides and tutorials.
- **Developers of Ultrasonic and Software Serial Libraries:** For simplifying sensor and communication handling.

Feel free to reach out for any questions or collaborations related to this project!
