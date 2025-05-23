# PMPO：针对大小语言模型的概率度量提示优化方法

发布时间：2025年05月22日

`LLM应用` `提示工程`

> PMPO: Probabilistic Metric Prompt Optimization for Small and Large Language Models

# 摘要

> 提示优化为提升大型语言模型（LLM）性能提供了一种实用且广泛应用的替代方案，相比微调。然而，现有方法通常依赖于昂贵的输出生成、自我批判能力或人工标注的偏好，这限制了它们的可扩展性，尤其是对于较小规模或未经过指令微调的模型。我们引入了PMPO（概率度量提示优化），一个统一的框架，它利用基于token级别的交叉熵损失作为直接、轻量级的评估信号来优化提示。PMPO通过屏蔽并衡量低质量提示片段对损失的影响来识别它们，然后通过在正例和负例上最小化损失来重写并选择改进的变体。与先前方法不同，它在优化过程中不需要输出采样或人工评估，仅依赖于前向传播和对数似然。PMPO通过紧密对齐的基于损失的评估策略，支持监督和基于偏好的任务。实验表明，PMPO在不同模型规模和任务上始终优于先前方法：它在BBH上实现了最高的平均准确率，在GSM8K和AQUA-RAT上表现强劲，并将AlpacaEval 2.0的胜率提高了超过19个百分点。这些结果突显了PMPO的有效性、效率和广泛应用潜力。

> Prompt optimization offers a practical and broadly applicable alternative to fine-tuning for improving large language model (LLM) performance. However, existing methods often rely on costly output generation, self-critiquing abilities, or human-annotated preferences, which limit their scalability, especially for smaller or non-instruction-tuned models. We introduce PMPO (Probabilistic Metric Prompt Optimization), a unified framework that refines prompts using token-level cross-entropy loss as a direct, lightweight evaluation signal. PMPO identifies low-quality prompt segments by masking and measuring their impact on loss, then rewrites and selects improved variants by minimizing loss over positive and negative examples. Unlike prior methods, it requires no output sampling or human evaluation during optimization, relying only on forward passes and log-likelihoods. PMPO supports both supervised and preference-based tasks through a closely aligned loss-based evaluation strategy. Experiments show that PMPO consistently outperforms prior methods across model sizes and tasks: it achieves the highest average accuracy on BBH, performs strongly on GSM8K and AQUA-RAT, and improves AlpacaEval 2.0 win rates by over 19 points. These results highlight PMPO's effectiveness, efficiency, and broad applicability.

[Arxiv](https://arxiv.org/abs/2505.16307)