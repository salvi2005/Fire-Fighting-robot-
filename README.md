# Fire-Fighting-robot-
Fire fighting robot that extinguished the fire automatically with the using of sensors 
This Arduino code is designed to control a dual-motor system such as a simple robot or rover using an L298D motor driver IC with an Arduino board.

Core Functions
Pin Definitions: Pin assignments for motor driver inputs (AIN1, AIN2, BIN1, BIN2) and enables (PWM_A, PWM_B). These pins allow bidirectional control of two motors.

Motor Direction Control: Functions like forward(), backward(), turnLeft(), and turnRight() set the direction pins high or low to control motor rotation and direction.

Speed Control: Uses analogWrite() with PWM pins to vary motor speed; the value (0-255) dictates how fast motors spin.

Smooth Rotation: Code sections with angle loops (0 to 180, and 180 to 0) show rotating motors or servos in steps, likely for creating gradual movement or steering.

Common Use Cases
Basic Robot/Rover: Move forward, backward, stop, or turn left/right.

Steering or Servo Motor Control: Uses progressive angle changes to smoothly rotate actuators.

Remote or Automated Vehicle: Can be extended for line-following, obstacle avoidance, or manually controlled bots.

Notable Features
Serial Output: Setup function initializes serial output, useful for debugging or monitoring.

Modular Functions: Clearly defined functions (forward, backward, etc.) make the code easy to modify for more complex robots or to integrate with sensors for advanced projects.

Hardware Required
Arduino UNO or compatible board

L298D dual H-Bridge motor driver

Two DC motors (or one dual-axis system)

External power for motors

Jumper wires and basic prototyping components
