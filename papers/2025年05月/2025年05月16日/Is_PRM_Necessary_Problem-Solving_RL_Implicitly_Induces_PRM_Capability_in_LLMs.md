# PRM真的必要吗？问题解决型强化学习在LLMs中隐式具备了PRM能力

发布时间：2025年05月16日

`LLM理论` `人工智能`

> Is PRM Necessary? Problem-Solving RL Implicitly Induces PRM Capability in LLMs

# 摘要

> 推理能力的发展是大型语言模型（LLMs）研究中的关键前沿领域。强化学习（RL）和过程奖励模型（PRMs）是这一领域的两大主要方法论框架。然而，DeepSeek-R1的实证结果颠覆了传统认知：专注于数学问题解决的纯RL训练无需集成PRM，即可逐步提升推理能力。本研究深入探讨了RL训练与PRM能力之间的关系，发现问题解决熟练度与过程监督能力是推理的两个互补维度，二者在纯RL训练中协同进化。值得注意的是，当前的PRMs在应用于DeepSeek-R1和QwQ-32B等先进模型时，表现甚至不如简单的多数投票基线。为解决这一局限性，我们提出了Self-PRM，这是一种内省框架，模型通过自我奖励机制自主评估和重新排序生成的解决方案。尽管Self-PRM在基准准确性（尤其是在更大的样本量下）上始终有所提升，但分析揭示了持续存在的挑战：该方法在困难问题上精度较低（<10%），经常错误地将有缺陷的解决方案归类为有效。这些分析强调了继续扩展RL以改善奖励对齐和内省准确性的必要性。总体而言，我们的发现表明，PRM可能并非提升复杂推理能力的必需品，因为纯RL不仅提升了问题解决技能，还内在地培养了强大的PRM能力。我们希望这些发现能为构建更可靠且具有自我意识的复杂推理模型提供切实可行的见解。


> The development of reasoning capabilities represents a critical frontier in large language models (LLMs) research, where reinforcement learning (RL) and process reward models (PRMs) have emerged as predominant methodological frameworks. Contrary to conventional wisdom, empirical evidence from DeepSeek-R1 demonstrates that pure RL training focused on mathematical problem-solving can progressively enhance reasoning abilities without PRM integration, challenging the perceived necessity of process supervision. In this study, we conduct a systematic investigation of the relationship between RL training and PRM capabilities. Our findings demonstrate that problem-solving proficiency and process supervision capabilities represent complementary dimensions of reasoning that co-evolve synergistically during pure RL training. In particular, current PRMs underperform simple baselines like majority voting when applied to state-of-the-art models such as DeepSeek-R1 and QwQ-32B. To address this limitation, we propose Self-PRM, an introspective framework in which models autonomously evaluate and rerank their generated solutions through self-reward mechanisms. Although Self-PRM consistently improves the accuracy of the benchmark (particularly with larger sample sizes), analysis exposes persistent challenges: The approach exhibits low precision (<10\%) on difficult problems, frequently misclassifying flawed solutions as valid. These analyses underscore the need for continued RL scaling to improve reward alignment and introspective accuracy. Overall, our findings suggest that PRM may not be essential for enhancing complex reasoning, as pure RL not only improves problem-solving skills but also inherently fosters robust PRM capabilities. We hope these findings provide actionable insights for building more reliable and self-aware complex reasoning models.

[Arxiv](https://arxiv.org/abs/2505.11227)