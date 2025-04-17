# 高效自适应的同时语音翻译，基于完全单向架构

发布时间：2025年04月16日

`LLM应用` `语音翻译`

> Efficient and Adaptive Simultaneous Speech Translation with Fully Unidirectional Architecture

# 摘要

> 同时语音翻译（SimulST）在处理部分语音输入时逐步生成翻译。尽管大型语言模型（LLMs）在离线翻译任务中表现出色，但将其应用于同时语音翻译（SimulST）却面临诸多挑战。现有的基于LLM的SimulST方法要么因重复编码双向语音编码器而产生显著计算开销，要么依赖固定读写策略，限制了效率和性能。为此，我们提出了高效自适应同时语音翻译（EASiST），采用完全单向架构，包含语音编码器和LLM。EASiST通过多时延数据整理策略生成语义对齐的SimulST训练样本，并将SimulST重新定义为带有显式读写标记的交错生成任务。为了实现自适应推理，我们引入了轻量级策略头，用于动态预测读写动作。此外，我们采用多阶段训练策略对齐语音-文本模态，并优化翻译与策略行为。在MuST-C En$ightarrow$De和En$ightarrow$Es数据集上的实验表明，EASiST在延迟-质量权衡方面优于多个强大基线。

> Simultaneous speech translation (SimulST) produces translations incrementally while processing partial speech input. Although large language models (LLMs) have showcased strong capabilities in offline translation tasks, applying them to SimulST poses notable challenges. Existing LLM-based SimulST approaches either incur significant computational overhead due to repeated encoding of bidirectional speech encoder, or they depend on a fixed read/write policy, limiting the efficiency and performance. In this work, we introduce Efficient and Adaptive Simultaneous Speech Translation (EASiST) with fully unidirectional architecture, including both speech encoder and LLM. EASiST includes a multi-latency data curation strategy to generate semantically aligned SimulST training samples and redefines SimulST as an interleaved generation task with explicit read/write tokens. To facilitate adaptive inference, we incorporate a lightweight policy head that dynamically predicts read/write actions. Additionally, we employ a multi-stage training strategy to align speech-text modalities and optimize both translation and policy behavior. Experiments on the MuST-C En$\rightarrow$De and En$\rightarrow$Es datasets demonstrate that EASiST offers superior latency-quality trade-offs compared to several strong baselines.

[Arxiv](https://arxiv.org/abs/2504.11809)