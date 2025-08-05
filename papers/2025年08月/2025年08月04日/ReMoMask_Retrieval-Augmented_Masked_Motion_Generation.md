# # ReMoMask: 检索增强遮蔽动作生成

发布时间：2025年08月04日

`LLM应用` `计算机视觉` `3D动作生成`

> ReMoMask: Retrieval-Augmented Masked Motion Generation

# 摘要

> 文本到动作（T2M）生成的目标是根据自然语言描述合成现实且语义对齐的人类动作序列。然而，现有方法面临双重挑战：生成模型（如扩散模型）存在多样性不足、误差累积和物理不合理性问题，而检索增强生成（RAG）方法则表现出扩散惯性、部分模式坍塌和不同步伪影。为了解决这些限制，我们提出了ReMoMask，一个整合三项关键创新的统一框架：1) 双向动量文本-动作模型通过动量队列将负样本规模与批次大小解耦，显著提升跨模态检索精度；2) 语义时空注意力机制在部件级融合过程中施加生物力学约束，消除不同步伪影；3) RAG-无条件引导通过引入少量无条件生成来增强泛化能力。ReMoMask基于MoMask的RVQ-VAE构建，能够在极简步骤中高效生成时间连贯的动作。在标准基准上的广泛实验表明，ReMoMask实现了最先进性能，与前SOTA方法RAG-T2M相比，在HumanML3D和KIT-ML上的FID分数分别提高了3.88%和10.97%。代码：https://github.com/AIGeeksGroup/ReMoMask。网站：https://aigeeksgroup.github.io/ReMoMask。


> Text-to-Motion (T2M) generation aims to synthesize realistic and semantically aligned human motion sequences from natural language descriptions. However, current approaches face dual challenges: Generative models (e.g., diffusion models) suffer from limited diversity, error accumulation, and physical implausibility, while Retrieval-Augmented Generation (RAG) methods exhibit diffusion inertia, partial-mode collapse, and asynchronous artifacts. To address these limitations, we propose ReMoMask, a unified framework integrating three key innovations: 1) A Bidirectional Momentum Text-Motion Model decouples negative sample scale from batch size via momentum queues, substantially improving cross-modal retrieval precision; 2) A Semantic Spatio-temporal Attention mechanism enforces biomechanical constraints during part-level fusion to eliminate asynchronous artifacts; 3) RAG-Classier-Free Guidance incorporates minor unconditional generation to enhance generalization. Built upon MoMask's RVQ-VAE, ReMoMask efficiently generates temporally coherent motions in minimal steps. Extensive experiments on standard benchmarks demonstrate the state-of-the-art performance of ReMoMask, achieving a 3.88% and 10.97% improvement in FID scores on HumanML3D and KIT-ML, respectively, compared to the previous SOTA method RAG-T2M. Code: https://github.com/AIGeeksGroup/ReMoMask. Website: https://aigeeksgroup.github.io/ReMoMask.

[Arxiv](https://arxiv.org/abs/2508.02605)