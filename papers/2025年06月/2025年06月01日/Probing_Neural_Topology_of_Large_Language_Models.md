# 大型语言模型的神经拓扑探索

发布时间：2025年06月01日

`LLM理论` `人工智能` `神经网络`

> Probing Neural Topology of Large Language Models

# 摘要

> 通过连接神经表示与可解释语义，对大型语言模型（LLMs）的探查揭示了其内部机制的诸多奥秘。然而，神经元之间如何协同激活以产生涌现能力仍是个谜，这限制了我们对LLMs的理解与安全开发。本研究提出了一种图探查方法，旨在揭示LLMs神经元的功能连接拓扑结构及其与语言生成性能的关系。通过对不同家族和规模的LLMs内部神经图进行分析，我们发现了一种仅凭神经拓扑结构即可预测下一个词预测性能的普遍规律。这种预测能力在仅保留1%神经连接或在预训练仅8步后探查模型时依然表现稳健，凸显了拓扑模式的稀疏性和早期出现。进一步的图匹配分析表明，尽管不同LLMs在架构、参数和训练数据上存在显著差异，但它们发展出了复杂且一致的神经拓扑结构，这可能构成了它们语言生成能力的基础。图探查工具箱的代码和数据已发布于https://github.com/DavyMorgan/llm-graph-probing。


> Probing large language models (LLMs) has yielded valuable insights into their internal mechanisms by linking neural representations to interpretable semantics. However, how neurons functionally co-activate with each other to give rise to emergent capabilities remains largely unknown, hindering a deeper understanding and safer development of LLMs. In this work, we introduce graph probing, a method for uncovering the functional connectivity topology of LLM neurons and relating it to language generation performance. By analyzing internal neural graphs across diverse LLM families and scales, we discover a universal predictability of next-token prediction performance using only neural topology. This predictability is robust even when retaining just 1% of neuron connections or probing models after only 8 pretraining steps, highlighting the sparsity and early emergence of topological patterns. Further graph matching analysis suggests that, despite significant distinctions in architectures, parameters, and training data, different LLMs develop intricate and consistent neural topological structures that may form the foundation for their language generation abilities. Codes and data for the graph probing toolbox are released at https://github.com/DavyMorgan/llm-graph-probing.

[Arxiv](https://arxiv.org/abs/2506.01042)