# Line Following with Obstacle Avoidance Robot

This project is a simple line-following robot with obstacle avoidance. It uses an Arduino Nano and various components to build a robot that can follow a line while avoiding obstacles.

## Components Used

- **Arduino Nano R3**: The brain of the robot, responsible for controlling all operations.
- **L298N Dual Motor Controller Driver**: Drives the motors that move the robot.
- **2S 18650 Battery Holder – Dual Cell Battery Case**: Holds the 18650 Li-ion rechargeable batteries to power the robot.
- **18650 Li-ion Rechargeable Battery (3.7V, 2200mAh)**: Provides power to the robot.
- **Portable Battery Charger for 18650**: Used to charge the 18650 batteries.
- **5 Channel Infrared Reflective PIR Sensor Module**: Used for line following. It detects the black line on the ground.
- **Ultrasonic Sonar Sensor HC-SR04**: Measures distance to avoid obstacles.
- **LFR 3D Printed Body**: The body frame of the robot.
- **Cartoon Ultrasonic Sensor Bracket for HC-SR04**: Holds the ultrasonic sensor in place.
- **Mini Metal Ball Caster Wheel**: Acts as a support wheel for the robot.
- **Jumper Wires (M-M and M-F, 20+20 Pack)**: For connecting the components.
- **SPST On-Off Rocker Switch**: Turns the robot on and off.
- **Mini Breadboard**: For connecting wires and components easily.
- **6V 100 RPM DC Gear BO Motor - TT Dual Shaft Straight**: Used for driving the wheels of the robot.
- **Robot Wheel for BO Motors (65mm, Yellow)**: The wheels that allow the robot to move.

## Circuit Diagram

You can view the circuit diagram for this project by clicking on the link below:

![Circuit Diagram](https://raw.githubusercontent.com/ZAN-Tech-bd/Line-Following-with-Obstacle-Avoidance-Robot-Kit-/refs/heads/main/line_following_with_obstacle_avoidance_robot_circuit_image.png)

## How It Works

1. **Line Following**: 
   - The robot uses 5-channel infrared sensors to detect the black line on the ground. 
   - The sensors give signals to the Arduino, which decides which motor to activate to keep the robot on the track.

2. **Obstacle Avoidance**: 
   - The ultrasonic sensor (HC-SR04) measures the distance from obstacles in front of the robot.
   - If the robot detects an obstacle, it will stop, turn around, or navigate around the obstacle.

3. **Motors and Movement**: 
   - The L298N motor controller drives the two DC motors that control the wheels.
   - The motors are powered by the 18650 Li-ion batteries, which are recharged using the portable battery charger.

## Setup and Wiring

1. **Power Supply**: Connect the 18650 battery holder to the Arduino Nano and motor driver to power the system.
2. **Motors**: Connect the two DC motors to the L298N motor driver, which controls the direction and speed.
3. **Sensors**:
   - Connect the 5-channel infrared sensor module to the Arduino for line following.
   - Connect the ultrasonic sensor (HC-SR04) to the Arduino for obstacle detection.
4. **Switch**: Use the SPST On/Off switch to turn the robot on or off.

## Instructions

1. **Assembly**: 
   - Mount all components onto the 3D printed body.
   - Connect the motors to the motor controller and the sensors to the Arduino as per the wiring diagram.

2. **Programming**:
   - Upload the Arduino code to the Arduino Nano to control the robot's behavior.
   
3. **Testing**:
   - Place the robot on a track with a black line for line following.
   - Test the robot in an area with obstacles to check the obstacle avoidance functionality.

## Credits

This project was created and is maintained by the ZAN-Tech team. Special thanks to those who contributed to the components, code, and design!

---

Feel free to contribute or make improvements to this project by submitting a pull request.

