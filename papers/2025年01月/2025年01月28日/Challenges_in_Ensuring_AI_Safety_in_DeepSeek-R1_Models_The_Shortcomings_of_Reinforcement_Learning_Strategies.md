# DeepSeek-R1 模型 AI 安全挑战：强化学习策略的短板

发布时间：2025年01月28日

`LLM理论

理由：这篇论文主要讨论了大型语言模型（LLMs）在无害性控制方面的挑战，特别是针对DeepSeek-R1模型的分析。论文探讨了强化学习（RL）和监督微调（SFT）在减少有害输出方面的局限性，并提出了一种混合训练方法。这些内容涉及LLM的理论研究，特别是模型对齐、训练方法和无害性控制的理论探讨，因此应归类为LLM理论。` `人工智能`

> Challenges in Ensuring AI Safety in DeepSeek-R1 Models: The Shortcomings of Reinforcement Learning Strategies

# 摘要

> 大型语言模型（LLMs）在推理、对齐和任务性能上取得了显著进展，但确保其无害性仍是一大挑战，尤其是在DeepSeek-R1等先进模型中。本文分析了强化学习（RL）作为减少DeepSeek-R1有害输出的主要方法的局限性，并与监督微调（SFT）进行了对比。尽管RL提升了推理能力，但它面临奖励黑客、泛化失败、语言混合和高计算成本等问题。我们提出了结合RL和SFT的混合训练方法，以实现更稳健的无害性控制。此外，还提供了负责任部署DeepSeek-R1的建议和未来研究方向。

> Large Language Models (LLMs) have achieved remarkable progress in reasoning, alignment, and task-specific performance. However, ensuring harmlessness in these systems remains a critical challenge, particularly in advanced models like DeepSeek-R1. This paper examines the limitations of Reinforcement Learning (RL) as the primary approach for reducing harmful outputs in DeepSeek-R1 and compares it with Supervised Fine-Tuning (SFT). While RL improves reasoning capabilities, it faces challenges such as reward hacking, generalization failures, language mixing, and high computational costs. We propose hybrid training approaches combining RL and SFT to achieve robust harmlessness reduction. Usage recommendations and future directions for deploying DeepSeek-R1 responsibly are also presented.

[Arxiv](https://arxiv.org/abs/2501.17030)