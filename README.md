# Hi, I'm Lakshiaharan 👋

Undergraduate engineer focused on **autonomous systems simulation**, **audio deep learning & digital signal processing**, and **cloud-native backend architectures**.

[![GitHub](https://img.shields.io/badge/GitHub-lakshiaharan-181717?style=flat-square&logo=github)](https://github.com/lakshiaharan)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin)](https://linkedin.com)
[![Live Demos](https://img.shields.io/badge/Live_Deployments-Active-2ea44f?style=flat-square)](#-featured-projects)

---

### 🚀 Featured Projects

#### 🤖 [AegisKinetic Studio](https://github.com/lakshiaharan/aegis-kinetic-studio)
> **Interactive autonomous robotics simulation & pathfinding benchmark suite**  
> `React 19` `TypeScript` `Node.js` `WebSockets` `Tailwind CSS` `Vitest`
- **Simulation Engine**: 50 Hz telemetry stream over WebSockets with analytical 2D LiDAR raycasting & differential-drive unicycle kinematics.
- **Pathfinding Benchmarks**: $A^*$ (0.62–0.94 ms), Dijkstra (2.01–3.77 ms), Greedy BFS (0.12–0.27 ms), and continuous RRT trajectory sampling.
- **Verification**: 26/26 automated unit and physics integration tests passing with Vitest.
- 🔗 **[Live Demo](https://aegis-kinetic-studio.vercel.app)** • **[Source Code](https://github.com/lakshiaharan/aegis-kinetic-studio)**

#### 🎵 [ESC-50 Audio Classification](https://github.com/lakshiaharan/audio-classification-esc50)
> **Deep learning & signal processing framework for environmental sound classification**  
> `Python` `PyTorch` `Librosa` `Spectrogram Analysis` `Coordinate Attention`
- **Signal Engineering**: Multi-resolution STFTs combined with differential spectral velocities ($\Delta, \Delta^2$) to capture acoustic transients.
- **Model Architecture**: Coordinate Attention CNN backbone evaluated on the ESC-50 dataset (2,000 clips across 50 categories).
- **Evaluation**: 5-fold cross-validation with a strict leak-free split methodology (76.80% ± 1.45% CV accuracy).
- 🔗 **[Web Demo](https://audio-classification-esc50.vercel.app)** • **[Source Code](https://github.com/lakshiaharan/audio-classification-esc50)**

#### ☁️ [Spice Route Restaurant](https://github.com/lakshiaharan/spice-route-restaurant)
> **Decoupled multi-tier cloud prototype built on AWS services**  
> `AWS (EC2, DynamoDB, SNS, S3, CloudWatch)` `TypeScript` `Express` `PM2`
- **Cloud Architecture**: REST API on EC2 Ubuntu Linux, DynamoDB On-Demand tables, Amazon SNS asynchronous pub/sub event fanout.
- **Observability & Security**: Custom CloudWatch metric dispatcher with CPU alarms; IAM Instance Profiles with zero hardcoded credentials.
- 🔗 **[Live Web App](https://spice-route-restaurant-flame.vercel.app/)** • **[S3 Static Site](http://spice-route-restaurant-lakshi-2026.s3-website.ap-south-1.amazonaws.com/)** • **[Source Code](https://github.com/lakshiaharan/spice-route-restaurant)**

#### 🚑 [SynapseAid](https://github.com/lakshiaharan/synapse-aid)
> **Browser-based emergency response simulation with deterministic multi-agent matching & hybrid retrieval**  
> `TypeScript` `React` `Node.js` `Spatial GIS` `Gale-Shapley Matcher`
- **System Design**: Dual-stream conversational triage integrating speech synthesis, retrieval, and GIS vector distance matching.
- **Custom Algorithms**: In-browser Gale-Shapley responder matching, 24-D vector projection + BM25 rank fusion, and SHA-256 cryptographic audit ledger.
- 🔗 **[Live Demo](https://synapse-aid.vercel.app)** • **[Source Code](https://github.com/lakshiaharan/synapse-aid)**

---

### 🛠️ Technical Skills

- **Languages**: TypeScript, JavaScript, Python, C/C++, SQL, HTML5/CSS3
- **Frameworks & Libraries**: React 19, Node.js, Express, PyTorch, Librosa, Vitest, Tailwind CSS
- **Cloud & DevOps**: AWS (EC2, DynamoDB, SNS, CloudWatch, S3), Vercel, Docker, Git, Linux
- **Core Engineering**: Autonomous Kinematics, Path Planning ($A^*$, RRT), Digital Signal Processing (STFT), Event-Driven Architecture

---
