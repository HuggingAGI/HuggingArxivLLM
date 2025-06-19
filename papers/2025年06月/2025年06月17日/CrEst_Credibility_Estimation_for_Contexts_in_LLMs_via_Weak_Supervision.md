# CrEst：基于弱监督学习的LLM上下文可信度评估

发布时间：2025年06月17日

`LLM应用` `信息评估` `知识管理`

> CrEst: Credibility Estimation for Contexts in LLMs via Weak Supervision

# 摘要

> 上下文信息的整合显著提升了大型语言模型（LLMs）在知识密集型任务上的性能。然而，现有方法常常忽视一个关键挑战：上下文文档的可信度可能差异巨大，这可能导致不可靠信息的传播。本文中，我们提出了CrEst，这是一个新颖的弱监督框架，用于在LLM推理过程中评估上下文文档的可信度，且无需人工标注。我们的方法基于一个见解：可信的文档往往与其他可信文档在语义上具有一致性，从而可以通过文档间的一致性实现自动化可信度评估。为了将可信度整合到LLM推理中，我们提出了两种集成策略：一种是黑箱方法，适用于无法访问内部权重或激活的模型；另一种是白箱方法，直接修改注意力机制。在三种模型架构和五个数据集上的广泛实验表明，CrEst始终优于强大的基线模型，准确率最高提升26.86%，F1分数增加3.49%。进一步的分析表明，即使在高噪声条件下，CrEst仍能保持稳健的性能表现。

> The integration of contextual information has significantly enhanced the performance of large language models (LLMs) on knowledge-intensive tasks. However, existing methods often overlook a critical challenge: the credibility of context documents can vary widely, potentially leading to the propagation of unreliable information. In this paper, we introduce CrEst, a novel weakly supervised framework for assessing the credibility of context documents during LLM inference--without requiring manual annotations. Our approach is grounded in the insight that credible documents tend to exhibit higher semantic coherence with other credible documents, enabling automated credibility estimation through inter-document agreement. To incorporate credibility into LLM inference, we propose two integration strategies: a black-box approach for models without access to internal weights or activations, and a white-box method that directly modifies attention mechanisms. Extensive experiments across three model architectures and five datasets demonstrate that CrEst consistently outperforms strong baselines, achieving up to a 26.86% improvement in accuracy and a 3.49% increase in F1 score. Further analysis shows that CrEst maintains robust performance even under high-noise conditions.

[Arxiv](https://arxiv.org/abs/2506.14912)