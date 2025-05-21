# 权重与奇异值的双重分解及低秩适应

发布时间：2025年05月20日

`LLM理论` `人工智能` `大型语言模型`

> Dual Decomposition of Weights and Singular Value Low Rank Adaptation

# 摘要

> 参数高效微调（PEFT）在适应大型语言模型（LLMs）的下游任务中扮演了关键角色，其中低秩适配（LoRA）是最受欢迎的方法之一。然而，现有的基于LoRA的技术存在两大核心问题：训练过程不稳定和知识迁移效率低下，这些问题均源于适配器参数的随机初始化。为了解决这些难题，我们提出了DuDe，一种创新性方法，通过将权重矩阵分解为幅度和方向两部分，并采用奇异值分解（SVD）进行科学初始化。我们的全面评估显示，DuDe在MMLU上达到了48.35%的高准确率，在GSM8K上实现了62.53%（±1.59）的优异成绩。理论分析与实证结果共同证明，DuDe的分解策略不仅提升了优化稳定性，还更好地保留了预训练模型的知识，尤其在需要专业知识的特定领域任务中表现突出。凭借其卓越的实证表现和坚实的理论基础，DuDe为LLMs的参数高效微调方法贡献了重要价值。

> Parameter-Efficient Fine-Tuning (PEFT) has emerged as a critical paradigm for adapting Large Language Models (LLMs) to downstream tasks, among which Low-rank Adaptation (LoRA) represents one of the most widely adopted methodologies. However, existing LoRA-based approaches exhibit two fundamental limitations: unstable training dynamics and inefficient knowledge transfer from pre-trained models, both stemming from random initialization of adapter parameters. To overcome these challenges, we propose DuDe, a novel approach that decomposes weight matrices into magnitude and direction components, employing Singular Value Decomposition (SVD) for principled initialization. Our comprehensive evaluation demonstrates DuDe's superior performance and robustness, achieving up to 48.35\% accuracy on MMLU and 62.53\% ($\pm$ 1.59) accuracy on GSM8K. Our theoretical analysis and empirical validation collectively demonstrate that DuDe's decomposition strategy enhances optimization stability and better preserves pre-trained representations, particularly for domain-specific tasks requiring specialized knowledge. The combination of robust empirical performance and rigorous theoretical foundations establishes DuDe as a significant contribution to PEFT methodologies for LLMs.

[Arxiv](https://arxiv.org/abs/2505.14367)