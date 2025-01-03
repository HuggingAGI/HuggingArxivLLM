# TexAVi: 基于文本描述生成立体VR视频片段

发布时间：2025年01月02日

`其他

理由：这篇论文主要讨论的是从文本生成虚拟现实视频的技术，涉及文本到图像模型、Stable Diffusion、深度估计算法等技术。虽然提到了大型语言模型（LLM），但论文的核心内容并不直接涉及LLM的应用、理论或与LLM相关的Agent或RAG技术。因此，将其分类为“其他”更为合适。` `虚拟现实` `图形生成`

> TexAVi: Generating Stereoscopic VR Video Clips from Text Descriptions

# 摘要

> 尽管文本到图像、大型语言模型和文本到视频等生成模型取得了显著进展，但由于训练数据不足和虚拟环境中实现逼真深度与运动的复杂性，文本到虚拟现实的扩展仍处于探索阶段。本文提出了一种方法，通过整合现有生成系统，从文本生成立体虚拟现实视频。
    该方法分为三个阶段：首先，使用基础文本到图像模型从输入文本中提取上下文；接着，对生成的初步图像应用 Stable Diffusion，提升帧的真实感和质量；最后，通过深度估计算法生成左右眼视图，并将其拼接为沉浸式视频。这一系统在虚拟现实制作中极具潜力，能够大幅减少拍摄和场景构建的工作量。
    我们采用 Fréchet Inception Distance 和 CLIP Score 等图像评估技术，量化生成帧的视觉质量，验证了方法的有效性。
    本研究展示了自然语言驱动图形在虚拟现实模拟等领域的广阔前景。

> While generative models such as text-to-image, large language models and text-to-video have seen significant progress, the extension to text-to-virtual-reality remains largely unexplored, due to a deficit in training data and the complexity of achieving realistic depth and motion in virtual environments. This paper proposes an approach to coalesce existing generative systems to form a stereoscopic virtual reality video from text.
  Carried out in three main stages, we start with a base text-to-image model that captures context from an input text. We then employ Stable Diffusion on the rudimentary image produced, to generate frames with enhanced realism and overall quality. These frames are processed with depth estimation algorithms to create left-eye and right-eye views, which are stitched side-by-side to create an immersive viewing experience. Such systems would be highly beneficial in virtual reality production, since filming and scene building often require extensive hours of work and post-production effort.
  We utilize image evaluation techniques, specifically Fréchet Inception Distance and CLIP Score, to assess the visual quality of frames produced for the video. These quantitative measures establish the proficiency of the proposed method.
  Our work highlights the exciting possibilities of using natural language-driven graphics in fields like virtual reality simulations.

[Arxiv](https://arxiv.org/abs/2501.01156)