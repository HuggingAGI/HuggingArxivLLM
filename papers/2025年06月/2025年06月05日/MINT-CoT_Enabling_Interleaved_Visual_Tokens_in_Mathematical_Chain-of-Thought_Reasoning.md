# MINT-CoT：在数学链式思维推理中实现交错视觉标记

发布时间：2025年06月05日

`LLM应用` `多模态`

> MINT-CoT: Enabling Interleaved Visual Tokens in Mathematical Chain-of-Thought Reasoning

# 摘要

> 链式思维（CoT）显著提升了大型语言模型（LLMs）的数学推理能力，但将其拓展到多模态领域仍面临诸多挑战。目前的研究主要分为两类：一类是针对图像输入沿用文本推理方法，另一类是尝试将视觉信号融入数学链式思维。然而，这些方法在解决数学问题时存在三大核心局限：依赖粗粒度的框形图像区域、视觉编码器对数学内容理解有限、以及对视觉修改的外部能力依赖。为此，我们提出了MINT-CoT，通过引入数学交织令牌实现链式思维的视觉推理。MINT-CoT借助一个动态选择令牌，能够自适应地将相关视觉令牌融入文本推理步骤，精准捕捉数学图表中任意形状的视觉区域。为了支持这一创新，我们构建了包含54K数学问题的MINT-CoT数据集，每个推理步骤都与视觉区域在令牌级别精准对齐，并配备了严格的数据生成管道。我们还设计了三阶段的MINT-CoT训练策略，逐步融合纯文本CoT SFT、交织式CoT SFT和交织式CoT RL，最终打造出MINT-CoT-7B模型。实验结果表明，我们的方法在数学领域的视觉交织推理中表现出色，MINT-CoT-7B在MathVista上比基线模型高出+34.08%，在GeoQA上高出+28.78%，在MMStar上高出+23.2%。我们的代码和数据已开源，详情请访问https://github.com/xinyan-cxy/MINT-CoT

> Chain-of-Thought (CoT) has widely enhanced mathematical reasoning in Large Language Models (LLMs), but it still remains challenging for extending it to multimodal domains. Existing works either adopt a similar textual reasoning for image input, or seek to interleave visual signals into mathematical CoT. However, they face three key limitations for math problem-solving: reliance on coarse-grained box-shaped image regions, limited perception of vision encoders on math content, and dependence on external capabilities for visual modification. In this paper, we propose MINT-CoT, introducing Mathematical INterleaved Tokens for Chain-of-Thought visual reasoning. MINT-CoT adaptively interleaves relevant visual tokens into textual reasoning steps via an Interleave Token, which dynamically selects visual regions of any shapes within math figures. To empower this capability, we construct the MINT-CoT dataset, containing 54K mathematical problems aligning each reasoning step with visual regions at the token level, accompanied by a rigorous data generation pipeline. We further present a three-stage MINT-CoT training strategy, progressively combining text-only CoT SFT, interleaved CoT SFT, and interleaved CoT RL, which derives our MINT-CoT-7B model. Extensive experiments demonstrate the effectiveness of our method for effective visual interleaved reasoning in mathematical domains, where MINT-CoT-7B outperforms the baseline model by +34.08% on MathVista, +28.78% on GeoQA, and +23.2% on MMStar, respectively. Our code and data are available at https://github.com/xinyan-cxy/MINT-CoT

[Arxiv](https://arxiv.org/abs/2506.05331)