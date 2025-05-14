---
layout: project
title: NASA ChipSats Design Optimization
description: Developed a multidisciplinary optimization framework combining genetic algorithms, gradient-based methods, Monte Carlo simulation, and Poisson modeling to maximize lunar-impact ChipSat survivability.
technologies: [LS-DYNA, OpenMDAO, Python, ANSYS, CAD Modeling, Design of Experiments (DOE), Multidisciplinary Design Optimization (MDO), Data Visualization, Impact Simulation, Structural Analysis]
image: /assets/images/Chipsat-Stress-After-Impact.png
---

As part of a multidisciplinary team at Cornell University collaborating with NASA, I contributed to the design optimization of a lunar-impact ChipSat aimed at maximizing post-impact survivability within strict 3U CubeSat constraints. Our work focused on balancing key trade-offs between structural integrity, material selection, electronic layout, cost, and flight dynamics to create a system capable of surviving high-speed lunar impact.

Working across five integrated modules—Flight Profile, Structure, Electronics, Survivability, and Cost—we used LS-DYNA to simulate impact events and assess structural resilience. I helped implement Monte Carlo simulations alongside a Poisson-based survivability model to capture variability in design performance. Using OpenMDAO, our team coordinated multidisciplinary analyses and executed both heuristic (genetic algorithm) and gradient-based optimization methods to explore the design space.

The resulting Pareto front revealed how survivability trends with factors like mass and impact orientation, allowing us to identify design configurations that improve mission success without sacrificing feasibility. This work highlights the value of system-level modeling and optimization in designing robust, resource-constrained spacecraft for extreme environments.

![Optimal ChipSat Electronic Orientation and Component Shock Threshold ]({{ "/assets/images/ChipSat-Electronic-Opt.png" | relative_url }}){: .inline-image-l}

To determine the electronics layout, we evaluated the shock tolerance of individual components against simulated impact loads derived from our flight and structural models. Each component—such as the CC1310 processor, torque coils, and GPS module—was assigned a failure threshold in g-forces. Using outputs from our Monte Carlo and LS-DYNA simulations, we determined the maximum expected shock at various internal orientations. By integrating these values into our optimization algorithms, we identified the layout that minimized the likelihood of critical component failure. The final configuration, visualized in our component map, ensured that the shock level experienced by every part remained below its failure threshold (e.g., a system-wide shock level of 1082.4g versus a minimum component threshold of 1500g), enabling a survivable design without additional mass or shielding. This orientation strategy was critical in aligning survivability goals with CubeSat mass and volume constraints.
