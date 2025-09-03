# ReCode：借助细粒度检索增强生成改进基于LLM的代码修复

发布时间：2025年09月02日

`RAG` `工业与制造`

> ReCode: Improving LLM-based Code Repair with Fine-Grained Retrieval-Augmented Generation

# 摘要

> 大型语言模型（LLMs）的最新进展在代码生成、自动化程序修复等代码相关任务中展现出了惊人能力。尽管表现亮眼，现有代码修复方法大多面临训练成本高昂或推理计算开销大的问题。检索增强生成（RAG）凭借高效的上下文学习范式，成为了一种更具可扩展性的替代方案。但传统检索策略多依赖整体的代码-文本嵌入，难以捕捉代码的结构细节，从而造成检索质量不理想。为解决这些问题，我们提出了ReCode——一个细粒度检索增强上下文学习框架，专为精准高效的代码修复设计。具体来说，ReCode包含两项核心创新：（1）算法感知检索策略，通过初步预测算法类型来缩小搜索范围；（2）模块化双编码器架构，将代码与文本输入分开处理，实现输入与检索上下文间的细粒度语义匹配。此外，我们构建了新基准RACodeBench，其数据来源于真实用户提交的错误代码，能够解决合成基准的不足并支持真实场景的评估。在RACodeBench和竞赛编程数据集上的实验结果显示，ReCode不仅修复准确率更高，推理成本也大幅降低，充分体现了其在实际代码修复场景中的实用价值。

> Recent advances in large language models (LLMs) have demonstrated impressive capabilities in code-related tasks, such as code generation and automated program repair. Despite their promising performance, most existing approaches for code repair suffer from high training costs or computationally expensive inference. Retrieval-augmented generation (RAG), with its efficient in-context learning paradigm, offers a more scalable alternative. However, conventional retrieval strategies, which are often based on holistic code-text embeddings, fail to capture the structural intricacies of code, resulting in suboptimal retrieval quality. To address the above limitations, we propose ReCode, a fine-grained retrieval-augmented in-context learning framework designed for accurate and efficient code repair. Specifically, ReCode introduces two key innovations: (1) an algorithm-aware retrieval strategy that narrows the search space using preliminary algorithm type predictions; and (2) a modular dual-encoder architecture that separately processes code and textual inputs, enabling fine-grained semantic matching between input and retrieved contexts. Furthermore, we propose RACodeBench, a new benchmark constructed from real-world user-submitted buggy code, which addresses the limitations of synthetic benchmarks and supports realistic evaluation. Experimental results on RACodeBench and competitive programming datasets demonstrate that ReCode achieves higher repair accuracy with significantly reduced inference cost, highlighting its practical value for real-world code repair scenarios.

[Arxiv](https://arxiv.org/abs/2509.02330)