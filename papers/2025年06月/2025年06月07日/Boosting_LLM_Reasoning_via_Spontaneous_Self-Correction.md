# # 提升LLM推理：借助自发的自我修正

发布时间：2025年06月07日

`LLM应用

这篇论文专注于改进大型语言模型（LLMs）在数学推理任务中的性能。通过提出SPOC方法，作者展示了如何通过自我纠正和多智能体协作来提升模型的推理能力，属于LLM在特定领域的应用研究。`

> Boosting LLM Reasoning via Spontaneous Self-Correction

# 摘要

> 尽管大型语言模型（LLMs）在广泛的任务中展现了显著的成功，但数学推理仍是一个具有挑战性的领域。改进数学推理的一种方法是自我纠正，它设计了自我改进循环，让模型能够自行修正错误。然而，现有自我纠正方法将修正视为独立于生成过程的后处理优化，依赖额外的提示和系统设计来触发自我纠正，而不是在单一推理过程中实现实时的自发性自我修正。为了解决这一问题，我们提出了SPOC，这是一种使LLMs能够在单一推理过程中生成交错的解答和验证的自发性自我纠正方法。SPOC根据验证结果动态终止生成过程，从而有效扩展推理时间计算。通过赋予同一模型双重角色——解答提出者和验证者，SPOC从多智能体视角出发。我们采用一种简单而有效的方法生成合成数据进行微调，使模型能够发展自我验证和多智能体协作的能力。通过在线强化学习，我们进一步提升了模型的解答提出和验证准确性。在数学推理基准测试中的实验表明，SPOC显著提升了性能。值得注意的是，SPOC提高了Llama-3.1-8B和70B Instruct模型的准确性，在MATH500上分别提升了8.8%和11.6%，在AMC23上分别提升了10.0%和20.0%，在AIME24上分别提升了3.3%和6.7%。

> While large language models (LLMs) have demonstrated remarkable success on a broad range of tasks, math reasoning remains a challenging one. One of the approaches for improving math reasoning is self-correction, which designs self-improving loops to let the model correct its own mistakes. However, existing self-correction approaches treat corrections as standalone post-generation refinements, relying on extra prompt and system designs to elicit self-corrections, instead of performing real-time, spontaneous self-corrections in a single pass. To address this, we propose SPOC, a spontaneous self-correction approach that enables LLMs to generate interleaved solutions and verifications in a single inference pass, with generation dynamically terminated based on verification outcomes, thereby effectively scaling inference time compute. SPOC considers a multi-agent perspective by assigning dual roles -- solution proposer and verifier -- to the same model. We adopt a simple yet effective approach to generate synthetic data for fine-tuning, enabling the model to develop capabilities for self-verification and multi-agent collaboration. We further improve its solution proposal and verification accuracy through online reinforcement learning. Experiments on mathematical reasoning benchmarks show that SPOC significantly improves performance. Notably, SPOC boosts the accuracy of Llama-3.1-8B and 70B Instruct models, achieving gains of 8.8% and 11.6% on MATH500, 10.0% and 20.0% on AMC23, and 3.3% and 6.7% on AIME24, respectively.

[Arxiv](https://arxiv.org/abs/2506.06923)