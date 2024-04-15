# AI-Powered Drone Search and Rescue System

This project aims to develop an innovative solution for finding lost children using AI-powered drones. By leveraging cutting-edge technologies such as artificial intelligence and drone technology, we aim to significantly enhance the efficiency and effectiveness of search and rescue operations.

## Proposed System

The proposed approach involves the use of AI-powered drones equipped with real-time object detection capabilities to locate missing children. Key components of the proposed system include:

- Utilization of AI-powered drones for rapid coverage of large areas and real-time data streaming to rescue teams.
- Implementation of a YOLOv8 model on a Raspberry Pi for real-time human detection.
- Ten-step process including model training, drone calibration, and safe operation procedures.

## Advantages of Proposed System

The proposed system offers several advantages, including:

- Precision Navigation
- Unerring Detection
- Lifeline of Communication
- Synchronized Operations

## System Requirements

### Software Requirements

1. Convolutional Neural Networks (CNNs)
2. Mavlink
3. Mavproxy
4. Ardupilot
5. Computer Vision
6. OpenCV
7. Raspbian
8. YOLOv8 model

### Hardware Requirements

1. F450 quadcopter frame
2. A2212, 1000 KV BLDC motors
3. 1045 screws
4. 30A Cmonk ESCs
5. Pixhawk 2.4.8 hardware control unit
6. Flysky FSI6 radio transmitter and receiver
7. 3300mAh LiPo cell battery
8. XT60 connector
9. IMAX B6 AC charger
10. Tools: soldering iron, soldering wire, soldering paste, zip ties, dual-sided tape, scissors

## Implementation Technologies

### Path Planning and Altitude Fixing

Path planning involves creating a pre-programmed flight path for the drone, while altitude fixing ensures consistent height maintenance throughout the mission.

### Fail-safe Mechanism

A fail-safe mechanism ensures automated safety measures in case of anomalies or threshold exceedance during flight.

### YOLOv8

You Only Look Once (YOLO) v8 is a real-time object detection algorithm known for its speed and efficiency, making it ideal for drone object detection.

### MAVLink Protocol

MAVLink provides effective communication between drones and ground control stations, ensuring seamless interoperability.

## System Design

### Proposed System Architecture

The architecture involves hardware integration, calibration, Raspberry Pi integration, data collection, preprocessing, model implementation, and testing.

### Application Modules

1. Path Planning
2. Object Detection
3. Data Visualization
4. Response Generation

## Source Code

The source code includes implementations for drone hardware integration, software integration, YOLOv8 model training, Raspberry Pi integration, and path planning.

## Results

The project aims for an accuracy of at least 70% in object detection. Key metrics such as loss functions and mAP@50 are tracked during development.

## Conclusion

This project envisions a future where search and rescue missions are revolutionized by AI-powered drones. By combining advanced technologies, we aim to enhance the efficiency and effectiveness of search and rescue operations, potentially saving countless lives.

## Future Enhancements and Discussions

Future enhancements may include further refinement of the AI algorithms, integration of additional sensors for enhanced detection capabilities, and scalability for deployment in various environments.

