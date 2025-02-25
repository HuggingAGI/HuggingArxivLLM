# BioMaze：评测与优化大型语言模型的生物通路推理能力

发布时间：2025年02月23日

`LLM应用`

> BioMaze: Benchmarking and Enhancing Large Language Models for Biological Pathway Reasoning

# 摘要

> 大型语言模型（LLMs）在生物领域的应用引起了广泛关注，但其在复杂生物系统（如信号通路）中的推理能力仍有待深入研究，这对预测生物现象、提出科学假设和设计实验具有重要意义。本研究聚焦于LLMs在路径推理方面的潜力，推出了BioMaze数据集——一个包含5100个复杂路径问题的集合，这些问题均源自真实科研场景，涵盖了自然动态变化、外界干扰、额外干预条件以及多尺度研究目标等多种生物学情境。通过评估CoT和图增强推理等方法，我们发现LLMs在路径推理任务中表现欠佳，尤其在处理扰动系统时更具挑战性。为应对这一难题，我们开发了PathSeeker——一种基于交互式子图导航的LLM代理，通过增强推理能力，为科学研究者提供了一种更高效且科学化的复杂生物系统处理方案。BioMaze数据集和相关代码已在GitHub平台开放获取：https://github.com/zhao-ht/BioMaze。

> The applications of large language models (LLMs) in various biological domains have been explored recently, but their reasoning ability in complex biological systems, such as pathways, remains underexplored, which is crucial for predicting biological phenomena, formulating hypotheses, and designing experiments. This work explores the potential of LLMs in pathway reasoning. We introduce BioMaze, a dataset with 5.1K complex pathway problems derived from real research, covering various biological contexts including natural dynamic changes, disturbances, additional intervention conditions, and multi-scale research targets. Our evaluation of methods such as CoT and graph-augmented reasoning, shows that LLMs struggle with pathway reasoning, especially in perturbed systems. To address this, we propose PathSeeker, an LLM agent that enhances reasoning through interactive subgraph-based navigation, enabling a more effective approach to handling the complexities of biological systems in a scientifically aligned manner. The dataset and code are available at https://github.com/zhao-ht/BioMaze.

[Arxiv](https://arxiv.org/abs/2502.16660)