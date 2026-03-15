# 🤖 AquaNova: Hardware-Software Integration QA
**Domain:** IoT / Robotics | Autonomous Solar-Powered Aquatic System

AquaNova is an autonomous floating robot designed for environmental waste management. As the project lead, my QA focus was centered on the critical intersection of embedded software logic and physical hardware reliability in unpredictable aquatic environments.

---

## 🛠️ My Role & Responsibilities
In this project, I acted as the primary QA Engineer, responsible for designing the testing framework that ensured the robot's survival and operational efficiency. My work covered the entire SDLC (Software Development Life Cycle) and HDLC (Hardware Development Life Cycle).

### 🔍 Key QA Areas:
* **Sensor Fusion Validation:** Verified the accuracy of Ultrasonic sensors and GPS modules to ensure precise obstacle avoidance and navigation.
* **Power Logic Testing:** Validated the firmware's ability to switch between solar charging and battery discharge states without system resets.
* **Communication Integrity:** Tested the stability of the telemetry data sent from the robot to the control interface.
* **Environmental Stress Testing:** Conducted "Water-Hardening" tests to verify the integrity of the electronics housing under real-world conditions.

---

## 🧪 Testing Methodology
To ensure a "Zero-Failure" mission profile, I implemented the following testing strategies:

1. **Unit Testing:** Individual verification of C++ motor control functions and sensor library integrations.
2. **Integration Testing:** Ensuring the Raspberry Pi (AI/Vision) and Arduino (Hardware Control) communicated correctly via Serial protocol.
3. **Field Simulation:** Conducted "Dry Runs" on land to calibrate motor torque before deployment in water.
4. **Edge Case Analysis:** Tested the system’s "Fail-Safe" mode—ensuring the robot stops all motors if a sensor disconnects or if the battery drops below 10%.

---

## 📂 Documentation Standards
The testing for this project was recorded using standardized **Proof of Testing (POT)** formats. While the raw results are proprietary, the following documentation types were produced:
* **Hardware Integration Test Plans**
* **Firmware Calibration Logs**
* **Environmental Stability Reports**

---
**Lead QA & Developer:** John Ivan P. Ello  
*Specializing in the Quality Assurance of Autonomous Systems.*
