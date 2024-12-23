# HPC-Coder-V2：对跨低资源并行语言的代码大型语言模型展开研究

发布时间：2024年12月19日

`LLM应用` `高性能计算` `软件开发`

> HPC-Coder-V2: Studying Code LLMs Across Low-Resource Parallel Languages

# 摘要

> 大型语言模型（LLM）打造的编码工具作为软件开发助手成果斐然，不过它们通常是为通用编程任务而设计，在高性能计算等更专业的领域表现欠佳。为这些领域打造专门的模型和工具，对于在 HPC 等领域获取 LLM 的优势至关重要。尽管此前已有针对 HPC 特定模型的探索，但 LLM 仍难以生成并行代码，究竟是什么障碍在制约这些 LLM 以及该如何克服，都尚不明确。在本研究中，我们沿着专门的 HPC LLM 微调的多个维度展开深入探究，以更好地明晰挑战所在。基于我们的发现，我们对一个专门的 HPC LLM 进行了微调与评估，该模型被证实是迄今用于并行代码生成的表现最佳的开源代码 LLM。

> Large Language Model (LLM) based coding tools have been tremendously successful as software development assistants, yet they are often designed for general purpose programming tasks and perform poorly for more specialized domains such as high performance computing. Creating specialized models and tools for these domains is crucial towards gaining the benefits of LLMs in areas such as HPC. While previous work has explored HPC-specific models, LLMs still struggle to generate parallel code and it is not at all clear what hurdles are still holding back these LLMs and what must be done to overcome them. In this work, we conduct an in-depth study along the many axes of fine-tuning a specialized HPC LLM in order to better understand the challenges. Based on our findings we fine-tune and evaluate a specialized HPC LLM that is shown to be the best performing open-source code LLM for parallel code generation to date.

[Arxiv](https://arxiv.org/abs/2412.15178)