# GRACE：图引导的仓库感知代码补全——基于层次化代码融合

发布时间：2025年09月07日

`RAG` `工业与制造`

> GRACE: Graph-Guided Repository-Aware Code Completion through Hierarchical Code Fusion

# 摘要

> 大型语言模型（LLMs）擅长本地化代码补全，但在仓库级任务上却表现不佳——这主要受制于有限的上下文窗口，以及代码库中复杂的语义和结构依赖。尽管检索增强生成（RAG）通过检索相关代码片段缓解了上下文不足的问题，但现有方法仍存在明显局限：它们过度依赖文本相似度进行检索，忽略了调用链、继承层次等结构性关系；同时，将检索到的代码片段简单拼接成文本序列输入LLM的做法，也导致关键结构信息丢失。为解决这些问题，GRACE构建了一个多层多语义代码图，整合了文件结构、抽象语法树、函数调用图、类层次结构和数据流图，从而同时捕获代码的静态和动态语义。在检索阶段，GRACE采用混合图检索器，将基于图神经网络的结构相似度与文本检索相结合，并通过基于图注意力网络的重排序器进一步优化，优先选择拓扑相关的子图。为增强上下文信息，GRACE还引入了结构融合机制，将检索到的子图与局部代码上下文融合，并保留函数调用、继承等关键依赖关系。在公开的仓库级基准测试上进行的大量实验表明，GRACE在所有指标上均显著优于现有最佳方法。以DeepSeek-V3为基础LLM时，GRACE在所有数据集上均超越了最强的基于图的RAG基线，EM指标提升8.19%，ES指标提升7.51%。代码可在https://anonymous.4open.science/r/grace_icse-C3D5获取。

> LLMs excel in localized code completion but struggle with repository-level tasks due to limited context windows and complex semantic and structural dependencies across codebases. While Retrieval-Augmented Generation (RAG) mitigates context scarcity by retrieving relevant code snippets, current approaches face significant limitations. They overly rely on textual similarity for retrieval, neglecting structural relationships such as call chains and inheritance hierarchies, and lose critical structural information by naively concatenating retrieved snippets into text sequences for LLM input. To address these shortcomings, GRACE constructs a multi-level, multi-semantic code graph that unifies file structures, abstract syntax trees, function call graphs, class hierarchies, and data flow graphs to capture both static and dynamic code semantics. For retrieval, GRACE employs a Hybrid Graph Retriever that integrates graph neural network-based structural similarity with textual retrieval, refined by a graph attention network-based re-ranker to prioritize topologically relevant subgraphs. To enhance context, GRACE introduces a structural fusion mechanism that merges retrieved subgraphs with the local code context and preserves essential dependencies like function calls and inheritance. Extensive experiments on public repository-level benchmarks demonstrate that GRACE significantly outperforms state-of-the-art methods across all metrics. Using DeepSeek-V3 as the backbone LLM, GRACE surpasses the strongest graph-based RAG baselines by 8.19% EM and 7.51% ES points on every dataset. The code is available at https://anonymous.4open.science/r/grace_icse-C3D5.

[Arxiv](https://arxiv.org/abs/2509.05980)