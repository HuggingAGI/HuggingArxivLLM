# CALM：算法与语言模型协同进化实现自动启发式设计

发布时间：2025年05月18日

`LLM应用` `计算机科学` `人工智能`

> CALM: Co-evolution of Algorithms and Language Model for Automatic Heuristic Design

# 摘要

> 解决复杂的优化问题，传统上往往依赖于专家精心设计的启发式方法，这些方法通常是通过大量试错实验打磨而成。近期研究表明，将大型语言模型（LLMs）嵌入到精心设计的进化搜索框架中，能够以远低于传统方法的成本，自主发现高性能的启发式策略。然而，现有的方法主要依赖于语言引导，即通过调整提示生成过程来控制启发式方法的进化方向，而没有对底层的LLM进行适应性调整。我们提出了一种结合语言引导和数值引导的混合框架，其中数值引导通过基于生成启发式方法质量的强化学习对LLM进行微调来实现。这种联合优化使LLM能够与搜索过程共同进化。我们的方法在各种优化任务中均超越了现有的最先进（SOTA）基线，仅使用单个24GB GPU运行，采用7B模型并结合INT4量化技术。即使与那些依赖更强大API模型的纯语言引导方法相比，我们的方法也表现出更优的性能。


> Tackling complex optimization problems often relies on expert-designed heuristics, typically crafted through extensive trial and error. Recent advances demonstrate that large language models (LLMs), when integrated into well-designed evolutionary search frameworks, can autonomously discover high-performing heuristics at a fraction of the traditional cost. However, existing approaches predominantly rely on verbal guidance, i.e., manipulating the prompt generation process, to steer the evolution of heuristics, without adapting the underlying LLM. We propose a hybrid framework that combines verbal and numerical guidance, the latter achieved by fine-tuning the LLM via reinforcement learning based on the quality of generated heuristics. This joint optimization allows the LLM to co-evolve with the search process. Our method outperforms state-of-the-art (SOTA) baselines across various optimization tasks, running locally on a single 24GB GPU using a 7B model with INT4 quantization. It surpasses methods that rely solely on verbal guidance, even when those use significantly more powerful API-based models.

[Arxiv](https://arxiv.org/abs/2505.12285)