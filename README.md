
# Humanoid Servo Project

This project demonstrates controlling **6 servo motors** using an Arduino to simulate basic humanoid robot movements.

## Project Idea
The goal of this project is to test and control multiple servos in a humanoid robot setup, including:
- Performing a sweep motion with all 6 servos.
- Holding all servos at a neutral position (90°).
- Designing a walking motion algorithm for humanoid robots.

## How the Project Works
1. **Initialization**: All 6 servos are attached to the Arduino digital pins (2–7).  
2. **Sweep Motion**: When the program runs, all servos move together from 0° to 180° and back, performing a “sweep” motion for **2 seconds**.  
3. **Hold Position**: After the sweep, all servos are fixed at **90°**, representing the neutral stance of the humanoid robot.  
4. **Walking Motion Algorithm (Conceptual)**: Although the hardware only demonstrates sweep and hold, a theoretical walking motion is designed:
   - Lift one leg by moving hip, knee, and ankle joints.
   - Shift the body weight to the supporting leg.
   - Place the lifted leg down.
   - Repeat with the opposite leg to simulate walking.

## Files
- `HumanoidServo.ino` → Arduino code for 6 servos sweep and hold.  
- `image` → Pictures of the TinkerCad setup.
- `video` → short demo of project
   Download the demo video [here](video.mp4)


## Hardware
- Arduino Uno  
- 6 Servo Motors  
- Breadboard (optional)  
- Jumper wires  

## Notes
- The sweep motion allows testing all servos at once and ensures correct wiring.  
- The walking motion is described algorithmically for future implementation.  
- Images illustrate the TinkerCad connection of servos to Arduino.
