# PROVSYN：用于入侵检测的数据增强血缘图合成方法

发布时间：2025年06月06日

`LLM应用` `网络安全` `入侵检测`

> PROVSYN: Synthesizing Provenance Graphs for Data Augmentation in Intrusion Detection Systems

# 摘要

> 血缘图分析在入侵检测中至关重要，特别是针对高级持续性威胁（APTs），因为它能揭示复杂的攻击模式。尽管近期系统结合图神经网络（GNNs）与自然语言处理（NLP）以捕获结构和语义特征，但现实数据中的类别不平衡限制了它们的有效性。为解决这一问题，我们提出PROVSYN，一个自动化框架，通过三阶段管道合成血缘图：（1）基于结构-语义建模的异构图结构合成，（2）基于规则的拓扑优化，（3）利用大型语言模型（LLMs）进行语境感知的文本属性合成。PROVSYN包含一个综合评估框架，整合了结构、文本、时间和嵌入基指标，以及语义验证机制，用于评估生成的攻击模式和系统行为的正确性。为了展示其实用价值，我们使用合成图增强下游APT检测模型的训练数据集。实验结果表明，PROVSYN生成高保真血缘图，并通过有效的数据增强提升检测性能。

> Provenance graph analysis plays a vital role in intrusion detection, particularly against Advanced Persistent Threats (APTs), by exposing complex attack patterns. While recent systems combine graph neural networks (GNNs) with natural language processing (NLP) to capture structural and semantic features, their effectiveness is limited by class imbalance in real-world data. To address this, we introduce PROVSYN, an automated framework that synthesizes provenance graphs through a three-phase pipeline: (1) heterogeneous graph structure synthesis with structural-semantic modeling, (2) rule-based topological refinement, and (3) context-aware textual attribute synthesis using large language models (LLMs). PROVSYN includes a comprehensive evaluation framework that integrates structural, textual, temporal, and embedding-based metrics, along with a semantic validation mechanism to assess the correctness of generated attack patterns and system behaviors. To demonstrate practical utility, we use the synthetic graphs to augment training datasets for downstream APT detection models. Experimental results show that PROVSYN produces high-fidelity graphs and improves detection performance through effective data augmentation.

[Arxiv](https://arxiv.org/abs/2506.06226)