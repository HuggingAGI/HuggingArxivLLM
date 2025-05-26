# # 斑马-llama：迈向超高效率的混合模型

发布时间：2025年05月22日

`LLM理论` `人工智能`

> Zebra-Llama: Towards Extremely Efficient Hybrid Models

# 摘要

> 随着大型语言模型（LLMs）在多样化应用中的部署需求日益增长，提升其推理效率对于实现可持续和民主化的访问至关重要。然而，为了满足新的用户特定需求而重新训练LLMs在经济和环境上都是不可持续的。本研究提出了一种实用且可扩展的替代方案：通过现有预训练模型构建高效混合语言模型。我们的方法Zebra-Llama通过结合状态空间模型（SSMs）和多头潜在注意力（MLA）层，并使用优化的初始化和后训练管道，高效地将知识从预训练的Transformers中迁移，推出了一系列10亿、30亿和80亿参数的混合模型。Zebra-Llama仅使用70亿到110亿的训练标记（与预训练所需的数万亿标记相比），并采用80亿参数的教师模型，实现了与Transformer相当的准确性，同时接近SSM的效率。此外，Zebra-Llama大幅减少了键值缓存的大小——分别降至原大小的3.9%、2%和2.73%（针对10亿、30亿和80亿参数的变体），同时在LM Harness任务上的零样本性能平均保留了100%、100%和>97%。与MambaInLLaMA、X-EcoMLA、Minitron和Llamba等模型相比，Zebra-Llama在使用显著更少的标记、更小的教师模型和大幅减少的键值缓存内存的情况下，始终提供具有竞争力或更优的准确性。值得注意的是，Zebra-Llama-8B在使用8倍少的训练标记、超过12倍小的键值缓存和更小的教师模型（80亿参数 vs. 150亿参数）的情况下，其在少样本准确性的表现比Minitron-8B高出7%。它还实现了比MambaInLlama在32k上下文长度内2.6到3.8倍更高的吞吐量（每秒标记数）。我们将在论文被接受后发布代码和模型检查点。

> With the growing demand for deploying large language models (LLMs) across diverse applications, improving their inference efficiency is crucial for sustainable and democratized access. However, retraining LLMs to meet new user-specific requirements is prohibitively expensive and environmentally unsustainable. In this work, we propose a practical and scalable alternative: composing efficient hybrid language models from existing pre-trained models. Our approach, Zebra-Llama, introduces a family of 1B, 3B, and 8B hybrid models by combining State Space Models (SSMs) and Multi-head Latent Attention (MLA) layers, using a refined initialization and post-training pipeline to efficiently transfer knowledge from pre-trained Transformers. Zebra-Llama achieves Transformer-level accuracy with near-SSM efficiency using only 7-11B training tokens (compared to trillions of tokens required for pre-training) and an 8B teacher. Moreover, Zebra-Llama dramatically reduces KV cache size -down to 3.9%, 2%, and 2.73% of the original for the 1B, 3B, and 8B variants, respectively-while preserving 100%, 100%, and >97% of average zero-shot performance on LM Harness tasks. Compared to models like MambaInLLaMA, X-EcoMLA, Minitron, and Llamba, Zebra-Llama consistently delivers competitive or superior accuracy while using significantly fewer tokens, smaller teachers, and vastly reduced KV cache memory. Notably, Zebra-Llama-8B surpasses Minitron-8B in few-shot accuracy by 7% while using 8x fewer training tokens, over 12x smaller KV cache, and a smaller teacher (8B vs. 15B). It also achieves 2.6x-3.8x higher throughput (tokens/s) than MambaInLlama up to a 32k context length. We will release code and model checkpoints upon acceptance.

[Arxiv](https://arxiv.org/abs/2505.17272)