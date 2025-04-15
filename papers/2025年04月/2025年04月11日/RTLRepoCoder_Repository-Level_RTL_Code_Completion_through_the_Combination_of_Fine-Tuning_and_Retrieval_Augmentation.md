# RTLRepoCoder：结合微调和检索增强实现仓库级 RTL 代码补全

发布时间：2025年04月11日

`LLM应用` `硬件设计` `电子设计自动化`

> RTLRepoCoder: Repository-Level RTL Code Completion through the Combination of Fine-Tuning and Retrieval Augmentation

# 摘要

> 作为现代硬件设计的重要组成部分，手动编写寄存器传输级（RTL）代码（如Verilog）往往耗时费力。随着大型语言模型（LLMs）的巨大成功，研究人员开始探索利用LLMs生成RTL代码。然而，当前研究主要集中在生成简单的单个模块，无法满足实际需求。实际上，由于处理长上下文RTL代码和复杂跨文件依赖的挑战，现有解决方案无法应对实际硬件开发中的大规模Verilog仓库。作为首个专门针对大规模RTL开发适配LLMs的尝试，我们提出RTLRepoCoder，这是一个开创性的解决方案，通过特定的微调和检索增强生成（RAG）实现仓库级Verilog代码补全。我们使用来自真实世界的开源Verilog仓库，结合扩展的上下文大小，进行领域特定的微调。优化的RAG系统通过检索相关代码片段提高了输入上下文的信息密度。针对RAG进行了专门的优化，包括嵌入模型、跨文件上下文分割策略和块大小。我们的解决方案在公共基准上实现了最先进的性能，在编辑相似性和精确匹配率上显著超越GPT-4和先进的领域特定LLMs。全面的实验展示了我们方法的显著有效性，并为未来工作提供了见解。

> As an essential part of modern hardware design, manually writing Register Transfer Level (RTL) code such as Verilog is often labor-intensive. Following the tremendous success of large language models (LLMs), researchers have begun to explore utilizing LLMs for generating RTL code. However, current studies primarily focus on generating simple single modules, which can not meet the demands in real world. In fact, due to challenges in managing long-context RTL code and complex cross-file dependencies, existing solutions cannot handle large-scale Verilog repositories in practical hardware development. As the first endeavor to exclusively adapt LLMs for large-scale RTL development, we propose RTLRepoCoder, a groundbreaking solution that incorporates specific fine-tuning and Retrieval-Augmented Generation (RAG) for repository-level Verilog code completion. Open-source Verilog repositories from the real world, along with an extended context size, are used for domain-specific fine-tuning. The optimized RAG system improves the information density of the input context by retrieving relevant code snippets. Tailored optimizations for RAG are carried out, including the embedding model, the cross-file context splitting strategy, and the chunk size. Our solution achieves state-of-the-art performance on public benchmark, significantly surpassing GPT-4 and advanced domain-specific LLMs on Edit Similarity and Exact Match rate. Comprehensive experiments demonstrate the remarkable effectiveness of our approach and offer insights for future work.

[Arxiv](https://arxiv.org/abs/2504.08862)