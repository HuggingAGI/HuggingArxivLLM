# 信息素驱动的推理路径优化学习

发布时间：2025年01月31日

`LLM应用

理由：这篇论文提出了一种新的算法（ACO-ToT），将蚁群优化（ACO）与大型语言模型（LLMs）结合，用于解决复杂问题的推理路径探索。该方法通过结合LLMs和生物启发的集体搜索机制，显著提升了推理能力。这属于LLM在实际应用中的创新和改进，因此归类为LLM应用。` `人工智能` `优化算法`

> Pheromone-based Learning of Optimal Reasoning Paths

# 摘要

> 大型语言模型（LLMs）通过链式思维提示展现了强大的推理能力，但面对复杂问题时，寻找有效的推理方法仍是一大挑战。我们提出了一种名为蚁群优化引导的思维树（ACO-ToT）的新算法，它将ACO与LLMs结合，高效地探索复杂问题的最优推理路径。受神经系统赫布学习的启发，该方法利用一组经过精细调优的LLM“蚂蚁”在中心化的思维树中遍历并留下信息素轨迹，每只蚂蚁的移动由信息素轨迹和其专业知识的加权组合决定。算法通过专家混合评分函数评估推理路径，并在迭代中通过信息素强化有效路径。在GSM8K、ARC-Challenge和MATH三个推理任务上的实验表明，ACO-ToT显著优于现有链式思维优化方法，证明了将生物启发的集体搜索机制融入LLM推理能大幅提升推理能力。

> Large Language Models (LLMs) have demonstrated remarkable reasoning capabilities through chain-of-thought prompting, yet discovering effective reasoning methods for complex problems remains challenging due to the vast space of possible intermediate steps. We introduce Ant Colony Optimization-guided Tree of Thought (ACO-ToT), a novel algorithm that combines ACO with LLMs to discover optimal reasoning paths for complex problems efficiently. Drawing inspiration from Hebbian learning in neurological systems, our method employs a collection of distinctly fine-tuned LLM "ants" to traverse and lay pheromone trails through a centralized tree of thought, with each ant's movement governed by a weighted combination of existing pheromone trails and its own specialized expertise. The algorithm evaluates complete reasoning paths using a mixture-of-experts-based scoring function, with pheromones reinforcing productive reasoning paths across iterations. Experiments on three challenging reasoning tasks (GSM8K, ARC-Challenge, and MATH) demonstrate that ACO-ToT performs significantly better than existing chain-of-thought optimization approaches, suggesting that incorporating biologically inspired collective search mechanisms into LLM inference can substantially enhance reasoning capabilities.

[Arxiv](https://arxiv.org/abs/2501.19278)