# Domaino1s: 在高风险领域中引导LLM推理，生成可解释的答案

发布时间：2025年01月24日

`LLM应用

**理由**：这篇论文主要讨论了如何通过监督微调和树搜索提升大型语言模型（LLMs）在特定领域任务（如金融投资和法律问答）中的推理能力。论文提出了新的方法（如选择性树探索和PROOF-Score评估指标）来增强模型的可解释性和性能。这些内容属于LLM在实际应用中的改进和优化，因此分类为LLM应用。`

> Domaino1s: Guiding LLM Reasoning for Explainable Answers in High-Stakes Domains

# 摘要

> 大型语言模型（LLMs）广泛应用于下游领域，但在高风险任务（如金融投资和法律问答）中，现有模型往往只提供简短答案，缺乏推理和解释，降低了用户对其回答的信任。尽管原始的CoT（Chain-of-Thought）展现了潜力，但其推理过程缺乏自我纠正机制。为此，我们提出了Domain$o1$s，通过监督微调和树搜索提升LLMs在领域任务中的推理能力。我们构建了CoT-stock-2k和CoT-legal-2k数据集，用于微调模型，使其能够根据判断激活领域特定的推理步骤。此外，我们提出了选择性树探索，自动探索解决方案空间并采样最优推理路径，以提升性能。我们还引入了PROOF-Score，这是一种新的可解释性评估指标，为传统准确性指标提供了更丰富的评估维度。在股票投资推荐和法律推理问答任务上的大量实验表明，Domaino1s在性能和可解释性方面均表现优异。代码已开源：https://anonymous.4open.science/r/Domaino1s-006F/。

> Large Language Models (LLMs) are widely applied to downstream domains. However, current LLMs for high-stakes domain tasks, such as financial investment and legal QA, typically generate brief answers without reasoning processes and explanations. This limits users' confidence in making decisions based on their responses. While original CoT shows promise, it lacks self-correction mechanisms during reasoning. This work introduces Domain$o1$s, which enhances LLMs' reasoning capabilities on domain tasks through supervised fine-tuning and tree search. We construct CoT-stock-2k and CoT-legal-2k datasets for fine-tuning models that activate domain-specific reasoning steps based on their judgment. Additionally, we propose Selective Tree Exploration to spontaneously explore solution spaces and sample optimal reasoning paths to improve performance. We also introduce PROOF-Score, a new metric for evaluating domain models' explainability, complementing traditional accuracy metrics with richer assessment dimensions. Extensive experiments on stock investment recommendation and legal reasoning QA tasks demonstrate Domaino1s's leading performance and explainability. Our code is available at https://anonymous.4open.science/r/Domaino1s-006F/.

[Arxiv](https://arxiv.org/abs/2501.14431)