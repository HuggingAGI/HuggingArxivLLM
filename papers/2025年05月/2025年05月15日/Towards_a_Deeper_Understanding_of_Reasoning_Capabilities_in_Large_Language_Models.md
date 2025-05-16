# 深入理解大型语言模型的推理能力

发布时间：2025年05月15日

`LLM应用` `人工智能` `认知科学`

> Towards a Deeper Understanding of Reasoning Capabilities in Large Language Models

# 摘要

> 大型语言模型在静态基准测试中表现优异，但它们作为自我学习和推理代理在动态环境中的潜力仍有待探索。本研究系统评估了自我反思、启发式变异和规划等提示技术，以测试代理的适应能力。我们在动态环境中对多种开源语言模型进行了实验，发现较大模型通常优于较小模型，但策略性提示可显著缩小这一差距。此外，过长的提示可能对小型模型在基础反应任务上产生负面影响，而大型模型则表现得更加稳健。高级提示技术主要使小型模型在复杂游戏中受益，但对已表现出色的大型语言模型改进有限。然而，高级推理方法的结果变化显著：在推理与决策一致时，它们能显著提升性能，但也可能带来不稳定性，导致性能大幅下滑。与人类表现相比，我们的研究发现大型语言模型在关键领域如规划、推理和空间协调上仍存在明显局限，表明当前模型仍存在根本性不足，仅靠自我反思提示可能无法完全解决。推理是多维度的任务，尽管像“思维链”这样的方法可提升数学题的多步推理能力，但动态基准测试揭示了通用推理能力的重要不足，凸显了超越静态基准测试、捕捉推理复杂性的必要性。

> While large language models demonstrate impressive performance on static benchmarks, the true potential of large language models as self-learning and reasoning agents in dynamic environments remains unclear. This study systematically evaluates the efficacy of self-reflection, heuristic mutation, and planning as prompting techniques to test the adaptive capabilities of agents. We conduct experiments with various open-source language models in dynamic environments and find that larger models generally outperform smaller ones, but that strategic prompting can close this performance gap. Second, a too-long prompt can negatively impact smaller models on basic reactive tasks, while larger models show more robust behaviour. Third, advanced prompting techniques primarily benefit smaller models on complex games, but offer less improvement for already high-performing large language models. Yet, we find that advanced reasoning methods yield highly variable outcomes: while capable of significantly improving performance when reasoning and decision-making align, they also introduce instability and can lead to big performance drops. Compared to human performance, our findings reveal little evidence of true emergent reasoning. Instead, large language model performance exhibits persistent limitations in crucial areas such as planning, reasoning, and spatial coordination, suggesting that current-generation large language models still suffer fundamental shortcomings that may not be fully overcome through self-reflective prompting alone. Reasoning is a multi-faceted task, and while reasoning methods like Chain of thought improves multi-step reasoning on math word problems, our findings using dynamic benchmarks highlight important shortcomings in general reasoning capabilities, indicating a need to move beyond static benchmarks to capture the complexity of reasoning.

[Arxiv](https://arxiv.org/abs/2505.10543)