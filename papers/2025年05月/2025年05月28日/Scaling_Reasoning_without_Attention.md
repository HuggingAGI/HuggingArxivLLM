# 无注意力机制的推理能力扩展

发布时间：2025年05月28日

`LLM理论

摘要中提到论文讨论了大型语言模型的架构改进和训练策略，属于模型理论层面的研究。` `人工智能` `大规模模型`

> Scaling Reasoning without Attention

# 摘要

> 大型语言模型（LLMs）在复杂推理任务中取得了显著进展，但仍受限于两大核心挑战：因依赖Transformer而导致的架构低效，以及缺乏针对高难度领域的结构化微调。我们推出\ourmodel，一款无注意力机制的语言模型，通过架构和数据为中心的创新，同时解决这两个问题。基于Mamba-2的状态空间双层（SSD），我们的模型无需自注意力和键值缓存，实现固定内存、常数时间推理。为了训练其复杂推理能力，我们提出了一种基于	extsc{PromptCoT}合成范式的两阶段课程微调策略，通过抽象概念选择和理由引导生成，生成具有教学结构的问题。在基准评估中，\ourmodel-7B超越了同规模的强Transformer和混合模型，甚至在AIME 24、AIME 25和Livecodebench上分别以2.6%、0.6%和3.0%的优势超过了规模大得多的Gemma3-27B。这些结果凸显了状态空间模型作为高效且可扩展的注意力架构替代方案，在高容量推理中的潜力。

> Large language models (LLMs) have made significant advances in complex reasoning tasks, yet they remain bottlenecked by two core challenges: architectural inefficiency due to reliance on Transformers, and a lack of structured fine-tuning for high-difficulty domains. We introduce \ourmodel, an attention-free language model that addresses both issues through architectural and data-centric innovations. Built on the state space dual (SSD) layers of Mamba-2, our model eliminates the need for self-attention and key-value caching, enabling fixed-memory, constant-time inference. To train it for complex reasoning, we propose a two-phase curriculum fine-tuning strategy based on the \textsc{PromptCoT} synthesis paradigm, which generates pedagogically structured problems via abstract concept selection and rationale-guided generation. On benchmark evaluations, \ourmodel-7B outperforms strong Transformer and hybrid models of comparable scale, and even surpasses the much larger Gemma3-27B by 2.6\% on AIME 24, 0.6\% on AIME 25, and 3.0\% on Livecodebench. These results highlight the potential of state space models as efficient and scalable alternatives to attention-based architectures for high-capacity reasoning.

[Arxiv](https://arxiv.org/abs/2505.22425)