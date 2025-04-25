# GCN 结构信息与 LLM 化学知识融合，提升虚拟筛选效果

发布时间：2025年04月24日

`LLM应用` `药物发现`

> Combining GCN Structural Learning with LLM Chemical Knowledge for or Enhanced Virtual Screening

# 摘要

> 虚拟筛选在现代药物发现中发挥着关键作用，它能够有效识别出值得实验验证的候选分子。传统机器学习方法如支持向量机（SVM）和XGBoost依赖预定义的分子表示，这可能带来信息丢失和潜在偏差。而深度学习方法——特别是图卷积网络（GCNs）——通过直接处理分子图，提供了一种更强大且无偏见的解决方案。与此同时，大型语言模型（LLMs）凭借其强大的注意力机制，从大规模数据中捕捉复杂化学模式，在药物设计领域展现了卓越性能。  
  本文提出了一种创新的混合架构，将GCNs与LLM衍生嵌入相结合，实现了局部结构学习与全局化学知识的深度整合。LLM嵌入可预先计算并存储于分子特征库中，无需在训练或推理过程中重复运行LLM，从而确保了计算效率。研究发现，在每个GCN层之后（而非仅在最后一层）融入LLM嵌入，能够显著提升模型性能，使全局上下文在全网络中得到更深层次的整合。最终，我们的模型取得了优异的F1分数（88.8%），超越了独立GCN（87.9%）、XGBoost（85.5%）和SVM（85.4%）的传统方法。

> Virtual screening plays a critical role in modern drug discovery by enabling the identification of promising candidate molecules for experimental validation. Traditional machine learning methods such as support vector machines (SVM) and XGBoost rely on predefined molecular representations, often leading to information loss and potential bias. In contrast, deep learning approaches-particularly Graph Convolutional Networks (GCNs)-offer a more expressive and unbiased alternative by operating directly on molecular graphs. Meanwhile, Large Language Models (LLMs) have recently demonstrated state-of-the-art performance in drug design, thanks to their capacity to capture complex chemical patterns from large-scale data via attention mechanisms.
  In this paper, we propose a hybrid architecture that integrates GCNs with LLM-derived embeddings to combine localized structural learning with global chemical knowledge. The LLM embeddings can be precomputed and stored in a molecular feature library, removing the need to rerun the LLM during training or inference and thus maintaining computational efficiency. We found that concatenating the LLM embeddings after each GCN layer-rather than only at the final layer-significantly improves performance, enabling deeper integration of global context throughout the network. The resulting model achieves superior results, with an F1-score of (88.8%), outperforming standalone GCN (87.9%), XGBoost (85.5%), and SVM (85.4%) baselines.

[Arxiv](https://arxiv.org/abs/2504.17497)