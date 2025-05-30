---
title: "Low-Carrier-Ratio Current Control Strategy for Permanent Magnet Synchronous Motors"
excerpt: "Bachelor Thesis<br/>Jan. 2025 - May 2025"
date: 2025-05-23
collection: research
---

*The project was developed based on MATLAB/Simulink.*

<a href="https://github.com/zxzhuys/PMSM-Current-Decoupling" target="_blank" rel="noopener noreferrer" style="font-size:22px;">Simulink Models in GitHub</a>

***Keywords**: Permanent Magnet Synchronous Motor, FOC, Current Control, Complex Vector Decoupling, Low Carrier Ratio, Current Bandwidth.*

## Abstract
In servo systems with low-switching-frequency devices and high speeds, PMSMs operating under low carrier ratio often face challenges such as degraded dynamic performance and severe current coupling. Therefore, research on current decoupling and bandwidth extension for PMSMs holds significant theoretical and practical significance.

The results of the research mainly include:  

1. To achieve bandwidth expansion of the current loop, this study investigated common PWM sampling and update strategies. Theoretical analysis, comparative studies, simulations, and experimental validations were conducted for both single-sample single-update and double-sample double-update methods. Results demonstrated that the double-sample double-update strategy effectively reduced current loop delay and enhanced bandwidth.  

2. To realize dynamic decoupling of dq-axis currents, this study derived a complex vector decoupling method based on complex vector theory. Through theoretical analysis, simulations, and experiments, this approach was compared with traditional feedforward decoupling methods. The results validated that complex vector decoupling achieved dynamic decoupling of dq-axis currents while maintaining steady-state performance.

## Patent 
*Under Review*
* "A Method for Optimized Current Control of Permanent Magnet Synchronous Motors Based on MCU"

### Complex Vector Decoupling & Double-sample Double-update Strategy Performance

<img src='/images/CV-dq-current.png'>
