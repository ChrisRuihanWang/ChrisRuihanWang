# Hi, I'm Ruihan Wang 👋

MSc student in **Electric Power Engineering** at **KTH Royal Institute of Technology**, with a growing research focus on **robot learning, robotic manipulation, and learning-based control**.

My background is in **control theory and automation**, and I am currently building toward research in **robot learning and Vision-Language-Action (VLA) models**, with particular interest in combining modern learning-based policies with structured robotic control.

I enjoy working across the full robotics pipeline — from kinematics, control, and simulation to real-robot data collection, policy training, deployment, and evaluation.

---

## 🔬 Research Interests

- Robot Learning
- Robotic Manipulation
- Vision-Language-Action Models
- Reinforcement Learning for Robotics
- Learning-Based Control
- Embodied AI

---

## 📚 Current Learning Path

My current study path connects classical robotics and control with modern robot learning.

### Robotics & Control

- Robot kinematics and rigid-body motion
- SE(3), screw theory, Jacobians, and inverse kinematics
- Model Predictive Control (MPC)
- Optimal control and LQR
- Reinforcement Learning fundamentals

### Robot Learning

- Imitation Learning
- Action Chunking Transformer (ACT)
- Diffusion and Flow-Matching policies
- Vision-Language-Action models
- π0 / π0.5
- Reinforcement-learning post-training for robotic policies

### Learning & Implementation

- PyTorch
- Transformer architectures
- Flow Matching
- PPO / GAE / policy-gradient methods
- LeRobot
- Isaac Sim / Isaac Lab
- ROS2

My current focus is transitioning from **behavior cloning and imitation learning** toward **VLA fine-tuning and reinforcement-learning post-training**.

---

## 🚀 Selected Projects

### 🤖 SO-ARM101 ACT Generalization

A real-robot study of how an **Action Chunking Transformer (ACT)** policy generalizes under progressively expanded demonstration distributions.

**Technologies:** LeRobot · PyTorch · SO-ARM101 · OpenCV · Ubuntu

- Built a complete real-robot imitation-learning pipeline using **SO-ARM101**
- Collected demonstrations through leader-follower teleoperation
- Used dual-camera observations with top and side views
- Trained ACT policies on fixed, discrete-grid, and continuous object distributions
- Designed systematic real-robot rollout protocols for spatial generalization
- Analyzed retry behavior, distribution shift, and failure modes
- Compared policy performance before and after expanding the demonstration distribution

Key experimental results:

- **Stage 2 discrete-grid evaluation:** 39 / 45 (**86.7%**)
- **Stage 2 seen positions:** 23 / 25 (**92.0%**)
- **Stage 2 unseen positions:** 16 / 20 (**80.0%**)
- **Stage 3 continuous-pose evaluation:** 15 / 45 (**33.3%**)
- **Stage 3 stress test:** 1 / 5 (**20.0%**)
- **100-demo model on original grid:** 11 / 27 (**40.7%**)

One practical observation from the project was that:

> Increasing demonstration diversity does not automatically improve policy generalization.

🔗 **Repository:**  
https://github.com/ChrisRuihanWang/soarm101-act-generalization

---

### 🧪 Isaac Sim Teleoperation & Data Collection Pipeline

A reusable simulation pipeline for robot manipulation, keyboard teleoperation, and demonstration collection in **Isaac Sim / Isaac Lab**.

**Technologies:** Isaac Sim · Isaac Lab · Python · Franka Panda

- Built a Franka Panda manipulation environment in Isaac Sim
- Implemented robot control and keyboard teleoperation
- Integrated RGB observations and robot joint states
- Developed synchronized demonstration recording and dataset-generation workflows
- Structured the environment as a reusable foundation for imitation-learning and robot-learning experiments

The repository focuses on the infrastructure required before policy learning:

**Simulation → Teleoperation → Observation Collection → Demonstration Recording → Dataset Generation**

🔗 **Repository:**  
https://github.com/ChrisRuihanWang/isaacsim-teleop-data-pipeline

---

## 🔭 Current Work

I am currently working toward a second real-robot manipulation project based on **π0.5**.

The planned task focuses on **language-conditioned object selection and shape insertion**, where multiple objects with different colors and shapes are placed in the workspace and the robot must follow a language instruction to select the correct object and insert it into the corresponding slot.

The planned pipeline is:

**Language Instruction → Object Selection → Grasping → Slot Matching → Alignment → Insertion**

The project is intended to explore:

- π0.5 fine-tuning on SO-ARM101
- Multi-object and language-conditioned manipulation
- Continuous object-position variation
- Precision insertion
- Failure-driven data collection
- Reinforcement-learning post-training
- PPO / GRPO-style policy optimization for robotic manipulation

---

## 🛠 Tech Stack

### Robotics

- Isaac Sim / Isaac Lab
- LeRobot
- ROS2
- SO-ARM101
- Franka Panda
- Robot Kinematics
- Model Predictive Control

### Robot Learning

- Imitation Learning
- Action Chunking Transformer
- Vision-Language-Action Models
- Flow Matching
- Reinforcement Learning

### Machine Learning

- PyTorch
- Transformers
- Deep Learning
- Policy Training and Evaluation

### Programming

- Python
- Basic C / C++

### Systems

- Ubuntu 22.04
- Linux
- Conda
- CUDA

---

## 🎯 Research Direction

My longer-term goal is to pursue research in **robot learning and robotic control**, particularly in areas such as:

- Learning-based manipulation
- VLA-based robotic policies
- Reinforcement-learning post-training
- Safe and robust robot learning
- Integration of model-based control and learned policies

I am particularly interested in research problems that connect:

**Robotics & Control + Imitation / Reinforcement Learning + Vision-Language-Action Models**

---

## 📫 Contact

**Email:** ruihanw@kth.se  
**GitHub:** https://github.com/ChrisRuihanWang
