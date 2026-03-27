---
layout: page
title: Quadcopter with PID Control over Wi-Fi
description: Custom-designed quadcopter with smartphone control and optimized embedded code
img: assets/img/projects/quadcopter/Quadcopter.jpg
importance: 3
category: prototyping
toc:
  sidebar: left
images:
  photoswipe: true
---

## Project Overview

{: .mt-5 .mb-4 .border-bottom .pb-3 .font-weight-bold }

**Duration:** August 2020 - December 2020  
**Type:** Personal Project  
**Platform:** Arduino Uno R3  
**Control:** Smartphone via Wi-Fi (RemoteXY)

Designed and built a fully functional quadcopter from scratch, featuring custom PID control algorithms and smartphone-based wireless control. This project combined mechanical design, electronics integration, embedded programming, and control systems engineering.

<div class="pswp-gallery" id="gallery-overview">
  <div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
      <a href="{{ '/assets/img/projects/quadcopter/Quadcopter.jpg' | relative_url }}" data-pswp-width="2824" data-pswp-height="2875" target="_blank">
        <img src="{{ '/assets/img/projects/quadcopter/Quadcopter.jpg' | relative_url }}" class="img-fluid rounded z-depth-1" alt="Quadcopter" />
      </a>
    </div>
  </div>
</div>
<div class="caption">
  Completed quadcopter prototype with custom 3D-printed frame and full electronics integration
</div>

[View Source Code on GitHub](https://github.com/vuluanhtu/quadcopter){: .btn .btn-sm .z-depth-1}

---

## Design & Development

{: .mt-5 .mb-4 .border-bottom .pb-3 .font-weight-bold }

### Mechanical Design

{: .mt-4 .mb-3 .font-weight-bold }

**Frame Design:**

- Designed quadcopter frame in SolidWorks
- Optimized for structural integrity and minimal weight
- Considered motor mounting, battery placement, and electronics housing
- Designed for 3D printing manufacturing

**Component Integration:**
Based on thrust, weight, and flight time requirements, selected and integrated:

- Brushless motors (sized for required thrust)
- Propellers (matched to motor specifications)
- Li-Po battery (capacity vs. weight optimization)
- Electronic Speed Controllers (ESCs)
- MPU6050 IMU sensor (gyroscope + accelerometer)
- ESP8266 Wi-Fi module for wireless communication
- Arduino Uno R3 microcontroller

<div class="pswp-gallery" id="gallery-fea">
  <div class="row justify-content-sm-center">
    <div class="col-sm-6 mt-3 mt-md-0">
      <a href="{{ '/assets/img/projects/quadcopter/frame_FEA_SolidWorks.png' | relative_url }}" data-pswp-width="283" data-pswp-height="214" target="_blank">
        <img src="{{ '/assets/img/projects/quadcopter/frame_FEA_SolidWorks.png' | relative_url }}" class="img-fluid rounded z-depth-1" alt="Frame FEA in SolidWorks" />
      </a>
    </div>
  </div>
</div>
<div class="caption">
  SolidWorks FEA simulation of the 3D-printed quadcopter frame to verify structural integrity
</div>

### Electronics & Power System

{: .mt-4 .mb-3 .font-weight-bold }

- Circuit design and wiring schematic
- Power distribution planning
- ESC calibration and motor control
- Sensor mounting and vibration isolation
- Battery management and safety considerations

---

## Control System Development

{: .mt-5 .mb-4 .border-bottom .pb-3 .font-weight-bold }

### PID Algorithm Implementation

{: .mt-4 .mb-3 .font-weight-bold }
Developed a complete PID (Proportional-Integral-Derivative) control algorithm **from scratch** in C++ to stabilize the quadcopter during flight.

**Control Loops:**

- **Roll stabilization** - Left/right tilt correction
- **Pitch stabilization** - Forward/backward tilt correction
- **Yaw control** - Rotation control
- **Altitude hold** - Throttle management

**Tuning Process:**

- Conducted multiple flight tests
- Iteratively adjusted PID parameters (Kp, Ki, Kd)
- Optimized for stability vs. responsiveness
- Achieved stable hover and responsive control

### Code Optimization

{: .mt-4 .mb-3 .font-weight-bold }
Embedded systems require efficient code execution for real-time control. Implemented advanced optimization techniques:

**Runtime Optimization (<4ms loop time):**

- **Interrupt Service Routines (ISR)** - Hardware-triggered sensor reading
- **Bitwise Operations** - Fast mathematical operations
- **Direct Port Access** - Bypassed Arduino abstractions for speed
- **Arduino Datasheet Analysis** - Register-level programming

**Result:** Achieved consistent <4ms control loop execution time, ensuring stable flight control at >250Hz update rate.

---

## Wireless Control Interface

{: .mt-5 .mb-4 .border-bottom .pb-3 .font-weight-bold }

### RemoteXY Smartphone App

{: .mt-4 .mb-3 .font-weight-bold }
Designed custom control interface on iPhone using RemoteXY platform:

- Dual-stick controller layout (throttle, pitch, roll, yaw)
- Real-time telemetry display
- Emergency stop function
- Wi-Fi communication via ESP8266 module

<div class="pswp-gallery" id="gallery-remotexy">
  <div class="row justify-content-sm-center">
    <div class="col-sm-10 mt-3 mt-md-0">
      <a href="{{ '/assets/img/projects/quadcopter/RemoteXY_control_interface.png' | relative_url }}" data-pswp-width="3377" data-pswp-height="1250" target="_blank">
        <img src="{{ '/assets/img/projects/quadcopter/RemoteXY_control_interface.png' | relative_url }}" class="img-fluid rounded z-depth-1" alt="RemoteXY Control Interface" />
      </a>
    </div>
  </div>
</div>
<div class="caption">
  Custom RemoteXY smartphone control interface with dual-stick layout for throttle, pitch, roll, and yaw
</div>

### Communication Protocol

{: .mt-4 .mb-3 .font-weight-bold }

- ESP8266 Wi-Fi module integration
- Arduino-to-ESP8266 serial communication
- Packet-based control commands
- Low-latency wireless link for responsive control

---

## Testing & Validation

{: .mt-5 .mb-4 .border-bottom .pb-3 .font-weight-bold }

### Prototype Assembly

{: .mt-4 .mb-3 .font-weight-bold }

- 3D printed all custom frame components
- Assembled electronics with proper wire management
- Motor and ESC configuration
- Balance testing and center of gravity verification

### Flight Testing

{: .mt-4 .mb-3 .font-weight-bold }

- Initial tethered testing for safety
- Progressive test flights with parameter tuning
- Stability verification in various conditions
- Control responsiveness evaluation
- Battery life and endurance testing

---

## Technical Skills Demonstrated

{: .mt-5 .mb-4 .border-bottom .pb-3 .font-weight-bold }

### Mechanical Engineering

{: .mt-4 .mb-3 .font-weight-bold }

- **CAD Design** - Structural frame design in SolidWorks
- **Component Selection** - Motor, propeller, and battery sizing
- **Weight Optimization** - Structural efficiency analysis
- **System Integration** - Mechanical and electrical integration

### Embedded Programming

{: .mt-4 .mb-3 .font-weight-bold }

- **C/C++ Programming** - Arduino IDE development
- **PID Control** - Custom algorithm implementation from first principles
- **Code Optimization** - ISR, bitwise operations, direct port access
- **Real-time Systems** - Timing-critical control loops

### Electronics & Mechatronics

{: .mt-4 .mb-3 .font-weight-bold }

- **Sensor Integration** - MPU6050 IMU interfacing
- **Motor Control** - Brushless ESC communication
- **Wireless Communication** - ESP8266 Wi-Fi module
- **Power Systems** - Li-Po battery management

### Control Systems

{: .mt-4 .mb-3 .font-weight-bold }

- **PID Tuning** - Empirical parameter optimization
- **Stability Analysis** - Flight dynamics and control
- **Sensor Fusion** - Gyroscope and accelerometer data integration

---

## Engineering Value

{: .mt-5 .mb-4 .border-bottom .pb-3 .font-weight-bold }

This project showcases the ability to:

- Design complete mechatronic systems from concept to working prototype
- Implement advanced control algorithms from theoretical understanding
- Optimize embedded code for real-time performance
- Debug and refine complex systems through iterative testing
- Work across mechanical, electrical, and software domains

The quadcopter demonstrates practical application of control theory, embedded programming, and system integration - skills directly applicable to modern mechatronic product development in industries ranging from robotics to automotive to aerospace.

---

## Performance Specs

- **Flight Time:** ~8-10 minutes (dependent on battery capacity)
- **Control Update Rate:** >250Hz (< 4ms loop time)
- **Wireless Range:** ~50 meters (Wi-Fi limitation)
- **Stability:** Stable hover with minimal drift
- **Response Time:** Highly responsive to control inputs
