# 借助推理增强的奖励模型，强化思维过程

发布时间：2024年12月30日

`LLM应用

**理由**：这篇论文主要讨论了如何通过蒸馏-强化-推理（DRR）框架来改进大型语言模型（LLMs）在复杂多步推理任务中的表现。该框架涉及生成行为数据、训练判别奖励模型以及在推理时辅助决策，这些都是针对LLM在实际应用中的优化和改进。因此，这篇论文应归类为LLM应用。` `人工智能`

> Reinforcing Thinking through Reasoning-Enhanced Reward Models

# 摘要

> 大型语言模型（LLMs）在复杂多步推理中展现出巨大潜力，但因其对知识边界的有限认知，难以决定何时停止思考。尽管人类偏好对齐提供了新机遇，但高昂的标注成本阻碍了扩展法则的遵循。语言模型自我批评作为替代方案，因其固有偏见而备受质疑。本研究通过将LLM的推理过程提炼为合成行为数据，解决了这些挑战，无需手动标注中间步骤。基于此，我们提出了蒸馏-强化-推理（DRR）三步框架：首先，利用推理器（LLM）生成行为数据以展示其推理能力；其次，在行为数据上训练轻量级判别奖励模型（DM）；最后，在推理时部署DM以辅助决策。实验表明，DRR框架在不依赖复杂数据标注的情况下优于自我批评方法。凭借轻量级设计、易复制性和适应性，DRR适用于广泛的LLM任务。

> Large Language Models (LLMs) exhibit great potential in complex multi-step reasoning through inference-time thinking but still struggle with deciding when to stop thinking due to limited self-awareness about their knowledge boundaries. While human preference alignment has shown extraordinary opportunities, expensive labeling challenges adherence to scaling law. Language model self-critique, as an alternative to using human-labeled reasoning data, is questioned with its inherited biases. This work addresses these challenges by distilling the LLM's own reasoning processes into synthetic behavioral data, eliminating the need for manual labeling of intermediate steps. Building on this concept, we propose Distillation-Reinforcement-Reasoning (DRR), a three-step framework that leverages the LLM's inherent behaviors as external feedback by first generating behavioral data using the Reasoner (LLM) to reflect its reasoning capabilities, then training a lightweight discriminative reward model (DM) on behavioral data, and finally deploying the DM at inference time to assist the Reasoner's decision-making. Experiments on multiple benchmarks show that the DRR framework outperforms self-critique approaches without relying on additional complex data annotation. Benefiting from lightweight design, ease of replication, and adaptability, DRR is applicable to a wide range of LLM-centric tasks.

[Arxiv](https://arxiv.org/abs/2501.01457)