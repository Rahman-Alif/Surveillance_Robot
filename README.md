# Surveillance_Robot

The Surveillance Robot is a multifunctional IoT vehicle designed for remote monitoring. It operates by creating a standalone Wi-Fi Access Point, allowing a user to control the robot via a web browser on any smartphone or computer. The interface provides a live video feed from an onboard camera, which is mounted on a 2-axis servo gimbal (Pan/Tilt) to look around without moving the chassis. The user can also control the robot's movement (4-wheel drive), adjust motor speed, and toggle an LED light for night operations.

Simultaneously, a secondary system onboard, powered by an Arduino Uno, continuously monitors the ambient temperature and humidity using a DHT11 sensor. This data is displayed on a local LCD screen and transmitted via Bluetooth to a separate mobile app. The project successfully integrates motor driver logic, PWM signal generation, HTTP/WebSocket communication, and sensor data acquisition into a cohesive, battery-powered robotic platform.
