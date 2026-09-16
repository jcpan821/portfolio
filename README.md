# Jia-Cheng Pan | Robotics, Control & Embedded Systems Portfolio

 welcome to my technical portfolio! I am currently an M.S. student in Power Mechanical Engineering at National Tsing Hua University (NTHU), specializing in robotics, 3D vision, feedback control systems, and embedded hardware development.

---

## 🛠 Technical Skills & Tools

* **Programming**: Python, C, MATLAB
* **CAD & Mechanical Design**: SolidWorks, AutoCAD, 3D Printing, Rapid Prototyping
* **Simulation & AI**: MATLAB/Simulink, NVIDIA Isaac Sim

---

##  Featured Projects

### 1. Graduate Thesis: 3D Trajectory Reconstruction & Feedback Pitching Control
* **Institution**: National Tsing Hua University (2026 – Present)
* **Keywords**: Dual Camera Calibration, Real-Time Ball Tracking, Closed-Loop Control, Pitching Machine
* **Overview**:
  * Built a real-time 3D flight path trajectory reconstruction pipeline for baseballs using stereo-vision twin camera setups.
  * Extracted instantaneous ball velocities and landing coordinate projections to feed into a multi-axis pitching machine controller for high-precision pitch replication.

---

### 2. Autonomous Object-Retrieval Robot (Senior Graduation Design)
* **Institution**: National Central University (2023 – 2024) [1]
* **Role**: Lead Mechanical & Embedded Systems Engineer (Contributed 60% of overall project architecture) [2]
* **Keywords**: SolidWorks, Mecanum Wheels, Raspberry Pi, OpenCV, STM32, PID Control [1, 3-5]
* **Technical Highlights**:
  * **Mechanical Design**: Designed the complete chassis, 10° inclined scoop ramp, 120mm x 160mm ball storage bay, and custom motor brackets using **SolidWorks**, with all structural parts fabricated via 3D printing [1, 3, 6, 7].
  * **Vision Recognition**: Implemented BGR/HSV color masking and Hough Circle Transform on **Raspberry Pi** using **OpenCV** to track ping-pong ball coordinates in real-time [4, 8].
  * **Motion Control**: Programmed an **STM32** MCU with closed-loop **PID velocity control** to drive 4 Mecanum wheels for omnidirectional steering, ball interception, and automatic unloading [1, 4, 5].

---

### 3. DC Motor Modeling & High-Precision PID Controller Design
* **Course Project**: Automatic Control II, NCU (2023) [9]
* **Keywords**: Transfer Function, State-Space, Root Locus Analysis, MATLAB/Simulink [9-11]
* **Technical Highlights**:
  * Derived transfer function models ($ Den = s^2 + 502.9s + 5935 $) and state-space equations based on FARS-795PH motor performance curves [10, 12].
  * Utilized **Root Locus Analysis** to strategically add a controller zero at $ s = -450 $ between system poles, completely eliminating step-response overshoot (%OS = 0%) and accelerating settling time to 0.0069s [13-15].
  * Validated dynamic step-input stability and transient characteristics in **MATLAB/Simulink** [12, 16].

---

### 4. Microcontroller Hardware Calculator with Logic Decoding Architecture
* **Course Project**: Microcontroller Applications, NCU (2021) [17]
* **Keywords**: ATmega128, C, 74LS138, 74LS374, Data Bus Sharing, Keypad Polling [17, 18]
* **Technical Highlights**:
  * Designed an embedded calculator running on an **ATmega128** MCU written in **C** [17, 19].
  * Engineered address decoding using 74LS138 (3-to-8 decoders), 74LS374 (data latches), and 74LS245 (bus transceivers) to prevent bus contention across shared Data Bus (PORTD) and Address Bus (PORTB) architectures [17, 18, 20].
  * Programmed 4x4 matrix keypad polling routines and dynamic multiplexing algorithms driving 4-digit 7-segment displays [18, 21-23].

---

### 5. AI Exhibition Project: Smart Factory Hand-Motion Robot Control
* **Event**: AI Project Exhibition, NCU [24]
* **Keywords**: MediaPipe, NVIDIA Isaac Sim, Gesture Control, Robotic Arm [24]
* **Technical Highlights**:
  * Developed a low-cost, real-time hand-gesture recognition pipeline using MediaPipe and Python [24].
  * Synchronized spatial coordinate transformations into NVIDIA Isaac Sim to achieve low-latency virtual remote control of industrial robotic arms [24].

---

### 6. Semiconductor Poster: CMP Endpoint Detection (EPD) Mechanisms
* **Event**: Semiconductor Industry Exhibition, NCU [25]
* **Keywords**: Chemical-Mechanical Planarization, Optical Sensing, Friction, Acoustic Emission [25]
* **Technical Highlights**:
  * Analyzed wafer planarization mechanisms and compared Endpoint Detection (EPD) methodologies: Optical reflectance, Friction torque changes, and Acoustic Emission (AE) signal analysis [25].

---

##  Certificates & Credentials

* **TOEIC Official Score Certificate** (多益英語測驗證書)
* **Academic Exhibition Awards & Posters**: NCU AI Project Exhibition & Semiconductor Industry Poster Presentation [24, 25]
* **

---
