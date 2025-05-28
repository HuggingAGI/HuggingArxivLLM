# # 压缩LLM真的能“行动”吗？实证探究压缩LLM的智能体能力

发布时间：2025年05月25日

`Agent` `智能体` `智能体应用`

> Can Compressed LLMs Truly Act? An Empirical Evaluation of Agentic Capabilities in LLM Compression

# 摘要

> 后训练压缩显著降低了大型语言模型（LLMs）的计算和内存成本，使其能够实现资源高效的部署。然而，现有的压缩基准测试仅关注语言建模（如困惑度）和自然语言理解任务（如GLUE准确率），忽视了智能体能力——工作流、工具使用/函数调用、长上下文理解以及实际应用。我们引入了智能体压缩基准测试（ACBench），这是首个全面评估压缩对LLMs智能体能力影响的基准测试。ACBench涵盖（1）跨越4种能力的12项任务（例如，WorfBench用于工作流生成，Needle-in-Haystack用于长上下文检索），（2）量化（GPTQ，AWQ）和剪枝（Wanda，SparseGPT），以及（3）15种模型，包括小型（Gemma-2B）、标准（Qwen2.5 7B-32B）和蒸馏推理LLMs（DeepSeek-R1-Distill）。我们的实验揭示了压缩权衡：4位量化保留了工作流生成和工具使用（仅下降1%-3%），但降低了实际应用准确率（下降10%-15%）。我们引入了ERank、Top-k排名相关性和能量指标以系统化分析。ACBench为优化智能体场景下的LLM压缩提供了实用见解。代码可在https://github.com/pprp/ACBench获取。

> Post-training compression reduces the computational and memory costs of large language models (LLMs), enabling resource-efficient deployment. However, existing compression benchmarks only focus on language modeling (e.g., perplexity) and natural language understanding tasks (e.g., GLUE accuracy), ignoring the agentic capabilities - workflow, tool use/function call, long-context understanding and real-world application. We introduce the Agent Compression Benchmark (ACBench), the first comprehensive benchmark for evaluating how compression impacts LLMs' agentic abilities. ACBench spans (1) 12 tasks across 4 capabilities (e.g., WorfBench for workflow generation, Needle-in-Haystack for long-context retrieval), (2) quantization (GPTQ, AWQ) and pruning (Wanda, SparseGPT), and (3) 15 models, including small (Gemma-2B), standard (Qwen2.5 7B-32B), and distilled reasoning LLMs (DeepSeek-R1-Distill). Our experiments reveal compression tradeoffs: 4-bit quantization preserves workflow generation and tool use (1%-3% drop) but degrades real-world application accuracy by 10%-15%. We introduce ERank, Top-k Ranking Correlation and Energy to systematize analysis. ACBench provides actionable insights for optimizing LLM compression in agentic scenarios. The code can be found in https://github.com/pprp/ACBench.

[Arxiv](https://arxiv.org/abs/2505.19433)