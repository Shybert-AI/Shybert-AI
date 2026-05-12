### 👋 你好，我是Shybert | 多模态算法工程师

🏠 base 西安 | 📧 854197093@qq.com | QQ群：1029629549

一名拥有 **6年算法开发经验** 的从业者，专注于**语音前端处理、多模态模型训练与工程化部署**。热爱通过技术博客分享实战心得，并在多项国际AI赛事中积累了大量优化经验。

*   🔭 **目前深耕**：AEC回声消除、Diffusion模型加速、多模态内容生成
*   🌱 **正在探索**：大模型端侧部署、视频生成模型（如Wan2.2）的性能调优
*   👯 **乐于合作**：语音识别、声音事件检测、AI比赛方案复现与优化
*   📝 **坚持写作**：在 [CSDN博客](https://blog.csdn.net/weixin_43509698) 分享了 110+ 篇原创技术文章
*   ⚡ **近期高光**：📄 **arXiv论文**：Sparse Mixture-of-Experts Routing in Visual Diffusion Transformers (2025.05) | 2025 IKCEST大数据竞赛 **第10名**、2025百度商业大赛 **第5名**、2024 IKCEST大数据竞赛 **第8名**、GitHub项目 [OpenManus-WebUI](https://github.com/Shybert-AI/OpenManus-WebUI) **226 Stars ⭐**

---

### 🏆 比赛获奖与荣誉

我的竞赛经历覆盖了从**语音、视频到多模态虚假信息检测**等多个前沿领域，以下是一些代表性奖项：

| 年份 | 赛事名称 | 赛题/方向 | 获得名次 |
| :--- | :--- | :--- | :--- |
| 2025 | IKCEST国际大数据竞赛 | 结合大模型的拍照识题与解题 | 全球 **第10名** |
| 2025 | 百度商业AI技术创新大赛 | 视频广告生成推理性能优化（数字人生成） | 全国 **第5名** |
| 2024 | IKCEST国际大数据竞赛 | AI体育赛事解说 | 全球 **第8名** |
| 2024 | 第二届世界科学智能大赛 | 生命科学 & 物质科学赛道 | 第14名 & 第15名 |
| 2023 | IKCEST国际大数据竞赛 | 社交网络中多模态虚假信息甄别 | 全球 **第11名** |
| 2022 | vloong能源AI挑战赛 | 新能源电池异常检测 | **第3名** |

---

### 🚀 核心项目与亮点工作

这里是我在语音和多模态领域的一些代表性项目，涵盖了从模型训练到端侧部署的全链路实践。

#### 📌 多模态生成与视频编辑

*   **【研究诊断】UniGen-MOE：视频扩散MoE路由失效诊断 (2025.05)**
    基于 Wan2.2-TI2V-5B DiT 主干和 Qwen2.5-VL-3B-Instruct 编码器的 Token-Choice MoE 转换实验。
    发现 **"选择性锁死"** 和 **U型锁死分布** 两种新失效模式，提出 **"功能冗余假说"**，
    并记录了 Dense-to-MoE 转换三大法则和 bfloat16 精度陷阱的完整解决方案。
    相关论文已发布至 arXiv。([GitHub 项目](https://github.com/Shybert-AI/UniGen-MOE))

*   **【统一框架】UniGen-LingXi：9合1多模态生成与编辑 (2025.04)**
    资源高效、"编辑优先"的9合1多模态统一框架，涵盖文生图、文生视频、图像编辑、视频编辑等核心任务。
    为 UniGen-MOE 提供了实验基座。([GitHub 项目](https://github.com/Shybert-AI/UniGen-LingXi))

*   **【比赛方案】视频广告生成推理优化 (2025.09)**
    通过集成**FlashAttention、TeaCache、自定义注意力分块计算**等技巧，将单条视频推理时间从10分钟压缩至1分钟，实现 **10倍加速**，同时保证生成质量 (相似度 > 0.97)。([方案博客](https://blog.csdn.net/weixin_43509698/article/details/151196172))

*   **【短视频生成】OpenShortVideo：AI短视频智能制作平台 (2025.03)**
    集成剧本创作、角色管理、场景生成、镜头制作等完整工作流，帮助创作者快速生成高质量短视频内容。([GitHub 项目](https://github.com/Shybert-AI/openshortvideo)) (44 ⭐)

#### 📌 语音信号处理

*   **【回声消除】基于两阶段的声学回声消除系统**
    结合传统的 **TDC-wRLS线性滤波** 与 **U-Net深度学习**，构建两阶段回声消除系统，有效消除线性与非线性回声，显著提升语音通信质量。([GitHub 项目](https://github.com/Shybert-AI/AEC-Two-Stage-Based))

*   **【语音增强】DeepComplexCRN_streaming：深度复数循环网络语音增强**
    支持整段推理和流式推理，适用于实时语音处理场景。([GitHub 项目](https://github.com/Shybert-AI/DeepComplexCRN_streaming))

*   **【声音事件检测】AudioClassificationModelZoo-Pytorch**
    开源了基于Pytorch的 **20+种音频分类模型**，并支持流式测试，为声音事件检测研究提供便捷工具。([GitHub 项目](https://github.com/Shybert-AI/AudioClassificationModelZoo-Pytorch))

#### 📌 LLM应用与工程工具

*   **【端侧部署】Edge-side-LLMChat：基于MNN的边缘端本地大模型对话APK (2025.05)**
    基于 MNN 推理框架的 Android 端本地大模型对话应用，支持模型下载、图片输入和多模型管理。([GitHub 项目](https://github.com/Shybert-AI/Edge-side-LLMChat))

*   **【比赛方案】智能拍照解题助手 (2025.12)**
    融合多模型的智能学习工具，支持拍照上传、多模型智能解题、自动容错切换，提供步骤解析、语音讲解和错题收藏功能。作为 **2025 IKCEST 第10名**方案的实践成果。([GitHub 项目](https://github.com/Shybert-AI/Photo_Problem_Solving_Service)).体验地址：[体验地址](https://app-6t56f7j46o75.appmiaoda.com)  

*   **【WebUI应用】OpenManus-WebUI (2025.04)**
    构建了一个前端页面，通过Flask框架实现了对OpenManus的调用，并支持生成文件的预览，获得了 **226个Star**。([GitHub 项目](https://github.com/Shybert-AI/OpenManus-WebUI))

*   **【代码助手】claude-code-deepseek：双端模型驱动的可运行Claude代码源码 (2025.04)**
    采用双端模型驱动的 Claude Code 源码实现。([GitHub 项目](https://github.com/Shybert-AI/claude-code-deepseek)) (16 ⭐)

*   **【数字员工】AgentHub - OpenCode AI 数字员工管理中心 (2025.03)**
    基于 OpenCode 的 AI 数字员工管理平台。([GitHub 项目](https://github.com/Shybert-AI/agent-hub)) (7 ⭐)

*   **【比赛方案】AI_SECS_Agent：体育赛事解说系统 (2024.12)**
    一个集成了**目标追踪、姿态识别、OCR、球门识别**等多模型的多模态Agent系统，能根据足球比赛视频URL，自动生成AI解说。([GitHub 项目](https://github.com/Shybert-AI/2024IKCEST_AI_SECS_Agent))

*   **【比赛方案】MMF-RIM：多模态虚假信息甄别模型 (2023.11)**
    一个**6亿参数**的多模态融合模型，融合了**ERNIE、ResNet101、CLIP-ViT**和OCR文本特征，用于检测社交网络中的多模态谣言。([GitHub 项目](https://github.com/Shybert-AI/2023IKCEST_MMF-RIM))

---

### 🛠️ 技术栈与专长

**语音核心算法**
![AEC](https://img.shields.io/badge/-AEC%20回声消除-blue?style=flat-square)
![语音唤醒](https://img.shields.io/badge/-语音唤醒-blue?style=flat-square)
![声音事件检测](https://img.shields.io/badge/-声音事件检测(SED)-blue?style=flat-square)
![语音增强](https://img.shields.io/badge/-语音增强(Diffusion)-blue?style=flat-square)

**多模态与生成模型**
![多模态](https://img.shields.io/badge/-多模态融合-purple?style=flat-square)
![视频生成](https://img.shields.io/badge/-视频生成(Wan%2C%20Sora)-purple?style=flat-square)
![Diffusion](https://img.shields.io/badge/-Diffusion%20Models-purple?style=flat-square)
![CLIP](https://img.shields.io/badge/-CLIP-purple?style=flat-square)

**比赛与优化**
![模型加速](https://img.shields.io/badge/-推理加速(TeaCache%2C%20FlashAttention)-orange?style=flat-square)
![性能调优](https://img.shields.io/badge/-比赛方案复现-orange?style=flat-square)

**开发与部署框架**
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Kaldi](https://img.shields.io/badge/-Kaldi-2C3E50?style=flat-square)
![PaddlePaddle](https://img.shields.io/badge/-PaddlePaddle-0065B3?style=flat-square&logo=paddlepaddle&logoColor=white)
![C++/Shell](https://img.shields.io/badge/-C%2B%2B%20%2F%20Shell-00599C?style=flat-square&logo=c%2B%2B)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Flask](https://img.shields.io/badge/-Flask-000000?style=flat-square&logo=flask)
![Android](https://img.shields.io/badge/-Android(Kotlin)-3DDC84?style=flat-square&logo=android&logoColor=white)

---

### 📈 我的GitHub动态

<div align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=Shybert-AI&theme=radical" />
</div>
<div align="center">
  <a href="https://github.com/ashutosh00710/github-readme-activity-graph">
    <img src="https://github-readme-activity-graph.vercel.app/graph?username=Shybert-AI&theme=github-light" alt="GitHub Activity Graph" />
  </a>
</div>
