# Freespace Maglev Knitting

## Overview
Everyone wants hand-knitted clothing. Few know how to knit, 
fewer have the time. This project proposes using free-space 
magnetic levitation to automate the process — not by simulating 
an industrial knitting machine, but by replicating the mechanics 
of hand knitting using two magnetically actuated needles and a 
solenoid array.

## The Problem With Existing Work
Existing magnetically driven knitting systems are essentially 
industrial machines with magnetic upgrades. The needles sit in 
mechanical slots. Magnetics only control vertical movement. 
The architecture is complex, the needle count is high, and 
none of it resembles how a human actually knits.

## What This Project Does Differently
- Two needles. Like hand knitting.
- Full 6-DOF free-space actuation. No mechanical guides, 
  no onboard controllers.
- A purpose-designed needle where every component has a job:
  aluminum core for eddy current torque, non-continuous 
  magnetic strip for discrete pole levitation control.
- PWM frequency as a dual-purpose variable — generates torque 
  and manages cross-interference simultaneously.
- Camera-based AI monitoring for yarn feedback. No contact 
  sensors.

## Current Status
Theoretical framework in development.
Mathematical modeling and formal derivations in progress.
No prototype exists at this stage.

## References
1. Zhang, C., Li, D., Zuo, X., & Zhou, X. (2019). Magnetic array 
   knitting needle driving system design. IOP Conference Series: 
   Materials Science and Engineering, 612(3), 032026.

2. Zuo, X., Zhang, C., Xiong, T., Yin, W., Li, M., Zhang, C., 
   Wu, X., & Zhu, L. (2021). Maglev weft knitting needle driving 
   modeling and PID controller design. The Journal of The Textile 
   Institute, 113(8), 1715–1722.

3. Xiong, T., Peng, Y., Zuo, X., Zhang, C., Zhang, C., Zhang, L., 
   & Li, H. (2023). Magnetic field analysis and optimization of 
   the gauge of hybrid maglev needles. Applied Sciences, 13(3), 1257.

4. Zhang, D., Sheng, X., Gao, P., Wang, C., & Shi, Y. (2025). 
   Structure design and control of magnetic levitated needle driving 
   system. In Intelligent Robotics and Applications, ICIRA 2024, 
   Lecture Notes in Computer Science, vol. 15207. Springer, Singapore.
