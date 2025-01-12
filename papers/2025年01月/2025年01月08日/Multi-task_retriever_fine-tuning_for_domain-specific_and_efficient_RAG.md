# 多任务检索器微调：实现领域特定且高效的RAG

发布时间：2025年01月08日

`RAG

理由：这篇论文主要讨论了检索增强生成（RAG）在实际应用中的挑战，并提出了通过指令微调小型检索器编码器来优化RAG应用的解决方案。论文的核心内容围绕RAG技术的改进和应用展开，因此应归类为RAG。` `信息检索` `企业应用`

> Multi-task retriever fine-tuning for domain-specific and efficient RAG

# 摘要

> 检索增强生成（RAG）在部署大型语言模型（LLMs）时已广泛应用，因其能有效应对生成幻觉或过时信息等问题。然而，构建实际RAG应用时，仍面临诸多挑战。首先，检索信息通常局限于特定领域。由于微调LLMs成本高昂，优化检索器以提升输入数据质量更为实际。其次，随着更多应用部署于同一系统，单独部署检索器变得不切实际。此外，这些RAG应用通常需检索不同类型的数据。为此，我们提出了一种解决方案：通过指令微调小型检索器编码器，使其能适应多种领域任务，从而实现低成本、高扩展性和快速响应。我们展示了该编码器在域外设置及企业实际用例中的泛化能力。

> Retrieval-Augmented Generation (RAG) has become ubiquitous when deploying Large Language Models (LLMs), as it can address typical limitations such as generating hallucinated or outdated information. However, when building real-world RAG applications, practical issues arise. First, the retrieved information is generally domain-specific. Since it is computationally expensive to fine-tune LLMs, it is more feasible to fine-tune the retriever to improve the quality of the data included in the LLM input. Second, as more applications are deployed in the same real-world system, one cannot afford to deploy separate retrievers. Moreover, these RAG applications normally retrieve different kinds of data. Our solution is to instruction fine-tune a small retriever encoder on a variety of domain-specific tasks to allow us to deploy one encoder that can serve many use cases, thereby achieving low-cost, scalability, and speed. We show how this encoder generalizes to out-of-domain settings as well as to an unseen retrieval task on real-world enterprise use cases.

[Arxiv](https://arxiv.org/abs/2501.04652)