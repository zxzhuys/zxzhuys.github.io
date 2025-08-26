---
title: "Current Control of Low Carrier Ratio Permanent Magnet Synchronous Motor Drive System"
collection: research
excerpt: "Jan. 2025 - Jun. 2025"
date: 2025-06-01
type: "Bachelor Thesis"
venue: "College of Electrical Engineering, Zhejiang University"
location: "Hangzhou, China"
---

*Bachelor thesis, Completed and was responsible for all aspects of the project*

***Keywords**: Permanent Magnet Synchronous Motor(PMSM), Vector Control, Complex Vector Decoupling, Low Carrier Ratio, Current Bandwidth.*

## Abstract
In servo systems with low-switching-frequency devices and high speeds, PMSMs operating under low carrier ratios often face challenges such as degraded dynamic performance and severe current coupling. Therefore, research on current decoupling and bandwidth extension for PMSMs holds significant theoretical and practical significance.

1. To achieve bandwidth expansion of the current loop, this study investigated common PWM sampling and update strategies. Theoretical analysis, comparative studies, simulations, and experimental validations were conducted for both single-sample single-update and double-sample double-update methods. Results demonstrated that the double-sample double-update strategy effectively reduced current loop delay and enhanced bandwidth.  

2. To realize dynamic decoupling of dq-axis currents, this study derived a complex vector decoupling method based on complex vector theory. Through theoretical analysis, comparative studies, simulations, and experiments, this approach was compared with traditional feedforward decoupling methods. The results validated that complex vector decoupling achieved dynamic decoupling of dq-axis currents while maintaining steady-state performance.

3. To validate the proposed control strategy, this study modeled sensor signal transformation delays and commercial inverter (e.g., Siemens S120 series) current sampling methods in a high-fidelity Simulink simulation to ensure results accurately matched real-world control performance, and constructed a real-time motor control platform based on TMS320F28379D DSP. [[model](https://github.com/zxzhuys/PMSM-Current-Decoupling)]

## Publication
[1] ZHU Zixuan. Current Control of Low Carrier Ratio Permanent Magnet Synchronous Motors[D]. Zhejiang University, 2025.

[2] A Method for Optimized Current Control of Permanent Magnet Synchronous Motors Based on MCU. *(Patent Under Review)*

### Control Performance of Complex Vector Decoupling & Double-sample/Double-update Strategy 
<img src='/images/CV-dq-current.png'>

---

*The project was developed based on MATLAB/Simulink.*

*For more information, please visit my GitHub*

