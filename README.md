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

My current study path connects classical robotics and control with modern robot learning:

### Robotics & Control

- Robot kinematics and rigid-body motion
- Modern Robotics: SE(3), screw theory, Jacobians, inverse kinematics
- Model Predictive Control (MPC)
- Optimal control and LQR
- Reinforcement Learning fundamentals

### Robot Learning

- Imitation Learning
- Action Chunking Transformer (ACT)
- Diffusion / Flow-Matching policies
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

### 🤖 SO-101 ACT Generalization

A real-robot study of how an **Action Chunking Transformer (ACT)** policy generalizes under progressively expanded demonstration distributions.

**Technologies:** LeRobot · PyTorch · SO-ARM101 · OpenCV · Ubuntu

- Built a complete real-robot imitation-learning pipeline using **SO-ARM101**
- Collected demonstrations through leader-follower teleoperation
- Used dual-camera observations with top and side views
- Trained ACT policies on fixed, discrete-grid, and continuous object distributions
- Designed systematic real-robot rollout protocols for spatial generalization
- Analyzed retry behavior, distribution shift, and failure modes
- Compared performance before and after expanding the demonstration distribution

[Project Repository](https://github.com/ChrisRuihanWang/so101-act-generalization)

---

### 🧪 Isaac Sim Teleoperation & Data Collection Pipeline

A reusable simulation pipeline for robot control, keyboard teleoperation, and demonstration collection in **Isaac Sim / Isaac Lab**.

**Technologies:** Isaac Sim · Isaac Lab · Python · Franka Panda

- Built a Franka Panda manipulation environment in Isaac Sim
- Implemented robot control and keyboard teleoperation
- Integrated RGB observations and robot joint states
- Developed demonstration recording and dataset-generation workflows
- Designed the environment as a reusable foundation for imitation-learning experiments

<!-- Replace with the final repository URL -->
[Project Repository](YOUR_ISAACSIM_REPOSITORY_URL)

---

## 🔭 Current Work

I am currently working on a second real-robot manipulation project based on **π0.5**.

The planned task involves **language-conditioned object selection and shape insertion**:

```text
Language instruction
        ↓
Select the correct object
        ↓
Grasp
        ↓
Identify the corresponding slot
        ↓
Align and insert
```

The project is intended to explore:

- π0.5 fine-tuning on SO-ARM101
- Multi-object and language-conditioned manipulation
- Continuous object-position variation
- Precision insertion
- Failure-driven data collection
- Reinforcement-learning post-training with PPO / GRPO-style methods

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
- Policy Training & Evaluation

### Programming

- Python
- Basic C / C++

### Systems

- Ubuntu 22.04
- Linux
- Conda
- CUDA

---
## 📫 Contact

**Email:** ruihanw@kth.se  
**GitHub:** https://github.com/ChrisRuihanWang
