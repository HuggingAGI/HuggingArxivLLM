# BusterX：多语言大模型驱动的AI生成视频伪造检测与解释

发布时间：2025年05月18日

`LLM应用

理由：这篇论文主要探讨了如何利用多模态大型语言模型（MLLM）结合强化学习来检测AI生成的视频，属于将LLM应用于实际任务，因此归类为LLM应用。` `信息真实性`

> BusterX: MLLM-Powered AI-Generated Video Forgery Detection and Explanation

# 摘要

> AI生成模型的突破推动了超现实视频合成技术的发展，但也加剧了虚假信息通过社交媒体传播的风险，严重削弱了公众对数字内容的信任。针对这一问题，已有研究探索了多种AI生成图像的深度伪造检测方法，但随着Sora和WanX等视频生成模型的快速发展，目前仍缺乏大规模、高质量的AI生成视频数据集用于伪造检测。此外，现有检测方法多采用二分类模式，不仅难以解释模型决策依据，也无法为公众提供实用的防范建议。

为解决这些难题，我们推出了	extbf{GenBuster-200K}——一个包含20万高分辨率视频片段、涵盖最新生成技术和真实场景的大型AI生成视频数据集。同时，我们开发了	extbf{BusterX}框架，通过结合多模态大型语言模型(MLLM)和强化学习，实现视频真实性的准确判定与可解释分析。值得注意的是，GenBuster-200K是首个专为现实场景设计、整合最新生成技术的大规模高质量AI生成视频数据集，而BusterX则是首个将MLLM与强化学习相结合用于可解释AI生成视频检测的框架。

通过与现有最先进的方法进行广泛对比和深入的消融研究，我们验证了BusterX在视频检测任务中的优异性能和良好泛化能力。项目代码、训练模型及数据集将对外开放，为学术研究和实际应用提供有力支持。

> Advances in AI generative models facilitate super-realistic video synthesis, amplifying misinformation risks via social media and eroding trust in digital content. Several research works have explored new deepfake detection methods on AI-generated images to alleviate these risks. However, with the fast development of video generation models, such as Sora and WanX, there is currently a lack of large-scale, high-quality AI-generated video datasets for forgery detection. In addition, existing detection approaches predominantly treat the task as binary classification, lacking explainability in model decision-making and failing to provide actionable insights or guidance for the public. To address these challenges, we propose \textbf{GenBuster-200K}, a large-scale AI-generated video dataset featuring 200K high-resolution video clips, diverse latest generative techniques, and real-world scenes. We further introduce \textbf{BusterX}, a novel AI-generated video detection and explanation framework leveraging multimodal large language model (MLLM) and reinforcement learning for authenticity determination and explainable rationale. To our knowledge, GenBuster-200K is the {\it \textbf{first}} large-scale, high-quality AI-generated video dataset that incorporates the latest generative techniques for real-world scenarios. BusterX is the {\it \textbf{first}} framework to integrate MLLM with reinforcement learning for explainable AI-generated video detection. Extensive comparisons with state-of-the-art methods and ablation studies validate the effectiveness and generalizability of BusterX. The code, models, and datasets will be released.

[Arxiv](https://arxiv.org/abs/2505.12620)