# Obstacle Avoidance Robot / Wheelchair

This project is a simple obstacle avoidance system for a robot or wheelchair. It uses an ultrasonic sensor to detect obstacles in front and avoids them by changing its direction.

## Components Used
- Arduino Uno (or compatible board)
- HC-SR04 Ultrasonic Sensor
- Motor Driver (L293D or L298N)
- DC Motors and Wheels
- Chassis (for the robot)
- Jumper Wires

## Wiring Instructions
- Connect the HC-SR04 sensor:
  - VCC to 5V
  - GND to GND
  - Trig to pin 12
  - Echo to pin 11

- Connect the Motor Driver to control the wheels:
  - Left Motor:
    - Input 1 to pin 7
    - Input 2 to pin 6
  - Right Motor:
    - Input 3 to pin 5
    - Input 4 to pin 4

## Setup
1. Install the Arduino IDE if you haven't already.
2. Open the Arduino IDE and create a new sketch.
3. Copy and paste the provided code into the sketch.
4. Upload the sketch to your Arduino board.

## Usage
1. Power up your robot or wheelchair.
2. The ultrasonic sensor will continuously measure the distance to obstacles.
3. If an obstacle is detected at a distance less than 50 cm, the robot will back up and turn to avoid it.
4. If there are no obstacles within 50 cm, the robot will move forward.

## Troubleshooting
- Make sure all connections are secure and correct.
- Check that your Arduino is powered properly.
- Ensure that the motor driver is working as expected.

## License
This project code is provided without a specific license, and you are free to use it for personal and educational purposes. However, please respect any licensing or usage restrictions for components and libraries used in this project.

Happy tinkering!
