# CoSIL: 利用LLM驱动的代码仓库图搜索实现软件问题定位

发布时间：2025年03月28日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLMs）在软件工程中的应用，特别是如何通过LLMs实现高效的代码修复。论文提出了一种基于LLMs的函数级问题定位方法CoSIL，该方法利用LLMs的上下文理解和生成能力来定位代码中的问题，并生成补丁。这属于LLMs在特定任务中的应用，因此归类为LLM应用。` `软件工程` `软件开发`

> CoSIL: Software Issue Localization via LLM-Driven Code Repository Graph Searching

# 摘要

> 大型语言模型（LLMs）推动了自主软件工程的显著进步，催生了众多辅助开发者实现自动程序修复的软件工程代理。问题定位作为生成准确补丁的基础，至关重要。然而，现有方法在平衡简洁且有效的上下文以及充分全面的搜索空间方面面临挑战，这主要源于LLMs上下文窗口长度的限制。本文提出了一种基于LLMs的简单而强大的函数级问题定位方法——CoSIL，无需训练或索引。CoSIL通过模块调用图缩小搜索空间，迭代搜索函数调用图以获取相关上下文，并利用上下文剪枝技术控制搜索方向并有效管理上下文。值得注意的是，调用图在搜索过程中由LLM动态构建，无需预先解析。实验结果表明，使用Qwen2.5 Coder 32B，CoSIL在SWE bench Lite和SWE bench Verified上的Top-1定位成功率分别达到43%和44.6%，比现有方法高出8.6%到98.2%。当CoSIL用于指导补丁生成阶段时，修复率进一步提高了9.3%到31.5%。

> Large language models (LLMs) have significantly advanced autonomous software engineering, leading to a growing number of software engineering agents that assist developers in automatic program repair. Issue localization forms the basis for accurate patch generation. However, because of limitations caused by the context window length of LLMs, existing issue localization methods face challenges in balancing concise yet effective contexts and adequately comprehensive search spaces. In this paper, we introduce CoSIL, an LLM driven, simple yet powerful function level issue localization method without training or indexing. CoSIL reduces the search space through module call graphs, iteratively searches the function call graph to obtain relevant contexts, and uses context pruning to control the search direction and manage contexts effectively. Importantly, the call graph is dynamically constructed by the LLM during search, eliminating the need for pre-parsing. Experiment results demonstrate that CoSIL achieves a Top-1 localization success rate of 43 percent and 44.6 percent on SWE bench Lite and SWE bench Verified, respectively, using Qwen2.5 Coder 32B, outperforming existing methods by 8.6 to 98.2 percent. When CoSIL is applied to guide the patch generation stage, the resolved rate further improves by 9.3 to 31.5 percent.

[Arxiv](https://arxiv.org/abs/2503.22424)