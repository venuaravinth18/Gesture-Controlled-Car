Gesture-Controlled Car using Arduino & MPU6050
🚗 Control a car with hand gestures using an accelerometer! This project uses an MPU6050 sensor to detect tilt movements and an L298N motor driver to control DC motors.

📌 Features
✅ Tilt-based control (Forward, Backward, Left, Right)
✅ Simple Arduino code with MPU6050 library
✅ L298N motor driver for smooth DC motor control
✅ Customizable sensitivity (adjust threshold values)
✅ Supports 4WD & 2WD car chassis

🛠 Hardware Components
Component	Quantity
Arduino Uno/Nano	1
MPU6050 (Accelerometer + Gyroscope)	1
L298N Motor Driver	1
4WD Car Chassis (or 2 DC Motors)	1
9V Battery (or LiPo)	1
Jumper Wires	As needed
🔌 Circuit Connections
MPU6050 → Arduino
MPU6050 Pin	Arduino Pin
VCC	5V
GND	GND
SDA	A4
SCL	A5
L298N → Arduino
L298N Pin	Arduino Pin
ENA	5
IN1	6
IN2	7
IN3	8
IN4	9
ENB	10
12V	Battery (+)
GND	Battery (-) & Arduino GND
