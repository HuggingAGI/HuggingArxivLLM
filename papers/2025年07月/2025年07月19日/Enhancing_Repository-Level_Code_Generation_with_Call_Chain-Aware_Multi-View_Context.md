# 基于调用链感知的多视角上下文增强仓库级代码生成

发布时间：2025年07月19日

`RAG` `软件工程`

> Enhancing Repository-Level Code Generation with Call Chain-Aware Multi-View Context

# 摘要

> 仓库级代码生成旨在在指定仓库的上下文中生成代码。现有方法通常采用检索增强生成（RAG）技术，从仓库中提取相关上下文信息提供给大语言模型（LLM）。然而，这些方法往往难以有效识别真正相关的上下文，难以捕捉仓库的丰富语义，且上下文视角仍然狭窄。此外，大多数方法在提示构建过程中未能考虑检索代码中的结构关系，限制了LLM对上下文的准确理解。为了解决这些问题，我们提出了RepoScope，它利用调用链感知的多视图上下文进行仓库级代码生成。RepoScope构建了一个仓库结构语义图（RSSG），并检索了一个全面的四视图上下文，整合了结构和相似性基的上下文。我们提出了一种新颖的调用链预测方法，利用仓库的结构语义来提高目标函数中被调用者的识别能力。此外，我们还提出了一种结构保留的序列化算法用于提示构建，确保上下文对LLM的一致性。值得注意的是，RepoScope仅依赖静态分析，无需额外训练或多次LLM查询，从而保证了高效性和通用性。在广泛使用的仓库级代码生成基准（CoderEval 和 DevEval）上的评估表明，RepoScope优于现有最先进的方法，在pass@1分数上实现了高达36.35%的相对提升。进一步的实验强调了RepoScope在不同任务中改进代码生成的潜力，以及与现有方法有效结合的能力。

> Repository-level code generation aims to generate code within the context of a specified repository. Existing approaches typically employ retrieval-augmented generation (RAG) techniques to provide LLMs with relevant contextual information extracted from the repository. However, these approaches often struggle with effectively identifying truly relevant contexts that capture the rich semantics of the repository, and their contextual perspectives remains narrow. Moreover, most approaches fail to account for the structural relationships in the retrieved code during prompt construction, hindering the LLM's ability to accurately interpret the context. To address these issues, we propose RepoScope, which leverages call chain-aware multi-view context for repository-level code generation. RepoScope constructs a Repository Structural Semantic Graph (RSSG) and retrieves a comprehensive four-view context, integrating both structural and similarity-based contexts. We propose a novel call chain prediction method that utilizes the repository's structural semantics to improve the identification of callees in the target function. Additionally, we present a structure-preserving serialization algorithm for prompt construction, ensuring the coherence of the context for the LLM. Notably, RepoScope relies solely on static analysis, eliminating the need for additional training or multiple LLM queries, thus ensuring both efficiency and generalizability. Evaluation on widely-used repository-level code generation benchmarks (CoderEval and DevEval) demonstrates that RepoScope outperforms state-of-the-art methods, achieving up to a 36.35% relative improvement in pass@1 scores. Further experiments emphasize RepoScope's potential to improve code generation across different tasks and its ability to integrate effectively with existing approaches.

[Arxiv](https://arxiv.org/abs/2507.14791)