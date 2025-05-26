# ADLGen：生成符号化、事件驱动的传感器序列，用于人类行为建模

发布时间：2025年05月23日

`LLM应用` `智能环境` `日常活动识别`

> ADLGen: Synthesizing Symbolic, Event-Triggered Sensor Sequences for Human Activity Modeling

# 摘要

> 日常活动数据的现实世界采集面临诸多挑战，包括隐私问题、高昂的部署和标注成本，以及人类行为的固有稀疏性和不平衡性。我们提出了ADLGen，一个专为环境辅助环境设计的生成框架，用于合成现实的、事件触发的、符号化的传感器序列。ADLGen融合了仅解码器的Transformer、基于符号的时序编码，以及上下文和布局感知的采样机制，以生成语义丰富且物理上合理的传感器事件序列。为提升语义保真度并修正结构不一致，我们将大型语言模型整合到自动化的生成-评估-优化循环中，无需人工干预或特定环境调整，即可验证逻辑、行为和时间连贯性，并自动生成修正规则。通过采用新颖评估指标的全面实验表明，ADLGen在统计保真度、语义丰富度和下游活动识别方面超越了基线生成器，为日常活动数据合成提供了一个可扩展且保护隐私的解决方案。


> Real world collection of Activities of Daily Living data is challenging due to privacy concerns, costly deployment and labeling, and the inherent sparsity and imbalance of human behavior. We present ADLGen, a generative framework specifically designed to synthesize realistic, event triggered, and symbolic sensor sequences for ambient assistive environments. ADLGen integrates a decoder only Transformer with sign based symbolic temporal encoding, and a context and layout aware sampling mechanism to guide generation toward semantically rich and physically plausible sensor event sequences. To enhance semantic fidelity and correct structural inconsistencies, we further incorporate a large language model into an automatic generate evaluate refine loop, which verifies logical, behavioral, and temporal coherence and generates correction rules without manual intervention or environment specific tuning. Through comprehensive experiments with novel evaluation metrics, ADLGen is shown to outperform baseline generators in statistical fidelity, semantic richness, and downstream activity recognition, offering a scalable and privacy-preserving solution for ADL data synthesis.

[Arxiv](https://arxiv.org/abs/2505.17987)