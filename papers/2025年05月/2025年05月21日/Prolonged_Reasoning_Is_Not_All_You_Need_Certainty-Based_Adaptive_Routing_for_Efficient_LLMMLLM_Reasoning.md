# 冗长的推理并非全部所需：基于置信度的自适应路由机制，助力高效LLM/MLLM推理

发布时间：2025年05月21日

`LLM应用

摘要讨论了大型语言模型（LLMs）和多模态模型（MLLMs）在推理任务中的表现，并提出了一种自适应推理框架（CAR）来优化推理过程，以提高准确性和效率。这属于模型的应用层面，旨在改进模型在实际任务中的表现。因此，这篇论文被归类为LLM应用。` `视觉问答` `信息抽取`

> Prolonged Reasoning Is Not All You Need: Certainty-Based Adaptive Routing for Efficient LLM/MLLM Reasoning

# 摘要

> # 摘要
近期推理技术的突破显著提升了大型语言模型（LLMs）和多模态大型语言模型（MLLMs）在各类任务中的表现。然而，过度依赖思维链（CoT）推理不仅会损害模型性能，还会产生冗长的输出，降低效率。我们的研究表明，延长推理时间并非总能提升准确性，甚至可能在简单任务中导致性能下降。为解决这一问题，我们提出了一种基于确定性的自适应推理框架（CAR），该框架可根据模型困惑度动态切换短答案与长篇推理模式。CAR首先生成一个简短答案并评估其困惑度，仅在模型表现出低信心（即高困惑度）时触发推理机制。在多模态VQA/KIE基准测试和文本推理数据集上的实验表明，CAR在准确性和效率之间实现了最优平衡，其性能优于单纯的短答案和长篇推理方法。

> Recent advancements in reasoning have significantly enhanced the capabilities of Large Language Models (LLMs) and Multimodal Large Language Models (MLLMs) across diverse tasks. However, excessive reliance on chain-of-thought (CoT) reasoning can impair model performance and brings unnecessarily lengthened outputs, reducing efficiency. Our work reveals that prolonged reasoning does not universally improve accuracy and even degrade performance on simpler tasks. To address this, we propose Certainty-based Adaptive Reasoning (CAR), a novel framework that dynamically switches between short answers and long-form reasoning based on the model perplexity. CAR first generates a short answer and evaluates its perplexity, triggering reasoning only when the model exhibits low confidence (i.e., high perplexity). Experiments across diverse multimodal VQA/KIE benchmarks and text reasoning datasets show that CAR outperforms both short-answer and long-form reasoning approaches, striking an optimal balance between accuracy and efficiency.

[Arxiv](https://arxiv.org/abs/2505.15154)