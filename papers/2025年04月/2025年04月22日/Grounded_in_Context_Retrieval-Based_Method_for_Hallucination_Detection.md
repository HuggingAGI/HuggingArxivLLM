# 植根于上下文：基于检索的幻觉识别方法

发布时间：2025年04月22日

`LLM应用` `问答系统`

> Grounded in Context: Retrieval-Based Method for Hallucination Detection

# 摘要

> 尽管在生成基于现实的内容方面有所突破，但大语言模型（LLMs）在实际应用中仍难以避免生成不实答案。为此，我们推出Deepchecks的“立足上下文”幻觉检测框架，专为处理长上下文数据而设计，并广泛适用于摘要、数据提取及RAG等多种场景。受RAG架构启发，我们的解决方案巧妙结合了检索与自然语言推理（NLI）模型，通过一个仅支持512个token上下文窗口的编码器模型，精准预测前提与假设间事实的一致性。在RAGTruth的响应级别分类任务中，我们的框架以0.83的F1分数准确识别无支持声明，与该数据集上的训练方法表现相当，且在同类框架中使用相近规模模型时，性能更胜一筹。

> Despite advancements in grounded content generation, production Large Language Models (LLMs) based applications still suffer from hallucinated answers. We present "Grounded in Context" - Deepchecks' hallucination detection framework, designed for production-scale long-context data and tailored to diverse use cases, including summarization, data extraction, and RAG. Inspired by RAG architecture, our method integrates retrieval and Natural Language Inference (NLI) models to predict factual consistency between premises and hypotheses using an encoder-based model with only a 512-token context window. Our framework identifies unsupported claims with an F1 score of 0.83 in RAGTruth's response-level classification task, matching methods that trained on the dataset, and outperforming all comparable frameworks using similar-sized models.

[Arxiv](https://arxiv.org/abs/2504.15771)