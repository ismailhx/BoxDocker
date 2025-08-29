# BoxDocker: An Autonomous Debris Removal System

BoxDocker is an autonomous robotics spacecraft designed to combat the growing problem of space debris in Low Earth Orbit simulated in IsaacSim. 
The system is a versatile solution that uses a YOLOv11 deep learning model for real-time vision and a closed-loop control algorithm to detect and collect various space debris, as well as avoiding dangerous debris.

Technologies: YOLOv11 Computer Vision | IsaacSim | Robotics | CAD.
<img width="895" height="478" alt="image" src="https://github.com/user-attachments/assets/f19cc32b-a49a-409a-800a-a6256b330f82" />

## Project Summary
<img width="1200" height="1200" alt="image" src="https://github.com/user-attachments/assets/6cfe36ce-32c6-4aec-9564-25b84159d1a5" />



## Technical Approach
Developed within the NVIDIA Isaac Sim simulation environment, the BoxDocker is a multi-modal spacecraft with specialized capture mechanisms. These include a prismatic docker for large debris, deployable doors for mid-sized objects, and aerogel flaps for mcroscopic flecks. This simulation-first approach allowed us to rigorously test the system's ability to autonomously detect, evade, and capture a wide range of debris.

## Key Findings
Our simulation results validate the technical feasibility of the BoxDocker. The YOLOv11 model achieved over 97% detection accuracy, while the control system maintained a debris evasion rate of over 98%. The capture mechanisms also demonstrated high success rates on their respective target types. These findings confirm that a single, scalable robotic solution for space debris removal is a viable concept.
