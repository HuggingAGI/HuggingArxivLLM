# 迈向无需伪装标注的真实零样本伪装目标分割

发布时间：2024年10月22日

`LLM应用

理由：该论文摘要描述了一个利用多模态大语言模型（M-LLM）来实现零-shot伪装目标分割（COS）的框架。虽然论文的主要关注点是计算机视觉任务（COS），但其核心方法依赖于多模态大语言模型（M-LLM）的嵌入生成和语义对齐能力，属于将大语言模型应用于特定任务（即零-shot分割）的范畴。因此，该论文应归类为LLM应用。` `计算机视觉` `图像分割`

> Towards Real Zero-Shot Camouflaged Object Segmentation without Camouflaged Annotations

# 摘要

> # 摘要
伪装目标分割（COS）因标注数据稀缺而面临巨大挑战，细致的像素级标注既耗时又昂贵，主要源于目标与背景边界的复杂性。针对“能否在无需手动标注的情况下，以零-shot方式有效实现COS？”这一核心问题，我们给出了肯定答案，并提出了一个强大的零-shot COS框架。该框架利用COS的局部模式偏差，结合显著目标分割（SOS）的广泛语义特征空间，实现高效的零-shot迁移。我们集成了基于掩码图像建模（MIM）的图像编码器（针对参数高效微调优化）、多模态大语言模型（M-LLM）以及多尺度细粒度对齐（MFA）机制。MIM编码器专注于捕捉关键低级特征，M-LLM生成与视觉线索协同处理的标题嵌入，并通过MFA精确对齐，使框架能够准确解析复杂语义。为提升效率，我们引入可学习代码本，在推理中替代M-LLM，大幅降低计算开销。实验表明，该框架在零-shot COS中表现卓越，CAMO和COD10K上的$F_β^w$得分分别达72.9%和71.7%。移除M-LLM后，推理速度与传统端到端模型相当，达到18.1 FPS。代码：https://github.com/R-LEI360725/ZSCOS-CaMF

> Camouflaged Object Segmentation (COS) faces significant challenges due to the scarcity of annotated data, where meticulous pixel-level annotation is both labor-intensive and costly, primarily due to the intricate object-background boundaries. Addressing the core question, "Can COS be effectively achieved in a zero-shot manner without manual annotations for any camouflaged object?" we affirmatively respond and introduce a robust zero-shot COS framework. This framework leverages the inherent local pattern bias of COS and employs a broad semantic feature space derived from salient object segmentation (SOS) for efficient zero-shot transfer. We incorporate an Masked Image Modeling (MIM) based image encoder optimized for Parameter-Efficient Fine-Tuning (PEFT), a Multimodal Large Language Model (M-LLM), and a Multi-scale Fine-grained Alignment (MFA) mechanism. The MIM pre-trained image encoder focuses on capturing essential low-level features, while the M-LLM generates caption embeddings processed alongside these visual cues. These embeddings are precisely aligned using MFA, enabling our framework to accurately interpret and navigate complex semantic contexts. To optimize operational efficiency, we introduce a learnable codebook that represents the M-LLM during inference, significantly reducing computational overhead. Our framework demonstrates its versatility and efficacy through rigorous experimentation, achieving state-of-the-art performance in zero-shot COS with $F_β^w$ scores of 72.9\% on CAMO and 71.7\% on COD10K. By removing the M-LLM during inference, we achieve an inference speed comparable to that of traditional end-to-end models, reaching 18.1 FPS. Code: https://github.com/R-LEI360725/ZSCOS-CaMF

[Arxiv](https://arxiv.org/abs/2410.16953)