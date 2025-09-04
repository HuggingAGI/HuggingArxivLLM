# RecBase：面向零样本推荐的生成式基础模型预训练

发布时间：2025年09月03日

`LLM应用` `零售与电商`

> RecBase: Generative Foundation Model Pretraining for Zero-Shot Recommendation

# 摘要

> 基于大型语言模型（LLM）的推荐系统近期虽展现出潜力，但其跨域泛化能力却受限于以语言为中心的预训练与推荐任务之间的根本矛盾。现有方法依赖语言层面知识，难以捕捉跨域的动态物品级用户兴趣。为弥合这一差距，我们提出RecBase——一种以推荐为导向目标预训练的领域无关基础模型。RecBase借助大规模异质跨域语料库，通过统一文本表示与特征映射提升跨域泛化能力。为进一步对齐跨域物品语义，我们引入统一物品分词器，将物品编码为层级概念标识符，实现结构化表示与高效词汇共享。该模型通过自回归目标训练，以捕捉复杂的物品级序列模式。在八个真实世界数据集上，我们的15亿参数模型在零样本及跨域推荐任务中，性能达到甚至超越了参数规模达70亿的LLM基线模型。

> Recent advances in LLM-based recommendation have shown promise, yet their cross-domain generalization is hindered by a fundamental mismatch between language-centric pretraining and the recommendation task. Existing methods, relying on language-level knowledge, fail to capture dynamic, item-level user interests across domains. To bridge this gap, we propose RecBase, a domain-agnostic foundational model pretrained with a recommendation-oriented objective. RecBase leverages a large-scale, heterogeneous, cross-domain corpus with unified textual representations and feature mappings to enhance cross-domain generalization. To further align item semantics across domains, we introduce a unified item tokenizer that encodes items into hierarchical concept identifiers, enabling structured representation and efficient vocabulary sharing. The model is trained using an autoregressive objective to capture complex item-level sequential patterns. On eight real-world datasets, our 1.5B-parameter model matches or surpasses the performance of LLM baselines up to 7B parameters in zero-shot and cross-domain recommendation tasks.

[Arxiv](https://arxiv.org/abs/2509.03131)