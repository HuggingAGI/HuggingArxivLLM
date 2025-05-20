# BusterX：基于MLLM的AI视频伪造检测与解释系统

发布时间：2025年05月18日

`LLM应用` `网络信息安全`

> BusterX: MLLM-Powered AI-Generated Video Forgery Detection and Explanation

# 摘要

> 人工智能生成模型的突破推动了超级写实视频合成技术的发展，但也通过社交媒体放大了虚假信息的风险，削弱了人们对数字内容的信任。针对这一问题，已有研究探索了多种AI生成图像的深度伪造检测方法。然而，随着Sora、WanX等视频生成模型的快速发展，目前仍缺乏大规模、高质量的AI生成视频数据集用于伪造检测。此外，现有检测方法主要采用二分类思路，不仅缺乏对模型决策过程的解释性，也无法为公众提供实用的指导和见解。

为了解决这些难题，我们提出了	extbf{GenBuster-200K}——一个包含20万条高分辨率视频片段、涵盖多样最新生成技术和真实场景的大规模AI生成视频数据集。同时，我们开发了	extbf{BusterX}，一个结合多模态大型语言模型（MLLM）和强化学习的全新AI生成视频检测与解释框架，能够实现视频真实性的判定并提供清晰的推理依据。据我们所知，GenBuster-200K是首个专门针对真实场景、整合最新生成技术的大规模高质量AI生成视频数据集。而BusterX则是首个将MLLM与强化学习相结合，用于可解释AI生成视频检测的框架。

通过与现有最先进方法的广泛对比实验和消融实验，我们验证了BusterX在检测效果和适用性上的显著优势。所有代码、模型和数据集将对外开放，供研究者和开发者使用。

> Advances in AI generative models facilitate super-realistic video synthesis, amplifying misinformation risks via social media and eroding trust in digital content. Several research works have explored new deepfake detection methods on AI-generated images to alleviate these risks. However, with the fast development of video generation models, such as Sora and WanX, there is currently a lack of large-scale, high-quality AI-generated video datasets for forgery detection. In addition, existing detection approaches predominantly treat the task as binary classification, lacking explainability in model decision-making and failing to provide actionable insights or guidance for the public. To address these challenges, we propose \textbf{GenBuster-200K}, a large-scale AI-generated video dataset featuring 200K high-resolution video clips, diverse latest generative techniques, and real-world scenes. We further introduce \textbf{BusterX}, a novel AI-generated video detection and explanation framework leveraging multimodal large language model (MLLM) and reinforcement learning for authenticity determination and explainable rationale. To our knowledge, GenBuster-200K is the {\it \textbf{first}} large-scale, high-quality AI-generated video dataset that incorporates the latest generative techniques for real-world scenarios. BusterX is the {\it \textbf{first}} framework to integrate MLLM with reinforcement learning for explainable AI-generated video detection. Extensive comparisons with state-of-the-art methods and ablation studies validate the effectiveness and generalizability of BusterX. The code, models, and datasets will be released.

[Arxiv](https://arxiv.org/abs/2505.12620)