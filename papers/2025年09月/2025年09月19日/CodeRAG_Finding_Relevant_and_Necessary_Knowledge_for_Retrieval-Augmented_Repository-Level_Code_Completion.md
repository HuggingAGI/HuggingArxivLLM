# CodeRAG：面向检索增强的仓库级代码补全，挖掘相关且必要的知识

发布时间：2025年09月19日

`RAG` `基础理论`

> CodeRAG: Finding Relevant and Necessary Knowledge for Retrieval-Augmented Repository-Level Code Completion

# 摘要

> 仓库级代码补全能够基于仓库全局信息自动预测未完成代码。近年来，代码大型语言模型（code LLMs）的快速发展催生了多种仓库级代码补全方法，效果令人期待。但这些方法仍面临查询构建不合理、代码检索路径单一、检索器与代码LLM目标错位等问题。为此，我们提出了CodeRAG——一个专为检索增强型仓库级代码补全设计的知识识别框架，致力于精准定位相关且必要的知识。该框架的核心创新点包括：对数概率引导的查询构建、多路径代码检索，以及偏好对齐的BestFit重排序机制。在ReccEval和CCEval两个基准数据集上的大量实验验证了CodeRAG的优越性——它在性能上显著且稳定地超越了现有最佳方法。CodeRAG的代码已开源，地址为https://github.com/KDEGroup/CodeRAG。

> Repository-level code completion automatically predicts the unfinished code based on the broader information from the repository. Recent strides in Code Large Language Models (code LLMs) have spurred the development of repository-level code completion methods, yielding promising results. Nevertheless, they suffer from issues such as inappropriate query construction, single-path code retrieval, and misalignment between code retriever and code LLM. To address these problems, we introduce CodeRAG, a framework tailored to identify relevant and necessary knowledge for retrieval-augmented repository-level code completion. Its core components include log probability guided query construction, multi-path code retrieval, and preference-aligned BestFit reranking. Extensive experiments on benchmarks ReccEval and CCEval demonstrate that CodeRAG significantly and consistently outperforms state-of-the-art methods. The implementation of CodeRAG is available at https://github.com/KDEGroup/CodeRAG.

[Arxiv](https://arxiv.org/abs/2509.16112)