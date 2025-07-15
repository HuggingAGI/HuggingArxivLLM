# GeLaCo：一种通过进化方法实现层压缩的技术

发布时间：2025年07月14日

`LLM理论` `模型压缩` `机器学习`

> GeLaCo: An Evolutionary Approach to Layer Compression

# 摘要

> 大型语言模型（LLM）在众多任务中表现卓越，但因计算需求巨大，部署和使用中面临重大障碍。模型压缩方法通过减小模型规模同时保持其能力，是缓解这些问题的重要手段。沿此思路，如结构化剪枝等有前景的方法，通常需要昂贵的实验搜索以寻找最优变体，且可能忽视更优方案。本文介绍GeLaCo，一种通过层坍缩实现LLM压缩的进化方法。我们的方法借助群体搜索和模块化相似性适应度函数，有效探索压缩解空间，该函数捕获注意力、前馈及隐藏状态表示。GeLaCo支持单目标和多目标进化压缩搜索，在压缩和质量轴上首次建立Pareto前沿。我们通过基于困惑度和生成评估，在基础模型和指令微调模型上评估GeLaCo解，超越现有最优替代方案。

> Large Language Models (LLM) have achieved remarkable performance across a large number of tasks, but face critical deployment and usage barriers due to substantial computational requirements. Model compression methods, which aim to reduce model size while preserving its capacity, are an important means to mitigate these issues. Promising approaches along these lines, such as structured pruning, typically require costly empirical search for optimal variants and may run the risk of ignoring better solutions. In this work we introduce GeLaCo, an evolutionary approach to LLM compression via layer collapse. Our approach supports an efficient exploration of the compression solution space via population-based search and a module-wise similarity fitness function capturing attention, feed-forward, and hidden state representations. GeLaCo also supports both single and multi-objective evolutionary compression search, establishing the first Pareto frontier along compression and quality axes. We evaluate GeLaCo solutions via both perplexity-based and generative evaluations over foundational and instruction-tuned models, outperforming state-of-the-art alternatives.

[Arxiv](https://arxiv.org/abs/2507.10059)