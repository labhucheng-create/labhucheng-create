<p align="center">
  <img src="./assets/hero.svg" alt="Li Hucheng profile hero" width="100%" />
</p>

<h1 align="center">Li Hucheng</h1>
<p align="center"><strong>Systems / CUDA / Speech AI</strong></p>
<p align="center">
  Low-level systems engineer focused on Linux drivers, CUDA-like runtime infrastructure, PCIe/DMA data paths, and speech-centric AI research.
</p>
<p align="center">
  我主要做芯片底层软件与 AI 系统相关工作，关注 Linux 驱动、CUDA Runtime、算子优化、PCIe/DMA 数据链路，以及语音大模型研究。
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Linux%20Drivers-20242E?style=for-the-badge&logo=linux&logoColor=white" alt="Linux Drivers" />
  <img src="https://img.shields.io/badge/CUDA%20Runtime-1E5974?style=for-the-badge&logo=nvidia&logoColor=white" alt="CUDA Runtime" />
  <img src="https://img.shields.io/badge/PCIe%20%2F%20DMA-6F5340?style=for-the-badge&logoColor=white" alt="PCIe DMA" />
  <img src="https://img.shields.io/badge/Operator%20Optimization-57595D?style=for-the-badge&logoColor=white" alt="Operator Optimization" />
  <img src="https://img.shields.io/badge/Speech%20AI-6B72DB?style=for-the-badge&logoColor=white" alt="Speech AI" />
</p>

## Snapshot

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>Education</h3>
      <p><strong>Hunan University</strong><br/>AI Graduate Study, 2025-present</p>
      <p><strong>Changsha University</strong><br/>B.Eng. in Communication Engineering, 2016-2020</p>
    </td>
    <td width="50%" valign="top">
      <h3>Current Focus</h3>
      <p>Building driver/runtime infrastructure that makes domestic compute platforms easier to program and validate.</p>
      <p>Researching speech-centric large models, evaluation benchmarks, and bias analysis.</p>
    </td>
  </tr>
</table>

## Selected Work

### CUDA-like Runtime, Driver, and PCIe Host SDK
**Suzhou Ruixin Integrated Circuit Co., Ltd.**  
Worked on a Tianmai 3 compute stack in a domestic OS + self-developed RISC-V accelerator environment.

- Developed `ioctl`-based control paths between user space and devices.
- Participated in CUDA-like device driver architecture for device management and resource access.
- Implemented runtime-side library functions and event mechanisms for foundational compute APIs.
- Helped build the PCIe Host SDK path between Host and EP, including DMA data transfer links.
- Delivered 4 core modules that formed an initial runtime programming framework and reduced later algorithm migration cost.

### VPU Validation and Performance Optimization
**Suzhou Ruixin Integrated Circuit Co., Ltd.**

- Covered end-to-end encode/decode validation across GOP combinations, high resolutions, and multi-instance scenarios.
- Built performance baselines and regression data generation for multi-resolution and multi-format workloads.
- Diagnosed issues such as sequence init interrupts, firmware loading failures, second-frame encode failures, and multi-instance stalls.
- Improved VPU decode throughput from **1200 fps** to **2300 fps**.
- Improved single-stream **8K encode** throughput from **15 fps** to **30 fps**.

### Embedded BSP and Driver Development
**Changsha Jingjia Microelectronics Co., Ltd.**

- Developed or ported low-level modules including SPI Flash, NAND Flash, PCIe, RS232/RS422, GPIO, ADC, I2C, and EEPROM drivers.
- Ported the YAFFS file system on bare-metal boards and adapted PMON boot flow on the Loongson platform.
- Supported CPU + FPGA + GPU heterogeneous graphics/display processing boards with external communication and video pipelines.
- Implemented NTB-mode communication to connect PCIe RC-to-RC links.

## Research

### AudioBias-Bench for Speech-Centric Large Models

- Participated in building **AudioBias-Bench** and the **ECHO 22K** dataset for social bias evaluation in speech-centric large models.
- Designed tasks spanning both speech recognition and speech generation bias evaluation.
- Evaluated 15 mainstream speech-centric large models and analyzed age-related recognition/generation bias.
- Explored Chain-of-Thought style debiasing methods and their performance tradeoffs.

### Applied AI and Operator Optimization

- Built a U-Net based medical image workflow for tumor detection and segmentation using OpenCV and PyTorch.
- Optimized LayerNorm-style operators under a SIMT programming model, focusing on compute/communication overlap and parallel partitioning.

## Skills

```text
C / C++ / Linux Driver Development / IOCTL / PCIe / DMA
CUDA Runtime / Compute APIs / Operator Optimization / SIMT / SIMD
Embedded BSP / Validation / Performance Tuning / Speech AI Research
PyTorch / OpenCV / Benchmark Design / Large Model Evaluation
```

## Contact

- Email: [lihucheng0330@163.com](mailto:lihucheng0330@163.com)
- Location: Changsha, Hunan, China

<p align="center">
  <sub>Focused on serious systems work, while keeping one foot in CUDA infrastructure and one in speech AI research.</sub>
</p>
