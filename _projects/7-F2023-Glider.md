---
layout: project
title: Fixed-Wing Glider Optimization and Aerodynamic Modeling
description: Designed and tested a scaled glider system for two vastly different planetary environments, optimizing for maximum flight time and aerodynamic stability through dimensional analysis and iterative testing.
technologies: [Aerodynamic Modeling, Dimensional Analysis, Reynolds and Mach Scaling, XFLR5 Simulation, Experimental Flight Testing, Technical Reporting, CAD Design, Physics-Based Prototyping]
image: /assets/images/Plane.png
---

As part of Cornell’s MAE 3050 course, I worked with a team to design a glider that would maximize flight time across a 15-meter span under fictional planetary conditions. The challenge involved developing two versions of the same glider: the Earth Glider (EG), which was built and tested in a controlled environment, and the Tarrytown Glider (TG), a theoretical design scaled to operate under altered atmospheric parameters. Our objective was to create a design that would fly as slowly and stably as possible to maximize onboard instrumentation time. We selected a Clark Y airfoil and optimized the glider’s geometry to maintain low stall speeds, consistent lift, and stable center of gravity placement, ultimately achieving a successful 16-meter flight on Earth.

To model the TG, we applied dimensional analysis to maintain similarity in Reynolds and Mach numbers, scaling the EG down by a factor of 336. Using XFLR5, we simulated the aerodynamic forces acting on both models, validating assumptions for lift and drag coefficients. Although the scaled-down TG was too small to fabricate with real materials, the analysis revealed challenges in extreme miniaturization, prompting future recommendations to reverse the scaling process—designing for Tarrytown first, then scaling up. The project offered hands-on insight into aerodynamic scaling, glider stability, and the limits of physical prototyping under abstract constraints.

![Lift, Drag, and Moment Graphs of Final Plane Design over Various Reynold's Numbers]({{ "/assets/images/Cl-Cd.png" | relative_url }}){: .inline-image-l}