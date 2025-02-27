# 多-LLM 协作搜索：解决复杂问题的新方法

发布时间：2025年02月26日

`LLM应用

摘要中提到的论文提出了一种新的方法（MoSA）来提升大型语言模型在复杂推理任务中的表现，属于应用层面的创新。` `多智能体`

> Multi-LLM Collaborative Search for Complex Problem Solving

# 摘要

> 大型语言模型（LLMs）在处理复杂推理任务时常常力不从心，主要由于其在应对广袤的推理空间和自然语言固有模糊性方面的局限性。我们提出了一种名为混合搜索代理（MoSA）的新型范式，通过整合多个LLMs的集体专长，提升基于搜索的推理能力。MoSA结合独立探索与迭代优化，整合了来自多个LLMs的多样化推理路径，从而克服了单一模型方法的局限性。基于蒙特卡洛树搜索（MCTS）作为核心框架，MoSA使多个代理能够提出并聚合推理步骤，从而提高了推理的准确性。我们在四个推理基准上的全面评估表明，MoSA在复杂数学推理和常识推理等任务中，相较于单一代理和其他多代理基线，表现出一致的性能提升。

> Large language models (LLMs) often struggle with complex reasoning tasks due to their limitations in addressing the vast reasoning space and inherent ambiguities of natural language. We propose the Mixture-of-Search-Agents (MoSA) paradigm, a novel approach leveraging the collective expertise of multiple LLMs to enhance search-based reasoning. MoSA integrates diverse reasoning pathways by combining independent exploration with iterative refinement among LLMs, mitigating the limitations of single-model approaches. Using Monte Carlo Tree Search (MCTS) as a backbone, MoSA enables multiple agents to propose and aggregate reasoning steps, resulting in improved accuracy. Our comprehensive evaluation across four reasoning benchmarks demonstrates MoSA's consistent performance improvements over single-agent and other multi-agent baselines, particularly in complex mathematical and commonsense reasoning tasks.

[Arxiv](https://arxiv.org/abs/2502.18873)