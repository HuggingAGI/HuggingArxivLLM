# M3-AGIQA：多模态、多轮交互、多维度评估的AI生成图像质量评估

发布时间：2025年02月20日

`LLM应用` `图像生成` `图像处理`

> M3-AGIQA: Multimodal, Multi-Round, Multi-Aspect AI-Generated Image Quality Assessment

# 摘要

> 人工智能生成图像 (AGI) 模型的快速发展带来了质量评估的多重挑战，涉及感知质量、提示对应性和真实性等多个维度。为应对这些挑战，我们推出了 M3-AGIQA，一个全面的 AGI 质量评估框架，具备多模态、多轮和多方面的特性。该框架巧妙运用多模态大型语言模型 (MLLMs) 作为联合文本和图像编码器，并通过低秩适应 (LoRA) 微调技术，将在线 MLLMs 的高级描述能力整合到本地模型中。其结构化的多轮评估机制通过生成中间图像描述，深入剖析质量、对应性和真实性等关键要素。为了确保预测结果与人类感知判断高度一致，我们引入了一个由 xLSTM 和回归头组成的预测器，用于处理序列 logits 并预测平均意见得分 (MOS)。在多个基准数据集上的广泛实验表明，M3-AGIQA 不仅达到了当前最优的性能水平，更精准地捕捉了 AGI 质量的细微差别，而且通过跨数据集验证，展现了卓越的泛化能力。代码现已开源，地址为 https://github.com/strawhatboy/M3-AGIQA。

> The rapid advancement of AI-generated image (AGI) models has introduced significant challenges in evaluating their quality, which requires considering multiple dimensions such as perceptual quality, prompt correspondence, and authenticity. To address these challenges, we propose M3-AGIQA, a comprehensive framework for AGI quality assessment that is Multimodal, Multi-Round, and Multi-Aspect. Our approach leverages the capabilities of Multimodal Large Language Models (MLLMs) as joint text and image encoders and distills advanced captioning capabilities from online MLLMs into a local model via Low-Rank Adaptation (LoRA) fine-tuning. The framework includes a structured multi-round evaluation mechanism, where intermediate image descriptions are generated to provide deeper insights into the quality, correspondence, and authenticity aspects. To align predictions with human perceptual judgments, a predictor constructed by an xLSTM and a regression head is incorporated to process sequential logits and predict Mean Opinion Scores (MOSs). Extensive experiments conducted on multiple benchmark datasets demonstrate that M3-AGIQA achieves state-of-the-art performance, effectively capturing nuanced aspects of AGI quality. Furthermore, cross-dataset validation confirms its strong generalizability. The code is available at https://github.com/strawhatboy/M3-AGIQA.

[Arxiv](https://arxiv.org/abs/2502.15167)