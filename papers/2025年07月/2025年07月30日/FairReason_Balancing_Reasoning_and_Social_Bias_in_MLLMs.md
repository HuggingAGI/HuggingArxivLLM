# FairReason：多语言语言模型中推理与社会偏见的平衡之道

发布时间：2025年07月30日

`LLM应用` `人工智能` `偏见缓解`

> FairReason: Balancing Reasoning and Social Bias in MLLMs

# 摘要

> 多模态大型语言模型（MLLMs）在多种任务和模态中已达到顶尖水平。为进一步提升推理能力，近期研究探索了高级提示方案和后训练微调方法。尽管这些技术提高了逻辑准确性，但模型输出常带有显著社会偏见。推理增强与偏见缓解之间的相互作用——以及两者是否本质上存在权衡——仍是开放且紧迫的研究问题。我们的研究首先在相同条件下基准测试了三种偏见缓解策略——监督微调（SFT）、知识蒸馏（KD）和基于规则的强化学习（RL）——以确定其优缺点。在此基础上，我们调整了每个范式中去偏见和推理中心样本的比例，以绘制推理与偏见之间的权衡图。实验结果显示：通过强化学习训练的1:4样本比例，可以使刻板印象评分降低10%，同时保持模型原有推理准确性的88%，为在MLLMs中平衡公平性和能力提供了切实可行的指导。

> Multimodal Large Language Models (MLLMs) already achieve state-of-the-art results across a wide range of tasks and modalities. To push their reasoning ability further, recent studies explore advanced prompting schemes and post-training fine-tuning. Although these techniques improve logical accuracy, they frequently leave the models' outputs burdened with pronounced social biases. Clarifying how reasoning gains interact with bias mitigation-and whether the two objectives inherently trade off-therefore remains an open and pressing research problem. Our study begins by benchmarking three bias-mitigation strategies-supervised fine-uning (SFT), knowledge distillation (KD), and rule-based reinforcement learning (RL)-under identical conditions, establishing their baseline strengths and weaknesses. Building on these results, we vary the proportion of debias-focused and reasoning-centric samples within each paradigm to chart the reasoning-versus-bias trade-off. Our sweeps reveal a consistent sweet spot: a roughly 1:4 mix trained with reinforcement learning cuts stereotype scores by 10% while retaining 88% of the model's original reasoning accuracy, offering concrete guidance for balancing fairness and capability in MLLMs.

[Arxiv](https://arxiv.org/abs/2507.23067)