# 个性化图结构检索在大型语言模型中的应用

发布时间：2025年01月03日

`RAG

**理由**：该论文提出了一个基于个性化图检索增强生成（PGraphRAG）的框架，通过整合用户知识图谱来增强个性化响应。这种方法属于检索增强生成（RAG）的范畴，因为它结合了检索机制（用户知识图谱）和生成模型（LLM）来提升输出的质量和个性化。因此，该论文应归类为RAG。` `个性化推荐` `知识图谱`

> Personalized Graph-Based Retrieval for Large Language Models

# 摘要

> 随着大型语言模型（LLMs）的演进，其提供个性化和上下文感知响应的能力为提升用户体验带来了巨大潜力。然而，现有个性化方法通常仅依赖用户历史来增强提示，在数据稀疏的冷启动场景中效果有限。为此，我们提出了基于个性化图检索增强生成（PGraphRAG）的框架，通过整合用户知识图谱来丰富个性化。PGraphRAG将结构化用户知识直接融入检索过程，并用用户相关上下文增强提示，从而提升上下文理解和输出质量。我们还推出了基于个性化图的文本生成基准，用于评估用户历史稀疏或缺失场景下的个性化文本生成任务。实验表明，PGraphRAG在多种任务中显著优于现有方法，展现了图检索在个性化中的独特优势。

> As large language models (LLMs) evolve, their ability to deliver personalized and context-aware responses offers transformative potential for improving user experiences. Existing personalization approaches, however, often rely solely on user history to augment the prompt, limiting their effectiveness in generating tailored outputs, especially in cold-start scenarios with sparse data. To address these limitations, we propose Personalized Graph-based Retrieval-Augmented Generation (PGraphRAG), a framework that leverages user-centric knowledge graphs to enrich personalization. By directly integrating structured user knowledge into the retrieval process and augmenting prompts with user-relevant context, PGraphRAG enhances contextual understanding and output quality. We also introduce the Personalized Graph-based Benchmark for Text Generation, designed to evaluate personalized text generation tasks in real-world settings where user history is sparse or unavailable. Experimental results show that PGraphRAG significantly outperforms state-of-the-art personalization methods across diverse tasks, demonstrating the unique advantages of graph-based retrieval for personalization.

[Arxiv](https://arxiv.org/abs/2501.02157)