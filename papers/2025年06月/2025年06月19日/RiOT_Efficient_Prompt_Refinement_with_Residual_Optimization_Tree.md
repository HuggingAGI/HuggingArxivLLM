# RiOT：残差优化树助力高效提示优化

发布时间：2025年06月19日

`LLM应用`

> RiOT: Efficient Prompt Refinement with Residual Optimization Tree

# 摘要

> 大型语言模型（LLMs）的最新进展凸显了其在多种任务中的潜力，但其性能仍高度依赖于提示设计。现有自动提示优化方法面临两大挑战：缺乏多样性限制了创新探索，而语义漂移则会导致跨任务性能下降。为此，我们提出了一种全新的自动提示优化框架——残差优化树（RiOT）。RiOT通过文本梯度迭代优化提示，每一步生成多个语义多样的候选提示，并利用困惑度选择最优提示。同时，RiOT引入了文本残差连接，通过在优化过程中选择性保留有益内容来缓解语义漂移。其树状结构设计确保了优化过程的高效性、可扩展性和灵活性。在涵盖常识、数学、逻辑、时间和语义推理的五项基准测试中，RiOT不仅超越了以往的提示优化方法，还优于手动提示设计，展现了显著的优势。

> Recent advancements in large language models (LLMs) have highlighted their potential across a variety of tasks, but their performance still heavily relies on the design of effective prompts. Existing methods for automatic prompt optimization face two challenges: lack of diversity, limiting the exploration of valuable and innovative directions and semantic drift, where optimizations for one task can degrade performance in others. To address these issues, we propose Residual Optimization Tree (RiOT), a novel framework for automatic prompt optimization. RiOT iteratively refines prompts through text gradients, generating multiple semantically diverse candidates at each step, and selects the best prompt using perplexity. Additionally, RiOT incorporates the text residual connection to mitigate semantic drift by selectively retaining beneficial content across optimization iterations. A tree structure efficiently manages the optimization process, ensuring scalability and flexibility. Extensive experiments across five benchmarks, covering commonsense, mathematical, logical, temporal, and semantic reasoning, demonstrate that RiOT outperforms both previous prompt optimization methods and manual prompting.

[Arxiv](https://arxiv.org/abs/2506.16389)