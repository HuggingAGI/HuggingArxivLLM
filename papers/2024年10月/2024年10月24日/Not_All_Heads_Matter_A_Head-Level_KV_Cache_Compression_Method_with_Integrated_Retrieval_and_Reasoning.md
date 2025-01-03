# 并非所有头都重要：一种集成检索与推理的头级别KV缓存压缩方案

发布时间：2024年10月24日

`LLM理论

理由：这篇论文主要讨论了KV缓存技术在提升大型语言模型（LLM）计算效率中的应用，并提出了新的压缩方法（HeadKV和HeadKV-R2）来优化内存使用。这些方法涉及对注意力头的操作和上下文推理能力的估计，属于对LLM内部机制和理论的研究，旨在改进模型的计算效率和性能。因此，这篇论文应归类为LLM理论。` `问答系统`

> Not All Heads Matter: A Head-Level KV Cache Compression Method with Integrated Retrieval and Reasoning

# 摘要

> # 关键值（KV）缓存
KV缓存是提升LLMs计算效率的常用技术，但其内存开销随输入长度迅速增加。研究表明，并非所有标记对文本生成都同等重要，因此提出了层级KV缓存压缩方法，以选择性保留关键信息。我们注意到注意力头在生成中的独特作用，提出了头级KV缓存压缩方法HeadKV及其改进版HeadKV-R2，后者利用新颖的上下文推理能力估计进行压缩。我们的方法在单个头的层面上操作，评估它们在需要检索和推理能力的上下文问答任务中的重要性。在多个基准测试（如LongBench、LooGLE）、模型架构（如Llama-3-8B-Instruct、Mistral-7B-Instruct）和长上下文能力测试中的广泛实验表明，我们的头级KV缓存压缩在低资源设置（KV大小=64和128）中显著优于强基线。值得注意的是，我们的方法仅保留1.5%的KV缓存，却在上下文问答基准测试中达到了完整KV缓存性能的97%。

> Key-Value (KV) caching is a common technique to enhance the computational efficiency of Large Language Models (LLMs), but its memory overhead grows rapidly with input length. Prior work has shown that not all tokens are equally important for text generation, proposing layer-level KV cache compression to selectively retain key information. Recognizing the distinct roles of attention heads in generation, we propose HeadKV, a head-level KV cache compression method, and HeadKV-R2, which leverages a novel contextual reasoning ability estimation for compression. Our approach operates at the level of individual heads, estimating their importance for contextual QA tasks that require both retrieval and reasoning capabilities. Extensive experiments across diverse benchmarks (LongBench, LooGLE), model architectures (e.g., Llama-3-8B-Instruct, Mistral-7B-Instruct), and long-context abilities tests demonstrate that our head-level KV cache compression significantly outperforms strong baselines, particularly in low-resource settings (KV size = 64 & 128). Notably, our method retains just 1.5% of the KV cache while achieving 97% of the performance of the full KV cache on the contextual question answering benchmark.

[Arxiv](https://arxiv.org/abs/2410.19258)