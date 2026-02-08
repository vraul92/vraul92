<div align="center">

# Rahul Vuppalapati 🧠

**Senior Data Scientist** | **Applied AI Researcher** | **GenAI & Computer Vision**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/vrc7)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/vraul92)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:vrc7.ds@gmail.com)

📍 Bengaluru, India | 8+ Years | Previously: **Apple** | **Walmart** | **IBM**

</div>

---

## 🧬 Research Focus

I build **production-grade AI systems** that solve real-world problems in defense, healthcare, and computer vision using foundation models and geometric deep learning.

```
┌─────────────────────────────────────────────────────────────┐
│  🔬 CURRENT RESEARCH AREAS                                  │
├─────────────────────────────────────────────────────────────┤
│  • 🛡️ Defense AI - Multi-view 3D reconstruction, tracking   │
│  • 🥭 AgriTech AI - Drone-based crop yield estimation       │
│  • 🏥 Medical AI - Zero-shot segmentation with SAM          │
│  • 📄 Multi-Modal RAG - Document understanding with vision  │
│  • 🎨 Generative AI - NeRF-inspired 3D reconstruction       │
│  • ⚡ Efficient ML - Edge deployment & model optimization   │
└─────────────────────────────────────────────────────────────┘
```

---

## 🚀 Featured Projects

<div align="center">

### 🛡️ CV Defense Portfolio
**Expert Computer Vision for Defense Applications**

[![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)](https://python.org)
[![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)](https://pytorch.org)
[![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white)](https://opencv.org)
[![Meta](https://img.shields.io/badge/SAM-Meta%20AI-0668E1?style=flat&logo=meta&logoColor=white)](https://segment-anything.com)

> Three production-grade CV systems: ThermalSAM (zero-shot detection), Ghost-Tracker (EKF tracking), Recon-Map (visual odometry)

**[🔗 View Project](https://github.com/vraul92/cv-defense-portfolio)**

**Key Features:**
- ✅ **ThermalSAM-Lite**: SAM-based zero-shot thermal object detection with MiDaS depth
- ✅ **Ghost-Tracker**: Extended Kalman Filter tracking with occlusion handling
- ✅ **Recon-Map**: Visual odometry for GPS-denied navigation
- ✅ **4,000+ lines** of production-grade Python
- ✅ **CPU-optimized** for edge deployment

```
Tech Stack: SAM + MiDaS + PyTorch + OpenCV + NumPy
Use Case: Defense surveillance, UAV tracking, GPS-denied navigation
```

</div>

---

<div align="center">

### 🥭 MangoYield AI
**AgriTech Drone Yield Estimation with SAM**

[![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)](https://python.org)
[![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)](https://pytorch.org)
[![Meta](https://img.shields.io/badge/SAM-Meta%20AI-0668E1?style=flat&logo=meta&logoColor=white)](https://segment-anything.com)
[![Gradio](https://img.shields.io/badge/Gradio-FF6B6B?style=flat&logo=python&logoColor=white)](https://gradio.app)

> Drone imagery → AI detection → Yield forecasting for mango farms

**[🔗 View Project](https://github.com/vraul92/neural-slam)** | **[🌐 Live Demo](https://huggingface.co/spaces/aarrvvee9/neural-slam)**

**Key Features:**
- ✅ **SAM (Segment Anything Model)** integration for fruit detection
- ✅ **3D Volume Estimation** from drone altitude and pixel analysis
- ✅ **Yield Forecasting** with confidence intervals
- ✅ **Interactive Dashboard** for farm analytics
- ✅ **Multi-variety Support** (Alphonso, Kesar, Dasheri, etc.)

```
Tech Stack: SAM + PyTorch + Plotly + Gradio + OpenCV
Use Case: AgriTech drone analytics for yield estimation
```

</div>

---

<div align="center">

### 🏥 Medical SAM-CLIP
**Zero-Shot Medical Image Segmentation**

[![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)](https://python.org)
[![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)](https://pytorch.org)
[![OpenAI](https://img.shields.io/badge/CLIP-412991?style=flat&logo=openai&logoColor=white)](https://openai.com/research/clip)
[![Meta](https://img.shields.io/badge/SAM-0668E1?style=flat&logo=meta&logoColor=white)](https://segment-anything.com)

> *"segment the left lung"* → Instant segmentation. No training required.

**[🔗 View Project](https://github.com/vraul92/medical-sam-clip)** | **[🌐 Live Demo](https://huggingface.co/spaces/aarrvvee9/medical-sam-clip)**

**Key Features:**
- ✅ Zero-shot medical image segmentation (X-ray, CT, MRI, pathology)
- ✅ SAM + CLIP fusion with attention visualization
- ✅ Interactive Gradio web interface
- ✅ Reproducible benchmarks (IoU: 0.847, Dice: 0.917)
- ✅ Interactive Plotly dashboards

```bash
pip install -r requirements.txt && python app.py
# Opens at http://localhost:7860 🌐
```

</div>

---

<div align="center">

### 📄 Multi-Modal RAG
**Documents That See - Visual + Text Understanding**

[![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)](https://python.org)
[![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)](https://pytorch.org)
[![OpenAI](https://img.shields.io/badge/CLIP-412991?style=flat&logo=openai&logoColor=white)](https://openai.com/research/clip)
[![HuggingFace](https://img.shields.io/badge/🤗%20Spaces-FFD21E?style=flat)](https://huggingface.co/spaces)

> Chat with documents containing text, charts, and images

**[🔗 View Project](https://github.com/vraul92/multimodal-rag)** | **[🌐 Live Demo](https://huggingface.co/spaces/aarrvvee9/multimodal-rag)**

**Key Features:**
- ✅ Multi-modal document understanding (text + images)
- ✅ CLIP + BGE embeddings for cross-modal retrieval
- ✅ Interactive Gradio interface
- ✅ Zero-install browser demo

</div>

---

## 🛠️ Tech Stack

### Core ML & AI
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat&logo=huggingface&logoColor=black)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)

### Foundation Models
![Meta AI](https://img.shields.io/badge/Meta%20SAM-0668E1?style=flat&logo=meta&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI%20CLIP-412991?style=flat&logo=openai&logoColor=white)
![Transformers](https://img.shields.io/badge/🤗%20Transformers-FFD21E?style=flat)
![LLaVA](https://img.shields.io/badge/LLaVA-Multimodal-FF6B6B?style=flat)

### Computer Vision & 3D
![Segment Anything](https://img.shields.io/badge/SAM-Segmentation-00D4AA?style=flat)
![NeRF](https://img.shields.io/badge/NeRF-3D%20Reconstruction-667EEA?style=flat)
![SLAM](https://img.shields.io/badge/SLAM-Localization-764BA2?style=flat)
![Kalman Filter](https://img.shields.io/badge/EKF-Tracking-FF9500?style=flat)

### Web & Deployment
![Gradio](https://img.shields.io/badge/Gradio-Web%20UI-FF6B6B?style=flat)
![Plotly](https://img.shields.io/badge/Plotly-Visualizations-3F4F75?style=flat)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![HuggingFace Spaces](https://img.shields.io/badge/🤗%20Spaces-FFD21E?style=flat)

### Cloud & MLOps
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazon-aws&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoft-azure&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat&logo=google-cloud&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)

---

## 📊 GitHub Stats

<div align="center">

[![GitHub Stats](https://github-readme-stats.vercel.app/api?username=vraul92&show_icons=true&theme=dracula&hide_border=true&count_private=true)](https://github.com/vraul92)

[![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=vraul92&layout=compact&theme=dracula&hide_border=true)](https://github.com/vraul92)

</div>

---

## 🏆 Career Highlights

| Company | Role | Impact |
|---------|------|--------|
| **Apple** | Senior Data Scientist | GenAI systems for on-device AI |
| **Walmart** | Principal Data Scientist | $50M+ revenue optimization via ML |
| **IBM** | Data Scientist | Enterprise AI solutions |

### Key Achievements
- 🎯 **$50M+** business impact across roles
- 🧬 **8+ years** in ML/CV/NLP/GenAI
- 🛡️ **Defense AI** - 3D reconstruction & tracking systems
- 🥭 **AgriTech AI** - Drone yield estimation systems
- 🏥 **Healthcare AI** - Zero-shot medical segmentation
- 📄 **Multi-modal AI** - RAG with visual understanding
- 🚀 **Production deployment** at scale

---

## 📚 Latest Research & Projects

- [🛡️ CV Defense Portfolio](https://github.com/vraul92/cv-defense-portfolio) - Defense CV: SAM 3D, EKF tracking, Visual Odometry (2025)
- [🥭 MangoYield AI](https://github.com/vraul92/neural-slam) - AgriTech drone yield estimation using SAM (2024)
- [🏥 Medical SAM-CLIP](https://github.com/vraul92/medical-sam-clip) - Zero-shot medical segmentation (2024)
- [📄 Multi-Modal RAG](https://github.com/vraul92/multimodal-rag) - Document AI with visual understanding (2024)

---

## 📖 Selected Publications & Citations

```bibtex
@software{vuppalapati2025_cv_defense,
  author = {Vuppalapati, Rahul},
  title = {CV Defense Portfolio: Expert Computer Vision for Defense Applications},
  year = {2025},
  url = {https://github.com/vraul92/cv-defense-portfolio}
}

@article{kirillov2023segment,
  title={Segment Anything},
  author={Kirillov, Alexander and Mintun, Eric and Ravi, Nikhila and Mao, Hanzi and Rolland, Chloe and Gustafson, Laura and Xiao, Tete and Whitehead, Spencer and Berg, Alexander C and Lo, Wan-Yen and others},
  journal={arXiv preprint arXiv:2304.02643},
  year={2023}
}

@article{ranftl2022towards,
  title={Towards Robust Monocular Depth Estimation: Mixing Datasets for Zero-shot Cross-dataset Transfer},
  author={Ranftl, René and Bochkovskiy, Alexey and Koltun, Vladlen},
  journal={IEEE Transactions on Pattern Analysis and Machine Intelligence},
  year={2022}
}

@article{welch1995introduction,
  title={An Introduction to the Kalman Filter},
  author={Welch, Greg and Bishop, Gary},
  year={1995}
}
```

---

## 💡 Open Source & Community

- 🔬 **HuggingFace Transformers** - Contributing multimodal capabilities
- 🛡️ **Defense AI** - Open-source CV tools for surveillance & navigation
- 🥭 **AgriTech AI** - Open-source tools for precision agriculture
- 🏥 **Medical AI** - Low-resource healthcare imaging tools
- 📊 **Reproducible ML** - Experiment tracking templates

---

## 🌱 Currently Exploring

- **Defense Foundation Models** - SAM for thermal/surveillance applications
- **Edge AI** - On-device inference for defense hardware
- **Visual Odometry** - GPS-denied navigation systems
- **3D Gaussian Splatting** - Real-time 3D reconstruction
- **Mamba & State Space Models** - Efficient sequence modeling

---

## 📫 Let's Connect

<div align="center">

I'm always interested in:
- 🤝 **Research collaborations** in Defense AI, Computer Vision, Healthcare AI
- 💼 **Senior IC roles** - Data Scientist / Applied Research / ML Engineer
- 🧪 **Open source projects** with real-world impact
- 🎯 **₹50-80 LPA (India)** | **$45+/hr (US Remote)**

**📧 vrc7.ds@gmail.com** | **[LinkedIn](https://linkedin.com/in/vrc7)**

</div>

---

<div align="center">

⭐ **If you find my work interesting, let's build something together!** ⭐

![Visitor Badge](https://visitor-badge.laobi.icu/badge?page_id=vraul92.vraul92)

</div>
