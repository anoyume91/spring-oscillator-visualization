Spring Oscillator – Hooke’s Law Visualization
Live Demo: https://anoyume91.github.io/pendulum-visual-controller/
An interactive physics-based spring–mass system demonstrating Hooke’s Law (F = –kx) with multiple analytical and artistic visualization modes.
This project explores how mathematical models can produce visual and dynamic behaviour when mapped onto real-time graphics.

Overview
This simulation models a one-dimensional spring–mass system with optional damping and an external driving force.
Several visualization modes are included to highlight different aspects of the system:
1.Wave propagation
2.Phase space portrait (position–velocity)
3.Energy landscape
4.Probability cloud inspired by harmonic oscillator behaviour

The goal is to show how physical equations translate into motion, structure, and visual patterns

Physics Model：
Hooke’s Law：
F_spring = -k * x
Damping：
F_damping = -b * v
Driving Force：
F_drive = A * cos(ωt)
Newton’s Second Law：
a = (F_spring + F_damping + F_drive) / m

Controls：
Drag the mass to set displacement
Space: switch visualization mode
D: toggle damping
F: toggle driving force
R: reset system
Mouse wheel: adjust mass
Keys 1–5: change spring constant

Technologies Used
p5.js
JavaScript
HTML/CSS
