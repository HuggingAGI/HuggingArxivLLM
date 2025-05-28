# 推理型LLMs：漫无目的的解决方案探索者

发布时间：2025年05月26日

`LLM理论

理由：这篇论文探讨了大型语言模型在推理过程中的系统性问题解决能力，分析了现有模型在推理过程中的不足，并提出了新的评估指标和工具。这属于对大型语言模型本身的理论研究，因此归类为LLM理论。` `人工智能`

> Reasoning LLMs are Wandering Solution Explorers

# 摘要

> 大型语言模型 (LLMs) 通过测试时计算 (TTC) 技术（如思维链提示和树状推理）展现出令人印象深刻的推理能力。然而，我们认为当前的推理型大语言模型 (RLLMs) 缺乏系统性探索解决方案的能力。本文定义了系统性问题解决的内涵，并揭示了推理型大语言模型更像是漫无目的地游荡者，而非系统性的探索者。通过对多个先进 LLM 的定性和定量分析，我们发现持续存在的问题：无效推理步骤、重复探索、幻觉或不忠实的结论等等。我们的研究发现表明，当前模型在简单任务上表现优异，但随着复杂性的增加，性能会急剧下降。基于这些发现，我们提倡引入新的评估指标和工具，不仅要评估最终输出，还要评估推理过程本身的结构。

> Large Language Models (LLMs) have demonstrated impressive reasoning abilities through test-time computation (TTC) techniques such as chain-of-thought prompting and tree-based reasoning. However, we argue that current reasoning LLMs (RLLMs) lack the ability to systematically explore the solution space. This paper formalizes what constitutes systematic problem solving and identifies common failure modes that reveal reasoning LLMs to be wanderers rather than systematic explorers. Through qualitative and quantitative analysis across multiple state-of-the-art LLMs, we uncover persistent issues: invalid reasoning steps, redundant explorations, hallucinated or unfaithful conclusions, and so on. Our findings suggest that current models' performance can appear to be competent on simple tasks yet degrade sharply as complexity increases. Based on the findings, we advocate for new metrics and tools that evaluate not just final outputs but the structure of the reasoning process itself.

[Arxiv](https://arxiv.org/abs/2505.20296)