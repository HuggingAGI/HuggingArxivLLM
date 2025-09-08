# 大语言模型预训练的性能扩展

发布时间：2025年09月05日

`其他` `基础理论`

> Scaling Performance of Large Language Model Pretraining

# 摘要

> 大型语言模型（LLMs）在各类自然语言处理应用中均表现出顶尖性能。训练这类模型计算成本极高：前沿人工智能（AI）研究公司为此投入数十亿美元打造超级计算基础设施，旨在基于日益庞大的数据集训练规模不断增长的模型。然而，公开文献中关于这些大型训练流水线的扩展性能与训练要点的信息却极为匮乏。大规模数据集与模型的处理本就复杂，而公开文献中关于扩展大型语言模型时如何优化训练性能的实用建议更是少之又少。本文旨在揭开大型语言模型预训练流水线的部分面纱——尤其聚焦分布式训练、跨数百节点管理大型数据集及扩展数据并行，核心在于充分释放GPU的可用计算能力。

> Large language models (LLMs) show best-in-class performance across a wide range of natural language processing applications. Training these models is an extremely computationally expensive task; frontier Artificial Intelligence (AI) research companies are investing billions of dollars into supercomputing infrastructure to train progressively larger models on increasingly massive datasets. Unfortunately, information about the scaling performance and training considerations of these large training pipelines is scarce in public literature. Working with large-scale datasets and models can be complex and practical recommendations are scarce in the public literature for tuning training performance when scaling up large language models. In this paper, we aim to demystify the large language model pretraining pipeline somewhat - in particular with respect to distributed training, managing large datasets across hundreds of nodes, and scaling up data parallelism with an emphasis on fully leveraging available GPU compute capacity.

[Arxiv](https://arxiv.org/abs/2509.05258)