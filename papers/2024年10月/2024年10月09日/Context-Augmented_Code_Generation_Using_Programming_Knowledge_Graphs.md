# 基于编程知识图谱的上下文增强代码生成

发布时间：2024年10月09日

`RAG

理由：这篇论文主要讨论了如何通过检索增强生成（RAG）技术来改进代码生成任务。论文提出了一种基于编程知识图谱（PKG）的新框架，用于语义化表示和检索代码，并通过树剪枝和重新排序机制来减少不相关上下文和幻觉。这些方法都是为了在推理时更好地整合外部知识，从而提高代码生成的准确性和效率。因此，这篇论文的核心内容与RAG技术密切相关，应归类为RAG。` `软件工程` `代码生成`

> Context-Augmented Code Generation Using Programming Knowledge Graphs

# 摘要

> 大型语言模型（LLMs）和代码-LLMs（CLLMs）在代码生成方面取得了显著进展，但在处理复杂问题时仍面临挑战。检索增强生成（RAG）通过在推理时整合外部知识来解决这一问题。然而，检索模型常难以找到最相关的上下文，而生成模型在接收到不相关数据时容易产生幻觉。我们提出了一种基于编程知识图谱（PKG）的新框架，用于语义化表示和检索代码。该框架通过树剪枝技术减少不相关上下文，实现细粒度代码检索。PKG结合重新排序机制，进一步减少幻觉。我们提出了基于PKG的块级和函数级两种检索方法，优化上下文粒度。在HumanEval和MBPP基准测试中，我们的方法将pass@1准确率提升了20%，并在MBPP上比现有最佳模型高出34%。我们的贡献包括基于PKG的检索、树剪枝、重新排序方法以及用于自动代码增强的Fill-in-the-Middle（FIM）模块，该模块可生成相关注释和文档字符串。

> Large Language Models (LLMs) and Code-LLMs (CLLMs) have significantly improved code generation, but, they frequently face difficulties when dealing with challenging and complex problems. Retrieval-Augmented Generation (RAG) addresses this issue by retrieving and integrating external knowledge at the inference time. However, retrieval models often fail to find most relevant context, and generation models, with limited context capacity, can hallucinate when given irrelevant data. We present a novel framework that leverages a Programming Knowledge Graph (PKG) to semantically represent and retrieve code. This approach enables fine-grained code retrieval by focusing on the most relevant segments while reducing irrelevant context through a tree-pruning technique. PKG is coupled with a re-ranking mechanism to reduce even more hallucinations by selectively integrating non-RAG solutions. We propose two retrieval approaches-block-wise and function-wise-based on the PKG, optimizing context granularity. Evaluations on the HumanEval and MBPP benchmarks show our method improves pass@1 accuracy by up to 20%, and outperforms state-of-the-art models by up to 34% on MBPP. Our contributions include PKG-based retrieval, tree pruning to enhance retrieval precision, a re-ranking method for robust solution selection and a Fill-in-the-Middle (FIM) enhancer module for automatic code augmentation with relevant comments and docstrings.

[Arxiv](https://arxiv.org/abs/2410.18251)