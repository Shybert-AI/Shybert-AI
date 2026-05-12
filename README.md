[![中文](https://img.shields.io/badge/lang-中文-red.svg)](README_zh.md)

### 👋 Hi, I'm Shybert | Multimodal Algorithm Engineer

🏠 Xi'an, China | 📧 854197093@qq.com | QQ Group：1029629549

A practitioner with **6 years of algorithm development experience**, focusing on **front-end speech processing, multimodal model training, and engineering deployment**. Passionate about sharing practical insights through technical blogs, and have accumulated extensive optimization experience across multiple international AI competitions.

*   🔭 **Currently working on**: AEC (Acoustic Echo Cancellation), Diffusion model acceleration, multimodal content generation
*   🌱 **Exploring**: On-device deployment of large models, performance tuning of video generation models (e.g., Wan2.2)
*   👯 **Open to collaboration**: Speech recognition, Sound Event Detection, AI competition solution reproduction & optimization
*   📝 **Writing regularly**: 110+ original technical articles on [CSDN Blog](https://blog.csdn.net/weixin_43509698)
*   ⚡ **Recent highlights**: 📄 **arXiv Paper**: Sparse Mixture-of-Experts Routing in Visual Diffusion Transformers (2025.05) | 2025 IKCEST **Top 10**, 2025 Baidu Commercial Competition **Top 5**, 2024 IKCEST **Top 8**, GitHub Project [OpenManus-WebUI](https://github.com/Shybert-AI/OpenManus-WebUI) **226 Stars ⭐**

---

### 🏆 Competition Awards & Honors

My competition experience spans multiple cutting-edge fields such as **speech, video, and multimodal misinformation detection**. Below are some representative awards:

| Year | Competition | Topic/Direction | Ranking |
| :--- | :--- | :--- | :--- |
| 2025 | IKCEST International Big Data Competition | Photo-based Problem Solving with LLMs | Global **Top 10** |
| 2025 | Baidu Commercial AI Technology Innovation Competition | Video Ad Generation Inference Optimization (Digital Human) | National **Top 5** |
| 2024 | IKCEST International Big Data Competition | AI Sports Commentary | Global **Top 8** |
| 2024 | 2nd World Scientific Intelligence Competition | Life Science & Materials Science Tracks | 14th & 15th |
| 2023 | IKCEST International Big Data Competition | Multimodal Misinformation Detection in Social Networks | Global **Top 11** |
| 2022 | vloong Energy AI Challenge | New Energy Battery Anomaly Detection | **3rd Place** |

---

### 🚀 Core Projects & Highlights

Here are some representative projects across speech and multimodal domains, covering the full pipeline from model training to on-device deployment.

#### 📌 Multimodal Generation & Video Editing

*   **【Diagnostic Research】UniGen-MOE: Diagnosing MoE Routing Failures in Video Diffusion (2025.05)**
    A Token-Choice MoE conversion experiment based on the Wan2.2-TI2V-5B DiT backbone and Qwen2.5-VL-3B-Instruct encoder.
    Discovered two novel failure modes: **"Selective Deadlock"** and **"U-shaped Deadlock Distribution"**, proposed the **"Functional Redundancy Hypothesis"**,
    and documented the Three Laws of Dense-to-MoE conversion and a complete solution to the bfloat16 precision trap.
    The associated paper has been released on arXiv. ([GitHub Repo](https://github.com/Shybert-AI/UniGen-MOE))

*   **【Unified Framework】UniGen-LingXi: 9-in-1 Multimodal Generation & Editing (2025.04)**
    A resource-efficient, "editing-first" 9-in-1 multimodal unified framework covering core tasks such as text-to-image, text-to-video, image editing, and video editing.
    Served as the experimental base for UniGen-MOE. ([GitHub Repo](https://github.com/Shybert-AI/UniGen-LingXi))

*   **【Competition Solution】Video Ad Generation Inference Optimization (2025.09)**
    Integrated **FlashAttention, TeaCache, custom attention block computation** and other techniques to compress single-video inference from 10 minutes to 1 minute, achieving **10x speedup** while maintaining generation quality (similarity > 0.97). ([Solution Blog](https://blog.csdn.net/weixin_43509698/article/details/151196172))

*   **【Short Video Generation】OpenShortVideo: AI Short Video Intelligent Production Platform (2025.03)**
    Integrated scriptwriting, character management, scene generation, and shot production workflows to help creators rapidly generate high-quality short video content. ([GitHub Repo](https://github.com/Shybert-AI/openshortvideo)) (44 ⭐)

#### 📌 Speech Signal Processing

*   **【Acoustic Echo Cancellation】Two-Stage Acoustic Echo Cancellation System**
    Combined traditional **TDC-wRLS linear filtering** with **U-Net deep learning** to build a two-stage AEC system that effectively eliminates both linear and nonlinear echoes, significantly improving speech communication quality. ([GitHub Repo](https://github.com/Shybert-AI/AEC-Two-Stage-Based))

*   **【Speech Enhancement】DeepComplexCRN_streaming: Deep Complex Recurrent Network for Speech Enhancement**
    Supports both full-utterance and streaming inference, suitable for real-time speech processing scenarios. ([GitHub Repo](https://github.com/Shybert-AI/DeepComplexCRN_streaming))

*   **【Sound Event Detection】AudioClassificationModelZoo-Pytorch**
    Open-sourced **20+ audio classification models** based on PyTorch, with streaming test support, providing a convenient toolkit for sound event detection research. ([GitHub Repo](https://github.com/Shybert-AI/AudioClassificationModelZoo-Pytorch))

#### 📌 LLM Applications & Engineering Tools

*   **【On-Device Deployment】Edge-side-LLMChat: Local LLM Chat APK Based on MNN (2025.05)**
    An Android local LLM chat application based on the MNN inference framework, supporting model downloads, image input, and multi-model management. ([GitHub Repo](https://github.com/Shybert-AI/Edge-side-LLMChat))

*   **【Competition Solution】Intelligent Photo Problem-Solving Assistant (2025.12)**
    A multi-model intelligent learning tool supporting photo upload, multi-model problem solving, automatic failover, and providing step-by-step analysis, voice explanations, and mistake collection. Implemented as the **2025 IKCEST Top 10** solution. ([GitHub Repo](https://github.com/Shybert-AI/Photo_Problem_Solving_Service)) [Live Demo](https://app-6t56f7j46o75.appmiaoda.com)

*   **【WebUI Application】OpenManus-WebUI (2025.04)**
    Built a front-end interface using Flask to invoke OpenManus, with file preview support for generated outputs, earning **226 Stars**. ([GitHub Repo](https://github.com/Shybert-AI/OpenManus-WebUI))

*   **【Competition Solution】AI_SECS_Agent: AI Sports Commentary System (2024.12)**
    A multimodal agent system integrating **object tracking, pose recognition, OCR, goal detection**, and other models to automatically generate AI commentary from football match video URLs. ([GitHub Repo](https://github.com/Shybert-AI/2024IKCEST_AI_SECS_Agent))

*   **【Competition Solution】MMF-RIM: Multimodal Misinformation Detection Model (2023.11)**
    A **600M-parameter** multimodal fusion model combining **ERNIE, ResNet101, CLIP-ViT**, and OCR text features to detect multimodal rumors in social networks. ([GitHub Repo](https://github.com/Shybert-AI/2023IKCEST_MMF-RIM))

---

### 🛠️ Tech Stack & Expertise

**Core Speech Algorithms**
![AEC](https://img.shields.io/badge/-AEC-blue?style=flat-square)
![Voice Wakeup](https://img.shields.io/badge/-Voice%20Wakeup-blue?style=flat-square)
![SED](https://img.shields.io/badge/-Sound%20Event%20Detection-blue?style=flat-square)
![Speech Enhancement](https://img.shields.io/badge/-Speech%20Enhancement%20(Diffusion)-blue?style=flat-square)

**Multimodal & Generative Models**
![Multimodal Fusion](https://img.shields.io/badge/-Multimodal%20Fusion-purple?style=flat-square)
![Video Generation](https://img.shields.io/badge/-Video%20Gen%20(Wan%2C%20Sora)-purple?style=flat-square)
![Diffusion Models](https://img.shields.io/badge/-Diffusion%20Models-purple?style=flat-square)
![CLIP](https://img.shields.io/badge/-CLIP-purple?style=flat-square)

**Competition & Optimization**
![Inference Acceleration](https://img.shields.io/badge/-Inference%20Acceleration%20(TeaCache%2C%20FlashAttention)-orange?style=flat-square)
![Solution Reproduce](https://img.shields.io/badge/-Competition%20Solution%20Reproduce-orange?style=flat-square)

**Development & Deployment Frameworks**
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Kaldi](https://img.shields.io/badge/-Kaldi-2C3E50?style=flat-square)
![PaddlePaddle](https://img.shields.io/badge/-PaddlePaddle-0065B3?style=flat-square&logo=paddlepaddle&logoColor=white)
![C++/Shell](https://img.shields.io/badge/-C%2B%2B%20%2F%20Shell-00599C?style=flat-square&logo=c%2B%2B)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Flask](https://img.shields.io/badge/-Flask-000000?style=flat-square&logo=flask)
![Android](https://img.shields.io/badge/-Android%20(Kotlin)-3DDC84?style=flat-square&logo=android&logoColor=white)

---

### 📈 My GitHub Activity

<div align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=Shybert-AI&theme=radical" />
</div>
<div align="center">
  <a href="https://github.com/ashutosh00710/github-readme-activity-graph">
    <img src="https://github-readme-activity-graph.vercel.app/graph?username=Shybert-AI&theme=github-light" alt="GitHub Activity Graph" />
  </a>
</div>
