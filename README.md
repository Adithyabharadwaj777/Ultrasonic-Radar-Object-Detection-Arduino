# Ultrasonic Radar Object Detection using Arduino

This project demonstrates a radar-like object detection system using an **Arduino UNO**, **ultrasonic sensor**, **servo motor**, and **MATLAB** for visualization. It detects objects in its surroundings and displays their distance and angle in real time, with visual feedback via LEDs and radar plots.

##  Project Objective

To design and implement a real-time radar prototype using Arduino and ultrasonic sensing that can:
- Detect stationary or moving objects
- Display object position using angle and distance
- Give real-time feedback via LEDs and MATLAB GUI

##  Problem Statement

Develop a prototype radar system based on Arduino that detects objects within a defined range and visualizes their positions using a radar-like interface.

---

##  Hardware Used
- Arduino UNO
- Ultrasonic Sensor (e.g., HC-SR04)
- Servo Motor
- Red and Green LEDs
- Resistors (e.g., 130Ω)
- Breadboard & Jumper Wires

##  Software Used
- Arduino IDE
- MATLAB

---

##  Working Principle

1. **Ultrasonic Sensor** sends out a sound wave.
2. It receives the echo from nearby objects.
3. Arduino calculates distance using Time-of-Flight.
4. Servo motor rotates the sensor across a sweep angle.
5. Red/Green LEDs indicate presence or absence of objects.
6. MATLAB GUI displays radar visualization.

---

##  Output

- **LED Feedback**: 
  - Red LED glows if object is detected.
  - Green LED glows if no object is detected.
  
- **MATLAB Radar Interface**: Real-time visualization of object position based on angle and distance.

---

##  Results & Conclusion

- Successfully detects objects and gives both visual (LED) and GUI-based (MATLAB) output.
- Responsive and relatively accurate within sensor limits.
- Could be improved in terms of range, precision, and GUI resolution.
- Applications: Robotics, Obstacle Avoidance, Automated Vehicles, Security Systems.

---

##  References

- [HowToMechatronics Arduino Radar](https://howtomechatronics.com/projects/arduino-radar-project/)
- [Robu Arduino Radar Guide](https://robu.in/arduino-radar-project-ultrasonic-based-radar-connection-and-code/)
- [Techatronic Radar Project](https://techatronic.com/radar-using-arduino-ultrasonic-sensor/)
- [How2Electronics Radar Model](https://how2electronics.com/arduino-radar-model-ultrasonic-sensor/)
- [YouTube Project Demo](https://www.youtube.com/watch?v=nYLdCVQLrGk)

---



