# # Visual Position Prompt for MLLM based Visual Grounding
多语言大型语言模型的视觉位置提示与视觉定位研究

发布时间：2025年03月19日

`LLM应用

论文摘要：多模态大型语言模型（MLLMs）在图像相关任务中表现出色，但在需要精确空间对齐的位置感知任务（如视觉定位）中仍存在不足。这种局限性主要源于两点：首先，MLLMs缺乏显式的空间参考机制，难以将文本描述与图像中的具体位置精准关联；其次，其特征提取过程更关注全局上下文而忽略了细粒度的空间细节，导致定位能力较弱。为解决这一问题，我们提出了配备视觉位置提示（VPP）的VPP-LLaVA模型，以显著提升其定位能力。VPP-LLaVA采用了双管齐下的创新机制：全局VPP通过在输入图像上叠加可学习的类似轴的嵌入，提供结构化的空间线索；局部VPP则借助位置感知查询专注于细粒度定位，有效建议可能的对象位置。此外，我们还构建了一个包含60万样本的VPP-SFT数据集，将高质量的视觉定位数据浓缩为紧凑格式，极大提升了训练效率。在这一数据集上进行VPP训练，显著增强了模型性能。尽管使用了比其他MLLMs（如依赖约2100万样本的MiniGPT-v2）更少的训练样本，VPP-LLaVA仍在标准定位基准测试中达到了当前最优水平。项目代码和VPP-SFT数据集将在论文被接受后发布至https://github.com/WayneTomas/VPP-LLaVA。

LLM应用` `计算机视觉` `图像处理`

> Visual Position Prompt for MLLM based Visual Grounding

# 摘要

> 多模态大型语言模型（MLLMs）在图像相关任务中表现出色，但在需要精确空间对齐的位置感知任务（如视觉定位）中仍存在不足。这种局限性主要源于两点：首先，MLLMs缺乏显式的空间参考机制，难以将文本描述与图像中的具体位置精准关联；其次，其特征提取过程更关注全局上下文而忽略了细粒度的空间细节，导致定位能力较弱。为解决这一问题，我们提出了配备视觉位置提示（VPP）的VPP-LLaVA模型，以显著提升其定位能力。VPP-LLaVA采用了双管齐下的创新机制：全局VPP通过在输入图像上叠加可学习的类似轴的嵌入，提供结构化的空间线索；局部VPP则借助位置感知查询专注于细粒度定位，有效建议可能的对象位置。此外，我们还构建了一个包含60万样本的VPP-SFT数据集，将高质量的视觉定位数据浓缩为紧凑格式，极大提升了训练效率。在这一数据集上进行VPP训练，显著增强了模型性能。尽管使用了比其他MLLMs（如依赖约2100万样本的MiniGPT-v2）更少的训练样本，VPP-LLaVA仍在标准定位基准测试中达到了当前最优水平。项目代码和VPP-SFT数据集将在论文被接受后发布至https://github.com/WayneTomas/VPP-LLaVA。

> Although Multimodal Large Language Models (MLLMs) excel at various image-related tasks, they encounter challenges in precisely aligning coordinates with spatial information within images, particularly in position-aware tasks such as visual grounding. This limitation arises from two key factors. First, MLLMs lack explicit spatial references, making it difficult to associate textual descriptions with precise image locations. Second, their feature extraction processes prioritize global context over fine-grained spatial details, leading to weak localization capability. To address this issue, we introduce VPP-LLaVA, an MLLM equipped with Visual Position Prompt (VPP) to improve its grounding capability. VPP-LLaVA integrates two complementary mechanisms. The global VPP overlays learnable, axis-like embeddings onto the input image to provide structured spatial cues. The local VPP focuses on fine-grained localization by incorporating position-aware queries, which suggests probable object locations. We also introduce a VPP-SFT dataset with 0.6M samples, consolidating high-quality visual grounding data into a compact format for efficient model training. Training on this dataset with VPP enhances the model's performance, achieving state-of-the-art results on standard grounding benchmarks despite using fewer training samples compared to other MLLMs like MiniGPT-v2, which rely on much larger datasets ($\sim$21M samples). The code and VPP-SFT dataset will be available at https://github.com/WayneTomas/VPP-LLaVA upon acceptance.

[Arxiv](https://arxiv.org/abs/2503.15426)