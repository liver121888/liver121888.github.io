---
name: Dynability5
tools: [EMG signal processing, Manipulator, ML]
image: ../img/projects/Dyna.png
# external_url: https://github.com/liver121888/NTUME-2021-MMC-FinalProject
description: Using an SVM classifier that recognizes filter-conditioned EMG pattern to control a 5 DoF manipulator.
---
# _Dynability5_
<iframe width="560" height="315" src="https://www.youtube.com/embed/r5DFUHN26QI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

[Code](https://github.com/liver121888/NTUME-2021-MMC-FinalProject)

In this project, my teammates and I integrated an EMG signal processing circuit (including IA, HF, LP, NP, Voltage compression, Voltage shift) and a 5Dof manipulator (Dynamixel AX-12A) to deliver water bottles for disabled people. We trained the SVM classifier by modifying TA's code, and eventually reached 90% of accuracy. Our classifier suffered from the ambient 60HZ noise, and thus the performance is not well. Future improvements would try to solve the noise issue.

[TA's original code](https://github.com/visionbike/Digital-Bio-Signal-Analysis)