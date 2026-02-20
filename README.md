# STM_and_Sensors

## 🎯 Objective
To build foundational knowledge on **STM microcontrollers** and essential sensors, set up **PlatformIO** for embedded development, and create a comprehensive report on **perception sensors and motors**, including their integration with **ROS**.

---

## 🛠️ Task Breakdown

### ✅ 1. Learn about STM Microcontrollers (STMs)
* **Understand Architecture:** Study what STM microcontrollers are, including ARM Cortex-M architecture and common series (e.g., STM32 F1, F4, H7).
* **Applications:** Study their applications in robotics, automation, and high-performance embedded systems.
* **Learning Material:** [STM32 blackpill](resources/stm32f411ce-3.pdf)

### ✅ 2. Install and Set Up PlatformIO on VS Code
* **Installation:** Install **Visual Studio Code (VS Code)** and the **PlatformIO IDE** extension.
* **Verification:** Verify installation by creating and running a sample STM32/Arduino project.
* **Management:** Understand how PlatformIO manages libraries, toolchains, and the `platformio.ini` configuration for STM32 development.



### ✅ 3. Research & Report: Perception Sensors and ROS Integration
Prepare a detailed report on the following sensors with a focus on how **ROS (Robot Operating System)** is utilized:

* **🔹 IMU (Inertial Measurement Unit)**
    * Role in orientation, localization, and balancing.
    * ROS packages: `imu_filter_madgwick`, `robot_localization`.
* **🔹 LiDAR (Light Detection and Ranging)**
    * Applications in SLAM, obstacle detection, and mapping.
    * ROS drivers: `rplidar_ros`, `velodyne`.
* **🔹 GPS (Global Positioning System)**
    * Role in outdoor navigation and global localization.
    * Data fusion in ROS: `nmea_navsat_driver`, `robot_localization`.
* **🔹 ZED 2i Stereo Camera (Depth Capabilities)**
    * Research the ZED SDK depth modes (Ultra, Quality, Performance).
    * Understand Neural Depth Sensing and its advantages in varied lighting.
    * ROS integration: Using `zed_wrapper` to access point clouds and depth maps.
    * ROS packages: `stereo_image_proc`, `zed_ros`.

**Key Points to Cover:**
* Overview and working principle of each sensor.
* ROS integration: packages, nodes, and message types (e.g., `sensor_msgs/LaserScan`).
* Example use cases in robotics.



### ✅ 5. Study & Document: Basic Sensors, Motors, and Drivers
* **🔹 Sensors**
    * **HC-SR04 Ultrasonic Sensor:** Distance measurement and interfacing. [HC-SR04](resources/HCSR04-datasheet-version-1.pdf)
    * **LSA08 Line Sensor Array:** Output formats and line-following logic.[LSA08](resources/LSA08-Users-Manual-Jun12.pdf)
    * **IR Sensors:** Obstacle detection and proximity sensing basics.[IR Sensors](resources/arduino-ir-infrared-obstacle-avoidance-sensor-module_(1).pdf)
    * **VL53L0X Time-of-Flight (ToF) Sensor** working principle , limitations and interfacing.[VL53L0X](resources/vl53l0x.pdf)
* **🔹 Motors and Actuators**
    * **Servo Motors:** Control signals (PWM) and applications.
    * **DC Motors:** Operation and control circuits.
    * **Brushed vs. Brushless:** Comparison of efficiency, control complexity, and pros/cons.
* **🔹 Motor Driver: MDD10A**
    * Summarize datasheet: Voltage/current ratings ($5\text{V}-30\text{V}$, $10\text{A}$ continuous).
    * Control interfaces: PWM (Speed) and DIR (Direction).[MDD10A](resources/MDD10A_User_s_Manual_(1).pdf)

---

## 📦 Deliverables
* 📄 **Detailed Report:** (PDF/Docx) covering IMU, LiDAR, Stereo Cameras (including ZED 2i), GPS, and with ROS integration and on other sensors, motors and motor drivers mentioned above.

* 📷 **Media:** Screenshots showing PlatformIO setup and a successful STM32 project build.

## 📦 Bonus Task
* 📄 **Wokwi simulation:** make an STM simulation of your choice on wokwi.(present your ideas before starting) .
* [wokwi](https://wokwi.com/)


# DEADLINE - 26/2/2026

---

