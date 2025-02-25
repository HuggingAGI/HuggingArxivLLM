# R³Mem：通过可逆压缩实现记忆保留与检索的无缝连接

发布时间：2025年02月21日

`LLM应用

摘要讨论了内存设计在提升大型语言模型性能中的应用，特别是通过R$^3$Mem内存网络优化信息检索与存储，应用于对话代理等任务，属于模型的实际应用。` `信息检索系统`

> R$^3$Mem: Bridging Memory Retention and Retrieval via Reversible Compression

# 摘要

> 内存对提升大型语言模型（LLMs）的实际应用性能至关重要。现有解决方案在性能上面临权衡：显式内存设计依赖外部存储，导致复杂管理和存储开销；隐式内存设计通过参数存储信息，但可靠检索面临挑战。本文提出了一种名为R$^3$Mem的内存网络，通过可逆上下文压缩优化信息的保留与检索。具体而言，R$^3$Mem利用虚拟内存令牌压缩并编码无限长的历史记录，并借助分层压缩策略，从文档级到实体级细化信息，以实现跨粒度的高效融合。在检索过程中，R$^3$Mem采用可逆架构，通过反向调用模型并利用压缩信息重建原始数据。该方法通过参数高效的微调实现，可无缝集成到任何基于Transformer的模型中。实验结果表明，R$^3$Mem在长上下文语言建模和检索增强生成任务中达到了最先进的性能。在对话代理等长期交互任务中，其表现显著优于传统内存模块，展现了其在下一代检索系统中的巨大潜力。

> Memory plays a key role in enhancing LLMs' performance when deployed to real-world applications. Existing solutions face trade-offs: explicit memory designs based on external storage require complex management and incur storage overhead, while implicit memory designs that store information via parameters struggle with reliable retrieval. In this paper, we propose R$^3$Mem, a memory network that optimizes both information Retention and Retrieval through Reversible context compression. Specifically, R$^3$Mem employs virtual memory tokens to compress and encode infinitely long histories, further enhanced by a hierarchical compression strategy that refines information from document- to entity-level for improved assimilation across granularities. For retrieval, R$^3$Mem employs a reversible architecture, reconstructing raw data by invoking the model backward with compressed information. Implemented via parameter-efficient fine-tuning, it can integrate seamlessly with any Transformer-based model. Experiments demonstrate that our memory design achieves state-of-the-art performance in long-context language modeling and retrieval-augmented generation tasks. It also significantly outperforms conventional memory modules in long-horizon interaction tasks like conversational agents, showcasing its potential for next-generation retrieval systems.

[Arxiv](https://arxiv.org/abs/2502.15957)