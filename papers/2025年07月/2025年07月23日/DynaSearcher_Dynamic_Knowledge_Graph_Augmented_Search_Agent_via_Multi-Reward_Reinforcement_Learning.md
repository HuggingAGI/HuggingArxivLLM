# # 摘要  
DynaSearcher：基于多奖励强化学习的动态知识图谱增强搜索代理  
DynaSearcher通过多奖励强化学习实现动态知识图谱的增强，从而显著提升了搜索效果。

发布时间：2025年07月23日

`Agent` `知识图谱` `问答系统`

> DynaSearcher: Dynamic Knowledge Graph Augmented Search Agent via Multi-Reward Reinforcement Learning

# 摘要

> 基于大型语言模型（LLMs）的多步骤智能检索系统在复杂信息搜索任务中展现出卓越性能。然而，实际应用中仍面临生成事实不一致的中间查询和低效搜索轨迹等挑战，可能引发推理偏差或冗余计算。为应对这些难题，我们提出了一种名为DynaSearcher的创新搜索代理，结合动态知识图谱和多奖励强化学习（RL）技术。我们的系统利用知识图谱作为外部结构化知识，通过显式建模实体关系来指导搜索过程，确保中间查询的事实一致性并减少无关信息干扰。同时，我们采用多奖励RL框架对检索准确性、效率和响应质量等训练目标进行精细控制。该框架不仅促进高质量中间查询和全面最终答案的生成，还能抑制不必要的探索并减少信息遗漏或冗余。实验结果表明，我们的方法在六个多跳问答数据集上达到了顶尖的答案准确性，且仅使用小型模型和有限计算资源即可匹敌前沿LLMs。此外，我们的方法在各种检索环境和更大规模模型中展现出强大的泛化能力和鲁棒性，凸显了其广泛应用前景。

> Multi-step agentic retrieval systems based on large language models (LLMs) have demonstrated remarkable performance in complex information search tasks. However, these systems still face significant challenges in practical applications, particularly in generating factually inconsistent intermediate queries and inefficient search trajectories, which can lead to reasoning deviations or redundant computations. To address these issues, we propose DynaSearcher, an innovative search agent enhanced by dynamic knowledge graphs and multi-reward reinforcement learning (RL). Specifically, our system leverages knowledge graphs as external structured knowledge to guide the search process by explicitly modeling entity relationships, thereby ensuring factual consistency in intermediate queries and mitigating biases from irrelevant information. Furthermore, we employ a multi-reward RL framework for fine-grained control over training objectives such as retrieval accuracy, efficiency, and response quality. This framework promotes the generation of high-quality intermediate queries and comprehensive final answers, while discouraging unnecessary exploration and minimizing information omissions or redundancy. Experimental results demonstrate that our approach achieves state-of-the-art answer accuracy on six multi-hop question answering datasets, matching frontier LLMs while using only small-scale models and limited computational resources. Furthermore, our approach demonstrates strong generalization and robustness across diverse retrieval environments and larger-scale models, highlighting its broad applicability.

[Arxiv](https://arxiv.org/abs/2507.17365)