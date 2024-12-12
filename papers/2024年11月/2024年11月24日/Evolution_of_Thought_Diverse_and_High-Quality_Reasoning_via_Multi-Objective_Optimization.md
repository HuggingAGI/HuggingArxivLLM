# 思想的演进：借由多目标优化达成多样且高品质的推理

发布时间：2024年11月24日

`LLM应用` `多模态`

> Evolution of Thought: Diverse and High-Quality Reasoning via Multi-Objective Optimization

# 摘要

> 随着多模态大型语言模型（MLLMs）在复杂推理任务中的应用日益广泛，推理路径的多样性和质量成为影响其性能的关键要素。当前的方法虽致力于通过路径扩展提升推理质量，却常常忽视推理路径的多样性及有效的信息共享，致使出现局部最优和效率不高的情况。为应对这些挑战，我们提出了思维进化（EoT），这是一个旨在通过培育高质量且多样化的推理路径来改进推理的多目标框架。具体而言，我们引入用于多目标优化的非支配排序遗传算法 II，借助交叉和变异算子来增进推理解决方案的多样性。另外，我们提出一种凝聚-聚合机制来聚类并消除冗余路径，促进父节点间更优的信息共享，最终提升推理过程的效率和质量。在各类视觉语言和语言推理任务上的验证实验表明，与其他竞争基线相比，EoT 在推理性能和效率方面表现出色。我们的研究为 MLLMs 的启发式推理框架设计提供了全新视角。

> As multi-modal large language models (MLLMs) are increasingly applied to complex reasoning tasks, the diversity and quality of reasoning paths become crucial factors affecting their performance. Although current methods aim to enhance reasoning quality through path expansion, they often neglect the diversity of reasoning paths and effective information sharing, leading to local optima and inefficiency. To address these challenges, we propose Evolution of Thought (EoT), a multi-objective framework designed to improve reasoning by fostering both high-quality and diverse reasoning paths. Specifically, we introduce the Non-dominated Sorting Genetic Algorithm II for multi-objective optimization, utilizing crossover and mutation operators to promote greater diversity in reasoning solutions. Additionally, we propose a Condensation-Aggregation mechanism to cluster and eliminate redundant paths, facilitate improved information sharing among parent nodes, and ultimately enhance both the efficiency and quality of the reasoning process. Validation experiments on various vision-language and language reasoning tasks demonstrate that EoT achieves superior reasoning performance and efficiency compared to other competitive baselines. Our study provides a novel perspective on the design of heuristic reasoning frameworks for MLLMs.

[Arxiv](https://arxiv.org/abs/2412.07779)