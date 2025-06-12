# Multiverse：你的语言模型默默决定了如何并行化生成与结果整合

发布时间：2025年06月11日

`LLM理论

这篇论文主要探讨了自回归大型语言模型（AR-LLMs）的并行生成能力，并提出了一种名为Multiverse的新模型架构。论文详细介绍了模型的设计、算法优化以及系统实现，并通过实验验证了其在性能和扩展性上的优势。这些内容涉及模型的理论改进和架构创新，属于LLM理论的范畴。`

> Multiverse: Your Language Models Secretly Decide How to Parallelize and Merge Generation

# 摘要

> 自回归大型语言模型（AR-LLMs）在序列生成中常展现出隐式并行性。受此启发，我们提出了Multiverse——一种全新的原生并行生成模型。Multiverse采用MapReduce范式，通过三个自动阶段完成生成：（i）Map阶段实现自适应任务分解，（ii）Process阶段执行并行子任务，（iii）Reduce阶段完成无损结果合成。我们通过数据、算法与系统的协同设计，构建了基于前沿AR-LLMs的Multiverse推理模型，实现了快速无缝迁移。从序列推理链出发，利用自动化LLM辅助管道将其转换为结构化训练数据，从而创建了Multiverse 1K，避免了人工标注成本。算法上，Multiverse注意力机制分离并行推理步骤，同时保持与因果注意力的兼容性，实现高效训练。系统上，Multiverse推理引擎支持并行推理，配备专用调度器，能够根据模型直接触发，在序列生成和并行生成之间动态切换。经过1K示例的3小时微调，Multiverse-32B成为唯一开源的非AR模型，性能与同规模领先AR-LLMs持平，AIME24 & 25得分分别为54%和46%。实验表明，Multiverse-32B展现了更优扩展性，在相同上下文长度下平均高出AR-LLMs 1.87%，实现不同批量大小下的最高2倍加速。我们已开源整个Multiverse生态系统，包括数据、模型权重、推理引擎、支持工具，以及完整的数据整理提示和详细的训练及评估指南。


> Autoregressive Large Language Models (AR-LLMs) frequently exhibit implicit parallelism in sequential generation. Inspired by this, we introduce Multiverse, a new generative model that enables natively parallel generation. Multiverse internalizes a MapReduce paradigm, generating automatically through three stages: (i) a Map stage for adaptive task decomposition, (ii) a Process stage for parallel subtask execution, and (iii) a Reduce stage for lossless result synthesis. Next, we build a real-world Multiverse reasoning model with co-design of data, algorithm, and system, enabling rapid and seamless transfer from frontier AR-LLMs. Starting from sequential reasoning chains, we create Multiverse 1K by converting them into structured training data using an automated LLM-assisted pipeline, avoiding costly human annotations. Algorithmically, we design Multiverse Attention to separate parallel reasoning steps while keeping compatibility with causal attention for efficient training. Systematically, we implement Multiverse Engine to enable parallel inference. It features a dedicated scheduler that dynamically switches between sequential and parallel generation, triggered directly by the model. After a 3-hour fine-tuning with 1K examples, our Multiverse-32B stands as the only open-sourced non-AR model achieving performance on par with leading AR-LLMs of the same scale, evidenced by AIME24 & 25 scores of 54% and 46%, respectively. Moreover, our budget control experiments show that Multiverse-32B exhibits superior scaling, outperforming AR-LLMs by 1.87% on average using the same context length. Such scaling further leads to practical efficiency gain, achieving up to 2x speedup across varying batch sizes. We have open-sourced the entire Multiverse ecosystem, including data, model weights, engine, supporting tools, as well as complete data curation prompts and detailed training and evaluation recipes.

[Arxiv](https://arxiv.org/abs/2506.09991)