# CoT-Space：基于强化学习的内部慢思考理论框架

发布时间：2025年09月04日

`LLM理论` `基础理论`

> CoT-Space: A Theoretical Framework for Internal Slow-Thinking via Reinforcement Learning

# 摘要

> 强化学习（RL）已成为提升大型语言模型（LLMs）推理能力的核心方法。然而，目前存在显著的理论缺口——传统的token级RL框架难以契合思维链（CoT）这类复杂多步骤思维过程的推理级本质。为此，我们提出了CoT-Space——一种新颖的理论框架，它将LLM推理从离散的token预测任务重构为连续推理级语义空间内的优化过程。通过从噪声和风险双重视角分析该过程，我们发现：收敛至最优CoT长度是欠拟合与过拟合之间根本权衡的必然结果。此外，大量实验为我们的理论发现提供了有力的实证支持。该框架不仅能为过度思考等实证现象提供连贯解释，还为未来开发更高效、更具泛化性的推理智能体奠定了坚实的理论基础。

> Reinforcement Learning (RL) has become a pivotal approach for enhancing the reasoning capabilities of Large Language Models (LLMs). However, a significant theoretical gap persists, as traditional token-level RL frameworks fail to align with the reasoning-level nature of complex, multi-step thought processes like Chain-of-Thought (CoT). To address this challenge, we introduce CoT-Space, a novel theoretical framework that recasts LLM reasoning from a discrete token-prediction task to an optimization process within a continuous, reasoning-level semantic space. By analyzing this process from both a noise perspective and a risk perspective, we demonstrate that the convergence to an optimal CoT length is a natural consequence of the fundamental trade-off between underfitting and overfitting. Furthermore, extensive experiments provide strong empirical validation for our theoretical findings. Our framework not only provides a coherent explanation for empirical phenomena such as overthinking but also offers a solid theoretical foundation to guide the future development of more effective and generalizable reasoning agents.

[Arxiv](https://arxiv.org/abs/2509.04027)