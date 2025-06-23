# BatteryBERT：通过点遮蔽信号建模实现真实电池故障检测。

发布时间：2025年05月31日

`LLM应用` `电动汽车` `储能系统`

> BatteryBERT for Realistic Battery Fault Detection Using Point-Masked Signal Modeling

# 摘要

> 锂离子电池的精准故障检测是保障电动汽车和储能系统安全运行的关键。然而，现有方法在捕捉复杂时序依赖关系和充分利用无标签数据方面仍存在局限。尽管大型语言模型（LLMs）具有强大的表示能力，但其架构并不直接适用于工业环境中常见的数值型时序数据。为此，我们提出了一种创新框架，通过扩展标准BERT架构，加入定制的时间序列到令牌表示模块，并针对电池应用设计了点级掩码信号建模（point-MSM）预训练任务，成功将BERT风格的预训练方法引入电池故障检测领域。这种方法能够实现对电流、电压等时序数据的自监督学习，生成分布稳健且具有上下文感知能力的时序嵌入。通过将这些嵌入与电池元数据结合，并输入下游分类器，我们实现了精准的故障分类。在大规模真实世界数据集上的实验表明，采用我们预训练参数初始化的模型在表示质量和分类准确性方面均有显著提升，实现了0.945的AUROC值，远超现有方法。这一结果充分验证了BERT风格预训练在时序故障检测中的有效性。

> Accurate fault detection in lithium-ion batteries is essential for the safe and reliable operation of electric vehicles and energy storage systems. However, existing methods often struggle to capture complex temporal dependencies and cannot fully leverage abundant unlabeled data. Although large language models (LLMs) exhibit strong representation capabilities, their architectures are not directly suited to the numerical time-series data common in industrial settings. To address these challenges, we propose a novel framework that adapts BERT-style pretraining for battery fault detection by extending the standard BERT architecture with a customized time-series-to-token representation module and a point-level Masked Signal Modeling (point-MSM) pretraining task tailored to battery applications. This approach enables self-supervised learning on sequential current, voltage, and other charge-discharge cycle data, yielding distributionally robust, context-aware temporal embeddings. We then concatenate these embeddings with battery metadata and feed them into a downstream classifier for accurate fault classification. Experimental results on a large-scale real-world dataset show that models initialized with our pretrained parameters significantly improve both representation quality and classification accuracy, achieving an AUROC of 0.945 and substantially outperforming existing approaches. These findings validate the effectiveness of BERT-style pretraining for time-series fault detection.

[Arxiv](https://arxiv.org/abs/2506.15712)