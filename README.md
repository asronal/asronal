<div align="center">

# ASRON A.L.

### Electronics & Communication Engineering · Embedded Systems · Edge AI · Computer Architecture

**Building systems from sensor → software → silicon.**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/asronal)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/asronal)

</div>

---

## About

I am an ECE student focused on building **hardware-integrated, compute-efficient systems** across embedded systems, edge AI, robotics, digital design, and computer architecture.

My work spans deploying computer-vision models on resource-constrained devices, building embedded Linux systems with Buildroot, and designing RTL for custom **RISC-V AI-oriented MCUs/SoCs**.

---

## What I Build

| Area | Focus |
|---|---|
| **Embedded Systems** | Raspberry Pi · NXP MCX · ARM Cortex-M33 · STM32 · ESP32 · Linux |
| **Embedded Linux** | Buildroot · custom root filesystems · networking · SSH · Wayland/Weston · system utilities |
| **Edge AI** | YOLO · ONNX · NCNN · OpenCV · TinyML · inference optimization |
| **Computer Vision** | Real-time detection · camera pipelines · spatial filtering · sensor fusion |
| **Robotics** | Multi-sensor systems · aerial platforms · onboard processing |
| **Digital Design** | Verilog · RTL · FPGA · RISC-V |
| **Computer Architecture** | CPU pipelines · memory systems · DSP · SIMD · AI accelerators |
| **ASIC Design** | Synthesis · timing constraints · QoR analysis · Synopsys Design Compiler |

---

## Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 01 · RV64-AI-MCU

**Custom RV64 AI-oriented MCU/SoC**

A modular RISC-V SoC combining a processor core, memory hierarchy, DSP engines, INT8 tensor acceleration, peripherals, security, debug and ASIC synthesis support.

- RV64IMC 5-stage pipeline
- 128-bit SIMD + MAC DSP subsystem
- 16×16 INT8 systolic TPU
- Tensor SRAM + tensor DMA
- Boot ROM, SRAM, I/D caches, QSPI Flash and PSRAM
- GPIO, UART, SPI, I²C, PWM, ADC, USB and CAN FD
- Security, crypto, debug, trace and performance blocks
- RTL, verification and Synopsys Design Compiler handoff flow

`RISC-V` `Verilog` `RTL` `DSP` `AI Acceleration` `ASIC`

[**View repository →**](https://github.com/asronal/RV64-AI-MCU)

**Status:** Active development

</td>
<td width="50%" valign="top">

### 02 · SkyNetics RAS Drone

**Multi-sensor aerial search-and-rescue platform**

An onboard perception system for detecting humans in avalanche and landslide environments using RGB vision, thermal sensing and mmWave radar.

- Raspberry Pi 4 onboard processing
- Pi Camera Module 3
- MLX90640 thermal array
- LD2450 mmWave radar
- YOLOv8 ONNX human detection
- SORT tracking and sensor fusion
- Live OSD with bounding boxes, thermal and radar views
- BotWing F722 flight-controller telemetry
- Offline operation and analog video output

`Raspberry Pi` `STM32` `YOLO` `ONNX` `Robotics` `Sensor Fusion`

[**View repository →**](https://github.com/asronal/SkyNetics-RAS-drone)

**Status:** Active development

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 03 · Astro OS

**Custom embedded Linux distribution for Raspberry Pi 4**

An experimental AArch64 Linux distribution built from scratch with Buildroot, focused on understanding the complete embedded Linux system stack.

- Raspberry Pi 4 AArch64 target
- Linux 6.12.x + BusyBox
- Custom ext4 root filesystem
- Ethernet + DHCP + Wi-Fi
- OpenSSH server/client
- Mesa3D + Wayland + Weston
- Custom `/etc/os-release` and userspace configuration
- Dedicated non-root `astro` user
- Custom `astro-info` system utility
- Custom login environment and MOTD

`Buildroot` `Linux` `AArch64` `Raspberry Pi` `Embedded Linux`

[**View repository →**](https://github.com/asronal/Astro_OS)

**Status:** v0.7.0 · Physical hardware validation pending

</td>
<td width="50%" valign="top">

### 04 · Road Perception

**Obstacle & pothole detection with Edge AI**

Computer vision for detecting road obstacles and potholes on resource-constrained hardware.

- YOLO-based detection
- ONNX deployment
- OpenCV / NCNN inference
- Raspberry Pi camera pipeline
- Spatial filtering + cooldown logic
- Resource-constrained edge inference

`YOLO` `ONNX` `NCNN` `OpenCV` `Edge AI`

[**View repository →**](https://github.com/asronal/Obstacle-and-Pothole-detection-model)

**Status:** Working prototype

</td>
</tr>
</table>

---

## Engineering Direction

**Hardware × Software × AI**

I am particularly interested in systems where the algorithm and hardware are designed together rather than optimized independently.

```text
Sensors
   ↓
Embedded Compute
   ↓
Edge AI / DSP
   ↓
Decision & Control
   ↓
Hardware Acceleration
   ↓
Custom Silicon
```

`Embedded` `Embedded Linux` `Edge AI` `RISC-V` `RTL` `Robotics`

---

## Engineering Stack

### Languages

![C](https://img.shields.io/badge/C-222222?style=flat-square&logo=c&logoColor=white)
![Python](https://img.shields.io/badge/Python-222222?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-222222?style=flat-square&logo=openjdk&logoColor=white)
![Verilog](https://img.shields.io/badge/Verilog-222222?style=flat-square&logo=verilog&logoColor=white)

### Embedded & Hardware

![ARM](https://img.shields.io/badge/ARM-222222?style=flat-square&logo=arm&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi-222222?style=flat-square&logo=raspberrypi&logoColor=white)
![NXP MCX](https://img.shields.io/badge/NXP%20MCX-222222?style=flat-square&logoColor=white)
![STM32](https://img.shields.io/badge/STM32-222222?style=flat-square&logo=stmicroelectronics&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-222222?style=flat-square&logo=espressif&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-222222?style=flat-square&logo=linux&logoColor=white)

**Current ARM learning:** NXP **FRDM-MCXN236** · Arm **Cortex-M33** · MCUXpresso SDK · MCUXpresso Extension for VS Code · peripheral and bare-metal development

### AI & Computer Vision

![PyTorch](https://img.shields.io/badge/PyTorch-222222?style=flat-square&logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-222222?style=flat-square&logo=opencv&logoColor=white)
![ONNX](https://img.shields.io/badge/ONNX-222222?style=flat-square&logo=onnx&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-222222?style=flat-square&logo=tensorflow&logoColor=white)

**Focus:** YOLO · ONNX/NCNN deployment · model optimization · real-time inference · sensor fusion · TinyML

### Digital Design & Architecture

`RISC-V` `RTL Design` `5-Stage Pipelines` `DSP` `SIMD` `MAC` `INT8 AI Acceleration` `Memory Systems` `ASIC Synthesis`

### Embedded Linux

`Buildroot` `Linux Kernel` `BusyBox` `AArch64` `Networking` `SSH` `Wayland` `Weston` `DRM/KMS`

### Tools

![Git](https://img.shields.io/badge/Git-222222?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-222222?style=flat-square&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-222222?style=flat-square&logo=visualstudiocode&logoColor=white)

---

## Current Work

<table>
<tr>
<td width="25%" valign="top">

**ARM / MCU**

Bare-metal embedded development on the **NXP FRDM-MCXN236**, using Cortex-M33 and the MCUXpresso SDK.

</td>
<td width="25%" valign="top">

**RISC-V SoC**

CPU architecture, RTL integration, memory systems, DSP, AI acceleration and synthesis.

</td>
<td width="25%" valign="top">

**Embedded Linux**

Buildroot-based Linux systems for Raspberry Pi, including networking, SSH, graphics and custom userspace.

</td>
<td width="25%" valign="top">

**Edge AI / Robotics**

Real-time computer vision, model optimization, onboard processing and multi-sensor perception.

</td>
</tr>
</table>

---

## GitHub

<div align="center">

### Selected Repositories

| Project | Focus | Status |
|:---|:---|:---:|
| **[RV64-AI-MCU](https://github.com/asronal/RV64-AI-MCU)** | RISC-V · RTL · DSP · AI acceleration | `ACTIVE` |
| **[SkyNetics RAS Drone](https://github.com/asronal/SkyNetics-RAS-drone)** | Embedded · Robotics · Sensor fusion | `ACTIVE` |
| **[Astro OS](https://github.com/asronal/Astro_OS)** | Buildroot · Embedded Linux · Raspberry Pi 4 | `v0.7.0` |
| **[Obstacle & Pothole Detection](https://github.com/asronal/Obstacle-and-Pothole-detection-model)** | YOLO · Edge AI · Computer Vision | `PROTOTYPE` |

[![GitHub](https://img.shields.io/badge/Explore%20all%20repositories-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/asronal?tab=repositories)

</div>

---

## Open To

- Embedded Systems internships
- Edge AI / Computer Vision internships
- RTL / FPGA / Digital Design internships
- Embedded Linux development
- Robotics and autonomous-systems opportunities
- Research and engineering collaborations
- Open-source hardware and software projects

---

<div align="center">

### Embedded Systems · ARM · Embedded Linux · Edge AI · RISC-V · RTL · Robotics

**From sensors to software to silicon.**

</div>
