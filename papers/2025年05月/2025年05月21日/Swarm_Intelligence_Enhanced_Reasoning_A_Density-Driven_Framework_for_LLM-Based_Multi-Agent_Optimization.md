# 群智增强推理：基于密度驱动的LLM多智能体优化框架

发布时间：2025年05月21日

`Agent` `群体智能` `优化算法`

> Swarm Intelligence Enhanced Reasoning: A Density-Driven Framework for LLM-Based Multi-Agent Optimization

# 摘要

> # 摘要
近期，许多方法如CoT提示和MAD被提出，旨在进一步提升大语言模型在推理任务中的复杂问题解决能力。然而，这些方法可能因无法找到最优解而无法解决复杂问题。群体智能在传统优化问题中一直是寻找最优解的强大工具。为此，我们提出了一种基于代理的群体智能（ASI）范式，将群体智能整合到推理过程中。在此范式下，我们将LLM推理建模为一个优化问题，并采用群体智能方案引导一组基于LLM的代理协作搜索最优解。为了避免群体智能陷入局部最优，我们进一步开发了增强推理的群体智能（SIER）框架，该框架采用基于密度的策略来提升推理能力。具体而言，我们提出通过核密度估计和非支配排序同时优化解的质量和多样性。这样，SIER通过扩展推理路径的多样性，有效增强了解空间的探索能力。此外，采用分步质量评估帮助代理通过纠正低质量中间步骤来提升解的质量。然后，我们使用质量阈值动态控制探索终止和候选步骤选择，使推理过程更加灵活高效。通过广泛的实验……

> Recently, many approaches, such as Chain-of-Thought (CoT) prompting and Multi-Agent Debate (MAD), have been proposed to further enrich Large Language Models' (LLMs) complex problem-solving capacities in reasoning scenarios. However, these methods may fail to solve complex problems due to the lack of ability to find optimal solutions. Swarm Intelligence has been serving as a powerful tool for finding optima in the field of traditional optimization problems. To this end, we propose integrating swarm intelligence into the reasoning process by introducing a novel Agent-based Swarm Intelligence (ASI) paradigm. In this paradigm, we formulate LLM reasoning as an optimization problem and use a swarm intelligence scheme to guide a group of LLM-based agents in collaboratively searching for optimal solutions. To avoid swarm intelligence getting trapped in local optima, we further develop a Swarm Intelligence Enhancing Reasoning (SIER) framework, which develops a density-driven strategy to enhance the reasoning ability. To be specific, we propose to perform kernel density estimation and non-dominated sorting to optimize both solution quality and diversity simultaneously. In this case, SIER efficiently enhances solution space exploration through expanding the diversity of the reasoning path. Besides, a step-level quality evaluation is used to help agents improve solution quality by correcting low-quality intermediate steps. Then, we use quality thresholds to dynamically control the termination of exploration and the selection of candidate steps, enabling a more flexible and efficient reasoning process. Extensive experiments are ...

[Arxiv](https://arxiv.org/abs/2505.17115)