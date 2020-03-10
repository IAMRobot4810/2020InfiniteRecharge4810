# 2020InfiniteRecharge4810
## Conventions
- For directions in auton, use your right hand (Right Hand Rule): point your thumb, pointer, and middle fingers at right angles to each other. Those are the directions that are positive. 
- For angles, make a thumbs up with your right hand. If you attatched arrows to your fingernails, that's the direction of positive rotation. 
## CAN IDs: 
1. Drive Left Master
2. Drive Left Slave
3. Drive Right Master
4. Drive Right Slave
5. Climber Master - With Climb Forward Limit Switch
6. Climber Slave  - With Climb Reverse Limit Switch
7. Skywalker 
8. Intake
9. Index Conveyer  -  With Pidgeon
10. Index Feeder Wheel
11. Shooter Master
12. Shooter Slave
13. Vanna

## Solenoid IDs
0. 
1. Intake Extend
2. 
3. Intake Retract
4. Vanna Forward THE REST ARE NOT RIGHT cause don't exist
5. Vanna Reverse
6. Shooter Angle Forward, if applicable
7. Shooter Angle Reverse, if applicable

## PWM IDs
0. LEDs

## Joystick Mappings
### Driver Joystick
- Two Joysticks for driving (Left Y is throttle, 
- Right X is turn)
- Left Joystick press: turbo drivebase
- Triggers for intaking
- Left bumper: Toggle state of intake's pheumatics
- Right Bumper: auto-align to target with vision
- DB/Slider 0 sets the maximum % output of drive motors

### Operator Joystick

- DPAD: UP = Rotation Control
- DPAD DOWN = Position Control
- DPAD Sideways = Vanna manual
Vanna pops up whenever its not disabled
- Left Trigger: Manual Shooter Speed
- Buttons are for preset speeds
  - A: Target zone (requires 2 position hood, currently N/A)
  - B: Will be auto-range shooter, or something else as needed
  - X: initiation line
  - Y: Trench
- Left Joystick Y: Fine adjust shooter setpoints to be partway between the current one and the next highest one
- Right Trigger: Fire Ball (Run indexer)
- Left Bumper: run indexer backwards
- Right Joystick Y: climb up/down
- DB/Slider 1 says how much to multiply the shooter RPM setpoint by %


### Feedback
Driver Rumbles when Vanna done
Operator rumbles when Aligned (only in Teleop)
LEDs white when shooter up to speed
LEDs Blue otherwise
LEDs currently aren't on robot