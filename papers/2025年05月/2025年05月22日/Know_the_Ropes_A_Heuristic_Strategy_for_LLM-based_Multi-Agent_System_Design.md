# # 熟谙诀窍：基于LLM的多智能体系统设计的启发式策略

发布时间：2025年05月22日

`LLM理论` `人工智能` `算法优化`

> Know the Ropes: A Heuristic Strategy for LLM-based Multi-Agent System Design

# 摘要

> 单体LLM遭遇三大硬性瓶颈：有限上下文、角色过载和脆性领域转移。传统多智能体方案虽能缓解这些问题，却引入了新的痛点：模糊的分解方式、不清晰的角色契约以及高昂的验证成本，这些都削弱了整体收益。因此，我们提出Know-The-Ropes (KtR)框架，将领域先验知识转化为算法蓝图层级结构。在这个框架中，任务被递归分解为类型化且由控制器中介的子任务，每个子任务均以零样本方式或最轻量级增强手段解决（例如链式推理、微调、自我检查）。基于No-Free-Lunch定理，KtR放弃了对通用提示的追求，转而专注于有纪律的任务分解。在背包问题（3-8个物品）上，三个GPT-4o-mini智能体通过修补单一瓶颈智能体，将准确率从零样本的3%提升至规模为5时的95%。在更具挑战性的任务分配问题（6-15个任务）上，一个六智能体o3-mini蓝图在规模10时达到100%准确率，规模13-15时达到84%，而零样本准确率仅为11%。算法感知的分解加上针对性增强，使 modest 模型转变为可靠合作者——无需持续打造更大模型。

> Single-agent LLMs hit hard limits--finite context, role overload, and brittle domain transfer. Conventional multi-agent fixes soften those edges yet expose fresh pains: ill-posed decompositions, fuzzy contracts, and verification overhead that blunts the gains. We therefore present Know-The-Ropes (KtR), a framework that converts domain priors into an algorithmic blueprint hierarchy, in which tasks are recursively split into typed, controller-mediated subtasks, each solved zero-shot or with the lightest viable boost (e.g., chain-of-thought, micro-tune, self-check). Grounded in the No-Free-Lunch theorem, KtR trades the chase for a universal prompt for disciplined decomposition. On the Knapsack problem (3-8 items), three GPT-4o-mini agents raise accuracy from 3% zero-shot to 95% on size-5 instances after patching a single bottleneck agent. On the tougher Task-Assignment problem (6-15 jobs), a six-agent o3-mini blueprint hits 100% up to size 10 and 84% on sizes 13-15, versus 11% zero-shot. Algorithm-aware decomposition plus targeted augmentation thus turns modest models into reliable collaborators--no ever-larger monoliths required.

[Arxiv](https://arxiv.org/abs/2505.16979)