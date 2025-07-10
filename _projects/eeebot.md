---
layout: page
title: EEEBot
description: As part of my first-year construction project, I built and programmed an autonomous robot using sensors and microcontrollers.
img: assets/img/eeebot/eeebot.jpg
importance: 1
category: Education
---

## Skills Gained

- Circuit building and soldering  
- Microcontroller programming (ESP32)  s
- Sensor integration (Ultrasonic, IMU)  
- Basic control systems (PID)  
- Communication protocols (I2C, MQTT)  
- Intro to computer vision with OpenCV  

---

## Key Features of My EEEBot

- Line following with sensor array  
- Stops when obstacle is within 20 cm  
- Remote control via web interface  
- OpenCV image recognition (e.g., detects arrow direction)  

---

## Challenges & Lessons

1. Issues with motor speed mismatch  
2. PID tuning complexity  
3. HSV mismatch in image processing  
4. Learned how to debug both hardware and software  

---

## Final Thoughts

Whilst this was a course-standard project, it gave me solid hands-on experience and built my confidence working with hardware and embedded systems.

---

## Gallery

<div class="text-center mt-3">
  <div style="width: 80%; margin: auto;">
    {% include figure.liquid 
      path="assets/img/eeebot/eeebot.jpg" 
      title="EEEBot robot overview" 
      class="img-fluid rounded z-depth-1" 
    %}
  </div>
  <div class="caption mt-1">Full view of the autonomous EEEBot robot</div>
</div>

<div class="row">
  <div class="col-sm-6 mt-3 text-center">
    {% include figure.liquid path="assets/img/eeebot/processed_image.jpg" title="OpenCV processed image" class="img-fluid rounded z-depth-1" %}
    <div class="caption mt-1">Processed image from OpenCV</div>
  </div>
  <div class="col-sm-6 mt-3 text-center">
    {% include figure.liquid path="assets/img/eeebot/web_control_dash.jpg" title="Node-RED dashboard" class="img-fluid rounded z-depth-1" %}
    <div class="caption mt-1">Web interface for remote control using Node-RED</div>
  </div>
</div>

<div class="row">
  <div class="col-sm-6 mt-3 text-center">
    {% include figure.liquid path="assets/img/eeebot/arrow_terminal_output.jpg" title="Terminal output" class="img-fluid rounded z-depth-1" %}
    <div class="caption mt-1">OpenCV arrow direction detection in terminal</div>
  </div>
  <div class="col-sm-6 mt-3 text-center">
    {% include figure.liquid path="assets/img/eeebot/block_diagram.jpg" title="System block diagram" class="img-fluid rounded z-depth-1" %}
    <div class="caption mt-1">Block diagram of the overall system</div>
  </div>
</div>

<div class="row">
  <div class="col-sm-6 mt-3 text-center">
    {% include figure.liquid path="assets/img/eeebot/ir_sensor_array.jpg" title="IR sensor array" class="img-fluid rounded z-depth-1" %}
    <div class="caption mt-1">IR sensor array used for line following with PID</div>
  </div>
  <div class="col-sm-6 mt-3 text-center">
    {% include figure.liquid path="assets/img/eeebot/sensor_circuit_diagram.jpg" title="Sensor circuit diagram" class="img-fluid rounded z-depth-1" %}
    <div class="caption mt-1">Circuit diagram for the IR sensor array</div>
  </div>
</div>

