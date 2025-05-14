---
layout: project
title: Dynamic Wind Turbine Design & Analysis
description: Designed and tested a small-scale wind turbine blade optimized for maximum power output using airfoil analysis, blade geometry tuning, and experimental validation.
technologies: [Airfoil Analysis, MATLAB, Python, Wind Tunnel Testing, CAD (SolidWorks), Data Visualization, Blade Geometry Optimization, ANSYS]
image: /assets/images/Turbine.png
---

As part of Cornell’s MAE 4272 course, I worked on a team to design a wind turbine blade optimized for small-scale energy capture under constrained RPM and environmental conditions. We evaluated multiple airfoil profiles, ultimately selecting NACA 4412 for its high lift-to-drag ratio at low Reynolds numbers, and used Weibull-distributed wind speeds to determine the optimal blade design speed. Using MATLAB and Python, we built a custom design code that calculated ideal chord and twist distributions based on power curve predictions and interpolated design RPM.

We fabricated the blades and conducted experimental validation using wind tunnel testing. Our team collected turbine performance data across a range of wind speeds and compared experimental power output to theoretical predictions. Despite minor blade deflection at high RPM, results closely aligned with simulations, with experimental peak power reaching 2.45 W versus a 3 W theoretical maximum. The project demonstrated the importance of coupling theoretical optimization with physical testing to improve blade reliability and performance.

![CAD Renderings of Turbine Design]({{ "/assets/images/4272.png" | relative_url }}){: .inline-image-l}
