# 群智能增强推理：密度驱动的LLM多智能体优化框架

发布时间：2025年05月21日

`LLM应用` `人工智能`

> Swarm Intelligence Enhanced Reasoning: A Density-Driven Framework for LLM-Based Multi-Agent Optimization

# 摘要

> 最近，研究者提出了多种方法，如思维链（CoT）提示和多智能体辩论（MAD），旨在进一步提升大型语言模型（LLMs）在推理场景中的复杂问题解决能力。然而，这些方法往往因缺乏寻找最优解的能力而难以应对复杂问题。群智（Swarm Intelligence）作为一种强大的工具，在传统优化领域一直被用于寻找最优解。为此，我们提出了一种基于智能体的群智（ASI）范式，将群智引入LLM的推理过程。在此范式下，我们将LLM推理建模为一个优化问题，并采用群智方案引导一组基于LLM的智能体协同搜索最优解。为了避免群智陷入局部最优，我们进一步开发了群智增强推理（SIER）框架，该框架采用基于密度的策略来提升推理能力。具体而言，我们通过核密度估计和非支配排序，同时优化解的质量和多样性。通过扩展推理路径的多样性，SIER能够更高效地增强解空间的探索能力。此外，我们采用分步质量评估来帮助智能体通过纠正低质量中间步骤来提升解的质量。然后，我们使用质量阈值动态控制探索的终止和候选步骤的选择，从而实现更灵活和高效的推理过程。大量实验表明...

> Recently, many approaches, such as Chain-of-Thought (CoT) prompting and Multi-Agent Debate (MAD), have been proposed to further enrich Large Language Models' (LLMs) complex problem-solving capacities in reasoning scenarios. However, these methods may fail to solve complex problems due to the lack of ability to find optimal solutions. Swarm Intelligence has been serving as a powerful tool for finding optima in the field of traditional optimization problems. To this end, we propose integrating swarm intelligence into the reasoning process by introducing a novel Agent-based Swarm Intelligence (ASI) paradigm. In this paradigm, we formulate LLM reasoning as an optimization problem and use a swarm intelligence scheme to guide a group of LLM-based agents in collaboratively searching for optimal solutions. To avoid swarm intelligence getting trapped in local optima, we further develop a Swarm Intelligence Enhancing Reasoning (SIER) framework, which develops a density-driven strategy to enhance the reasoning ability. To be specific, we propose to perform kernel density estimation and non-dominated sorting to optimize both solution quality and diversity simultaneously. In this case, SIER efficiently enhances solution space exploration through expanding the diversity of the reasoning path. Besides, a step-level quality evaluation is used to help agents improve solution quality by correcting low-quality intermediate steps. Then, we use quality thresholds to dynamically control the termination of exploration and the selection of candidate steps, enabling a more flexible and efficient reasoning process. Extensive experiments are ...

[Arxiv](https://arxiv.org/abs/2505.17115)