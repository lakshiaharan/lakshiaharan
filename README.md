# Hi, I'm Lakshiaharan 👋

**Robotics & Systems Engineering • Signal Processing & ML • Cloud Architecture**  
*Undergraduate Engineer (B.Tech) building high-performance simulations, deep learning audio pipelines, and cloud-native backends.*

[![GitHub](https://img.shields.io/badge/GitHub-lakshiaharan-181717?style=flat-square&logo=github)](https://github.com/lakshiaharan)
[![Live Demos](https://img.shields.io/badge/Live_Deployments-Active-2ea44f?style=flat-square)](#-featured-systems--codebases)
[![Vitest Passing](https://img.shields.io/badge/Automated_Tests-Passing-blue?style=flat-square)](#-featured-systems--codebases)

---

### 🔬 Core Technical Dimensions

```text
┌──────────────────────────────────────────────────────────────────────────────────┐
│                               TECHNICAL SPECTRUM                                 │
├──────────────────────┬──────────────────────┬────────────────────────────────────┤
│  Robotics & Systems  │  Signal Processing   │     Cloud & Distributed Systems    │
│  Differential Drive  │  Multi-Scale STFT    │     AWS Multi-Tier Architecture    │
│  LiDAR Raycasting    │  Coordinate Attn     │     DynamoDB + SNS Event Bus       │
│  Path Planning (A*)  │  5-Fold CV (ESC-50)  │     CloudWatch Telemetry & S3      │
└──────────────────────┴──────────────────────┴────────────────────────────────────┘
```

| Focus Area | Core Stack | Defensible Evidence in Repositories |
| :--- | :--- | :--- |
| **Robotics, Kinematics & DSA** | TypeScript, React 19, WebSockets, Vitest | Differential unicycle kinematics, analytical 360° LiDAR, $A^*$, Dijkstra, RRT, Boids swarm (25/25 unit tests) |
| **Signal Processing & Deep Learning** | Python, PyTorch, Librosa, NumPy | Multi-resolution STFTs, spectral delta velocity ($\Delta, \Delta^2$), Coordinate Attention on ESC-50 (76.8% 5-Fold CV) |
| **Cloud & Backend Systems** | Node.js, Express, AWS (EC2, DynamoDB, SNS, CloudWatch, S3) | Decoupled multi-tier ordering platform, IAM instance profile security, automated CloudWatch metric stream |
| **AI Systems Engineering** | TypeScript, Vector Search, LLM Tooling | Multi-agent conversational triage, GIS routing, Gale-Shapley matching, deterministic audit pipelines |

---

### 🚀 Featured Systems & Codebases

#### 1. [AegisKinetic Studio](https://github.com/lakshiaharan/aegis-kinetic-studio)
> **Interactive autonomous robotics simulation and real-time mission-control platform**  
> `React 19` `TypeScript` `Node.js` `WebSockets` `Tailwind CSS` `Vitest`
- **Simulation Engine**: 50 Hz telemetry stream over WebSockets with analytical 2D LiDAR raycasting & differential-drive unicycle kinematics.
- **Empirical Pathfinding Benchmarks**: $A^*$ (0.62–0.94 ms), Dijkstra (2.01–3.77 ms), Greedy BFS (0.12–0.27 ms), and RRT trajectory sampling.
- **Verification**: 25/25 automated unit and physics integration tests passing in Vitest.
- 🔗 **[Live Demo](https://aegis-kinetic-studio.vercel.app)** • **[Source Code](https://github.com/lakshiaharan/aegis-kinetic-studio)**

#### 2. [ESC-50 Audio Classification](https://github.com/lakshiaharan/audio-classification-esc50)
> **Deep learning & signal processing framework for environmental sound classification**  
> `Python` `PyTorch` `Librosa` `Spectrogram Analysis` `Coordinate Attention`
- **Signal Engineering**: Multi-resolution STFTs combined with differential spectral velocities ($\Delta, \Delta^2$) capturing acoustic transients.
- **Architecture**: Coordinate Attention CNN backbone evaluated on ESC-50 (2,000 clips across 50 categories).
- **Rigorous Evaluation**: 5-fold cross-validation with leak-free split methodology (76.80% ± 1.45% CV accuracy, 77.25% Fold 5).
- 🔗 **[Web Demo](https://audio-classification-esc50.vercel.app)** • **[Source Code](https://github.com/lakshiaharan/audio-classification-esc50)**

#### 3. [Spice Route Restaurant Platform](https://github.com/lakshiaharan/spice-route-restaurant)
> **Decoupled multi-tier cloud application built on AWS services**  
> `AWS (EC2, DynamoDB, SNS, S3, CloudWatch)` `TypeScript` `Express` `PM2`
- **AWS Infrastructure**: REST API on EC2 Ubuntu Linux, DynamoDB On-Demand tables, Amazon SNS asynchronous pub/sub event fanout.
- **SRE & Security**: Automated CloudWatch telemetry and CPU alarm thresholds; IAM Instance Profiles with zero hardcoded credentials.
- 🔗 **[Live Web App](https://spice-route-restaurant-flame.vercel.app/)** • **[S3 Static Site](http://spice-route-restaurant-lakshi-2026.s3-website.ap-south-1.amazonaws.com/)** • **[Source Code](https://github.com/lakshiaharan/spice-route-restaurant)**

#### 4. [SynapseAid](https://github.com/lakshiaharan/synapse-aid)
> **Multi-agent AI emergency triage simulation & deterministic routing architecture**  
> `TypeScript` `React` `Node.js` `Spatial GIS` `Gale-Shapley Matcher`
- **System Design**: Dual-stream conversational triage integrating speech synthesis, retrieval, and GIS vector distance matching.
- **Implementation Scope**: Full separation between custom deterministic business logic (Gale-Shapley matching, SHA-256 audit ledger) and simulated dispatch layers.
- 🔗 **[Live Demo](https://synapse-aid.vercel.app)** • **[Source Code](https://github.com/lakshiaharan/synapse-aid)**

---

### 🛠️ Technical Toolkit

- **Languages**: TypeScript, JavaScript, Python, C/C++, SQL, HTML5/CSS3
- **Frameworks & Libraries**: React 19, Node.js, Express, PyTorch, Librosa, Vitest, Tailwind CSS
- **Cloud & DevOps**: AWS (EC2, DynamoDB, SNS, CloudWatch, S3), Vercel, Docker, Git, Linux / Bash
- **Core Engineering**: Autonomous Kinematics, Pathfinding ($A^*$, RRT), Digital Signal Processing (STFT), Event-Driven Architecture

---
