# Portfolio

 welcome to my technical portfolio! I am currently an M.S. student in Power Mechanical Engineering at National Tsing Hua University (NTHU), specializing in robotics, 3D vision, feedback control systems, and embedded hardware development.

---

## Technical Skills & Tools

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

### 2. [Autonomous Object-Retrieval Robot (Senior Graduation Design)](大學畢業專題.pdf)
* **Institution**: National Central University (2024)
* **Role**: Lead Mechanical & Embedded Systems Engineer (Contributed 60% of overall project architecture)
* **Keywords**: SolidWorks, Mecanum Wheels, Raspberry Pi, OpenCV, STM32, PID Control
* **Technical Highlights**:
  * **Mechanical Design**: Designed the complete chassis, 120mm x 160mm ball storage bay, and custom motor brackets using **SolidWorks**, with all structural parts fabricated via 3D printing 
  * **Vision Recognition**: Implemented BGR/HSV color masking and Hough Circle Transform on **Raspberry Pi** using **OpenCV** to track ping-pong ball coordinates in real-time.
  * **Motion Control**: Programmed an **STM32** MCU with closed-loop **PID velocity control** to drive 4 Mecanum wheels for omnidirectional steering, ball interception, and automatic unloading.

---

### 3. [DC Motor Modeling & High-Precision PID Controller Design](馬達PID控制器.pdf)
* **Course Project**: Automatic Control II, NCU (2023)
* **Keywords**: Transfer Function, State-Space, Root Locus Analysis, MATLAB/Simulink
* **Technical Highlights**:
  * Derived transfer function models ($ Den = s^2 + 502.9s + 5935 $) and state-space equations based on FARS-795PH motor performance curves.
  * Utilized **Root Locus Analysis** to strategically add a controller zero at $ s = -450 $ between system poles, completely eliminating step-response overshoot (%OS = 0%) and accelerating settling time to 0.0069s.
  * Validated dynamic step-input stability and transient characteristics in **MATLAB/Simulink**.

---

### 4. [Microcontroller Hardware Calculator with Logic Decoding Architecture](微控制器課程成果報告.pdf)
* **Course Project**: Microcontroller Applications, NCU (2021)
* **Keywords**: ATmega128, C, 74LS138, 74LS374, Data Bus Sharing, Keypad Polling
* **Technical Highlights**:
  * Designed an embedded calculator running on an **AVRM128** MCU written in **C**.
  * Engineered address decoding using 74LS138 (3-to-8 decoders), 74LS374 (data latches), and 74LS245 (bus transceivers) to prevent bus contention across shared Data Bus (PORTD) and Address Bus (PORTB) architectures.
  * Programmed 4x4 matrix keypad polling routines and dynamic multiplexing algorithms driving 4-digit 7-segment displays.

---

### 5. [AI Exhibition Project: Smart Factory Hand-Motion Robot Control](<AI project poster.pdf>)
* **Event**: AI Project Exhibition, NCU
* **Keywords**: MediaPipe, NVIDIA Isaac Sim, Gesture Control, Robotic Arm
* **Technical Highlights**:
  * Developed a low-cost, real-time hand-gesture recognition pipeline using MediaPipe and Python.
  * Synchronized spatial coordinate transformations into NVIDIA Isaac Sim to achieve low-latency virtual remote control of industrial robotic arms.

---

### 6. [Semiconductor Poster: CMP Endpoint Detection (EPD) Mechanisms](<semi-conducter project.pdf>)
* **Event**: Semiconductor Industry Exhibition, NCU
* **Keywords**: Chemical-Mechanical Planarization, Optical Sensing, Friction, Acoustic Emission
* **Technical Highlights**:
  * Analyzed wafer planarization mechanisms and compared Endpoint Detection (EPD) methodologies: Optical reflectance, Friction torque changes, and Acoustic Emission (AE) signal analysis.

---

##  Certificates & Credentials

* [**TOEIC Official Score Certificate**](多益.pdf)
* **Academic Exhibition Awards & Posters**: NCU AI Project Exhibition & Semiconductor Industry Poster Presentation
* [**Academic Exhibition certificate**](應材證書_潘佳成.pdf): Equipment - Advanced Technologies of Semiconductor

---
