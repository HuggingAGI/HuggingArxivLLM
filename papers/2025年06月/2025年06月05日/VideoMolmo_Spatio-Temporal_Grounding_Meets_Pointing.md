# VideoMolmo：空间-时间定位与指向的交汇

发布时间：2025年06月05日

`LLM应用` `自动驾驶` `机器人技术`

> VideoMolmo: Spatio-Temporal Grounding Meets Pointing

# 摘要

> 时空定位是实现跨领域精准交互的关键，从生物研究到自主导航以及交互界面等场景均离不开这一技术。现有的基于视频的方法虽然在跟踪方面表现出色，但缺乏大型语言模型的复杂推理能力，导致其在上下文理解和泛化能力上存在局限。为此，我们推出了 VideoMolmo，这是一个专为基于文本描述的细粒度时空定位而设计的大型多模态模型。基于 Molmo 架构，VideoMolmo 引入了一个时间模块，通过注意力机制让每一帧都依赖于前序帧，从而确保时间一致性。此外，我们的创新性时间掩膜融合管道采用 SAM2 实现双向点传播，显著提升了视频序列的连贯性。这种两步分解方法，即先利用语言模型生成精确的定位坐标，再借助序列掩膜融合模块生成连贯的分割结果，不仅简化了语言模型的任务，还增强了可解释性。由于缺乏合适的现有数据集，我们整理了一个包含 72,000 个视频-字幕对和 100,000 个标注对象点的综合数据集。为了评估 VideoMolmo 的泛化能力，我们创建了 VPoS-Bench，这是一个涵盖五个真实场景的具挑战性的分布外基准测试：细胞追踪、自我中心视觉、自动驾驶、视频 GUI 交互和机器人技术。我们还对模型在引用视频对象分割（Refer-VOS）和推理 VOS 任务上的表现进行了评估。与现有模型相比，VideoMolmo 在时空定位精度和推理能力上都有显著提升。我们的代码和模型已在 https://github.com/mbzuai-oryx/VideoMolmo 上公开发布。

> Spatio-temporal localization is vital for precise interactions across diverse domains, from biological research to autonomous navigation and interactive interfaces. Current video-based approaches, while proficient in tracking, lack the sophisticated reasoning capabilities of large language models, limiting their contextual understanding and generalization. We introduce VideoMolmo, a large multimodal model tailored for fine-grained spatio-temporal pointing conditioned on textual descriptions. Building upon the Molmo architecture, VideoMolmo incorporates a temporal module utilizing an attention mechanism to condition each frame on preceding frames, ensuring temporal consistency. Additionally, our novel temporal mask fusion pipeline employs SAM2 for bidirectional point propagation, significantly enhancing coherence across video sequences. This two-step decomposition, i.e., first using the LLM to generate precise pointing coordinates, then relying on a sequential mask-fusion module to produce coherent segmentation, not only simplifies the task for the language model but also enhances interpretability. Due to the lack of suitable datasets, we curate a comprehensive dataset comprising 72k video-caption pairs annotated with 100k object points. To evaluate the generalization of VideoMolmo, we introduce VPoS-Bench, a challenging out-of-distribution benchmark spanning five real-world scenarios: Cell Tracking, Egocentric Vision, Autonomous Driving, Video-GUI Interaction, and Robotics. We also evaluate our model on Referring Video Object Segmentation (Refer-VOS) and Reasoning VOS tasks. In comparison to existing models, VideoMolmo substantially improves spatio-temporal pointing accuracy and reasoning capability. Our code and models are publicly available at https://github.com/mbzuai-oryx/VideoMolmo.

[Arxiv](https://arxiv.org/abs/2506.05336)