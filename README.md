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

My work ranges from deploying computer-vision models on resource-constrained devices to designing RTL for a custom **RV64 AI-oriented MCU/SoC**.

---

## What I Build

| Area | Focus |
|---|---|
| **Embedded Systems** | Raspberry Pi · NXP MCX · ARM Cortex-M33 · STM32 · ESP32 · Linux |
| **Edge AI** | YOLO · ONNX · NCNN · OpenCV · TinyML · inference optimization |
| **Computer Vision** | Real-time detection · vision pipelines · spatial filtering |
| **Robotics** | Multi-sensor systems · aerial platforms · onboard processing |
| **Digital Design** | Verilog · SystemVerilog · RTL · FPGA · RISC-V |
| **Computer Architecture** | CPU pipelines · memory systems · DSP · SIMD · AI accelerators |
| **ASIC Design** | Synthesis · timing constraints · QoR analysis · Synopsys Design Compiler |

---

## Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 01 · RV64-AI-MCU

**Custom RV64 AI-oriented MCU/SoC**

A RISC-V based microcontroller architecture with integrated DSP and AI acceleration.

- 5-stage RV64IMC CPU
- SIMD + MAC DSP subsystem
- 16×16 INT8 systolic TPU
- SRAM / ROM / cache / QSPI / PSRAM
- DMA, USB, CAN FD and common MCU peripherals
- RTL → synthesis → timing flow

`RISC-V` `Verilog` `RTL` `DSP` `ASIC`

[**View repository →**](https://github.com/asronal/RV64-AI-MCU)

**Status:** Active development

</td>
<td width="50%" valign="top">

### 02 · SkyNetics RAS Drone

**Multi-sensor aerial search-and-rescue platform**

An onboard sensing and perception system designed for low-connectivity and low-visibility environments.

- Raspberry Pi 4 onboard processing
- RGB + thermal + mmWave sensing
- MLX90640 thermal array
- LD2450 radar
- YOLO-based human detection
- Sensor fusion + live telemetry

`Raspberry Pi` `STM32` `YOLO` `Robotics`

[**View repository →**](https://github.com/asronal/SkyNetics-RAS-drone)

**Status:** Active development

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 03 · Road Perception

**Obstacle & pothole detection with Edge AI**

Computer vision for detecting road obstacles and potholes on resource-constrained hardware.

- YOLO-based detection
- ONNX deployment
- OpenCV / NCNN inference
- Raspberry Pi camera pipeline
- Spatial filtering + cooldown logic
- ~5–7 FPS on Raspberry Pi 4

`YOLO` `ONNX` `NCNN` `OpenCV`

[**View repository →**](https://github.com/asronal/Obstacle-and-Pothole-detection-model)

**Status:** Working prototype

</td>
<td width="50%" valign="top">

### Engineering Direction

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
```

`Embedded` `Edge AI` `RISC-V` `RTL` `Robotics`

</td>
</tr>
</table>

---

## Engineering Stack

### Languages

![C](https://img.shields.io/badge/C-222222?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-222222?style=flat-square&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-222222?style=flat-square&logo=python&logoColor=white)
![Verilog](https://img.shields.io/badge/Verilog-222222?style=flat-square&logoColor=white)
![SystemVerilog](https://img.shields.io/badge/SystemVerilog-222222?style=flat-square&logoColor=white)

### Embedded & Hardware

![ARM](https://img.shields.io/badge/ARM-222222?style=flat-square&logo=arm&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi-222222?style=flat-square&logo=raspberrypi&logoColor=white)
![NXP](https://img.shields.io/badge/NXP%20MCX-222222?style=flat-square&logoColor=white)
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

### Tools

![Git](https://img.shields.io/badge/Git-222222?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-222222?style=flat-square&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-222222?style=flat-square&logo=visualstudiocode&logoColor=white)

---

## Current Work

<table>
<tr>
<td width="33%" valign="top">

**ARM / MCU Development**

Learning embedded development on the **NXP FRDM-MCXN236**, using the Arm Cortex-M33, MCUXpresso SDK and MCUXpresso Extension for VS Code.

</td>
<td width="33%" valign="top">

**RISC-V MCU / SoC**

CPU architecture, RTL integration, memory systems, DSP and INT8 acceleration.

</td>
<td width="33%" valign="top">

**Edge AI & Robotics**

Real-time computer vision, model optimization, onboard processing and multi-sensor perception.

</td>
</tr>
</table>

---

## GitHub

<div align="center">

[![GitHub Stats](https://github-readme-stats.vercel.app/api?username=asronal&show_icons=true&hide_border=true&include_all_commits=false&count_private=false&rank_icon=github&cache_seconds=86400)](https://github.com/asronal)

[![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=asronal&layout=compact&hide_border=true&langs_count=6&cache_seconds=86400)](https://github.com/asronal?tab=repositories)

</div>

<div align="center">

**Explore the code →** [github.com/asronal](https://github.com/asronal)

</div>

---

## Open To

- Embedded Systems internships
- Edge AI / Computer Vision internships
- RTL / FPGA / Digital Design internships
- Robotics and autonomous-systems opportunities
- Research and engineering collaborations
- Open-source hardware and software projects

---

<div align="center">

### Embedded Systems · ARM · Edge AI · RISC-V · RTL · Robotics

**From sensors to software to silicon.**

</div>
