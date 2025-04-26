# Electrical and Software Engineer

#### Technical Skills: Embedded Linux, PCB Design, C, C++, Rust, Python, RTOS, Relay Protection, SQL, AWS, Snowflake, Data Engineering

## Education
- M.S, Electrical and Computer Engineering | Purdue (_May 2026_)       		
- M.S, Computer Science	| Georgia Tech (_May 2026_)	 			        		
- B.S, Electrical Engineering and Computer Science | The University of New Orleans (_May 2024_)

## Work Experience
**Engineer I - Software and Embedded @ Entergy (_January 2025 - Present_)**
- Developed a wide fleet of software for AMI Smart Meters, ranging from firmware, GPU/HPC, ML Models, and Tooling for our smart meter lab, increasing productivity by 30%+. Primarily utilizing C, C++, QT, and PyTorch
- CUDA, Computer Vision, RF Comms, firmware HALs, barcode scanner SDKs, LLM APIs

**Project Engineer - Embedded & Controls @ Petrotech (_May 2024 - January 2025_)**
- Engineered $500k+ OT projects – PLC, software, and electrical design for IoT, relay protection, SCADA
- Developed firmware (C/C++/Rust) for STM32 & RT-Linux, such as daemons, U-Boot, systemd, GPIO control, Device Tree, and Kernel Drivers. Set up high level software infra (Data Pipelines, SQL)

**Software Engineer Intern @ Entergy (_Aug 2023 - May 2024_)**
- Developed DevOps and test suite software for the Smart Grid with Jenkins, Python, C/C++
- Wrote CI/CD pipelines for Smart Meter Data System, analyzed with R and PowerBI


## Projects
### Virgo: GPU Microarchitecture SoC | _Scala, Verilog, C++, ASM_
[Project Link]([https://www.mdpi.com/1424-8220/22/8/3048](https://github.com/ucb-bar/virgo))

- Integrated dedicated matrix units at the cluster (SM)-level. Wrote C++ Kernels for DNN and Scala RTL with Chipyard

### SESC Processor Simulator: Multi-Core Cache Coherence and Branch Prediction | _Digital Design, C++_
- Studied and improved out-of-order and multi-core processor architectures using the SESC cycle-level simulator. Analyzed branch prediction mechanisms, cache hierarchy designs, and cache coherence protocols to evaluate their impacts on processor performance.
- Modified simulator source code in C++ to implement custom branch predictors, introduce the NXLRU cache replacement policy, and classify cache misses (compulsory, conflict, capacity, coherence) at a fine-grained level.
- Performed detailed experiments on pipeline depth sensitivity, cache associativity, cache latency effects, and scalability of shared-memory multi-core systems.

### Probabilistic SLAM and EKF Autonomous Navigation | _Python, AI_
- Developed a full-stack SLAM (Simultaneous Localization and Mapping) and autonomous navigation system for a drone operating in a dense, obstacle-filled environment.
- Designed and implemented an Extended Kalman Filter (EKF)-based online SLAM module to jointly estimate the drone's position and the locations of dynamic landmarks (trees) using noisy distance and bearing measurements.
- Built adaptive path-planning algorithm to navigate toward a target while dynamically avoiding obstacles, using collision prediction and local replanning heuristics.
- Integrated uncertainty handling in both measurement updates and motion predictions to maintain model robustness under sensor and actuation noise. Optimized movement commands to respect system constraints on steering and travel distance for extraction in a limited time horizon.



  
