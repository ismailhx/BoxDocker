# BoxDocker: An Autonomous Debris Removal System

<img width="895" height="478" alt="image" src="https://github.com/user-attachments/assets/f19cc32b-a49a-409a-800a-a6256b330f82" />

## Project Summary
BoxDocker is an autonomous robotics spacecraft designed to combat the growing problem of space debris in Low Earth Orbit simulated in IsaacSim. 
The system is a versatile solution that uses a YOLOv11 deep learning model for real-time vision and a closed-loop control algorithm to detect and collect various space debris, as well as avoiding dangerous debris.

## Space Debris
Space debris is one of the fastest-growing threats to space operations, with over **36,000 tracked objects larger than 10 cm** and **hundreds of millions of smaller fragments** orbiting Earth at high velocities. Even a fleck of paint can cause severe damage to satellites or spacecraft due to the extreme kinetic energy involved. This accumulation of debris not only endangers current missions but also risks triggering the **Kessler Syndrome** — a cascade of collisions that could make Low Earth orbit increasingly hazardous. Addressing this problem requires innovative autonomous systems in space capable of detecting, avoiding, and removing debris of all sizes.

## Technical Approach
### Technologies: YOLOv11 Computer Vision | IsaacSim | Robotics | CAD.
Developed within the NVIDIA Isaac Sim simulation environment, the BoxDocker spacecraft is an example of such a system, specialized with multi-modal capture mechanisms. These include a prismatic docker for small debris (1-10cm), deployable doors for mid-sized objects (10cm+), and aerogel flaps for mcroscopic flecks (under 1cm). Currently there is no existing solution that tackles all these debris sizes making this system unique. This simulation-first approach allowed the rigorous testing of the system's ability to autonomously detect, evade, and capture a wide range of debris.

<img width="772" height="267" alt="Screenshot 2025-08-29 211126" src="https://github.com/user-attachments/assets/3f2d5d5f-e697-41df-9923-4eef08d7a7a3" />
<img width="639" height="179" alt="Screenshot 2025-08-29 211147" src="https://github.com/user-attachments/assets/ec566dd2-cc8d-44f0-891e-008f9c2ada1b" />
<img width="417" height="173" alt="Screenshot 2025-08-29 211201" src="https://github.com/user-attachments/assets/017e958a-ce30-428a-a6eb-80933bde9d73" />


## Key Findings
Our simulation results validate the technical feasibility of the BoxDocker. The YOLOv11 model achieved over 97% detection accuracy, while the control system maintained a debris evasion rate of over 98%. The capture mechanisms also demonstrated high success rates on their respective target types. These findings confirm that a single, scalable robotic solution for space debris removal is a viable concept.

<img width="591" height="391" alt="Screenshot 2025-07-24 064843" src="https://github.com/user-attachments/assets/635a3d78-280e-450e-aca4-4d3b00eb6ffc" />
 <img width="534" height="410" alt="Screenshot 2025-08-19 143136" src="https://github.com/user-attachments/assets/fbd5abf7-3a55-4df0-afb2-fdcdf4c49557" />

## BoxDocker in Action
[https://www.youtube.com/watch?v=KIuLJWdtXso](https://www.youtube.com/watch?v=vqeBIw3_blg)

## Code
Due to working in partnership with Kings College I am not at liberty to share the source code.
