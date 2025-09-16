# CEMTM：基于上下文嵌入的多模态主题建模

发布时间：2025年09月14日

`LLM应用` `基础理论`

> CEMTM: Contextual Embedding-based Multimodal Topic Modeling

# 摘要

> 我们提出了CEMTM——一种上下文增强的多模态主题模型，专为从含文本与图像的长短文档中提取连贯且易懂的主题结构而设计。该模型依托微调的大型视觉语言模型（LVLMs）获取上下文嵌入，通过分布注意力机制对token级特征在主题推断中的贡献进行加权。重构目标将主题表示与文档嵌入对齐，确保跨模态语义连贯。与现有方法相比，CEMTM无需重复编码即可处理单文档多图像，且通过显式的词-主题与文档-主题分布保持可解释性。在六个多模态基准数据集上的大量实验证实，CEMTM持续超越单模态和多模态基线模型，平均LLM评分高达2.61。进一步分析表明，它在下游少样本检索任务中表现优异，且能在科学论文等复杂领域有效捕捉视觉关联的语义信息。

> We introduce CEMTM, a context-enhanced multimodal topic model designed to infer coherent and interpretable topic structures from both short and long documents containing text and images. CEMTM builds on fine-tuned large vision language models (LVLMs) to obtain contextualized embeddings, and employs a distributional attention mechanism to weight token-level contributions to topic inference. A reconstruction objective aligns topic-based representations with the document embedding, encouraging semantic consistency across modalities. Unlike existing approaches, CEMTM can process multiple images per document without repeated encoding and maintains interpretability through explicit word-topic and document-topic distributions. Extensive experiments on six multimodal benchmarks show that CEMTM consistently outperforms unimodal and multimodal baselines, achieving a remarkable average LLM score of 2.61. Further analysis shows its effectiveness in downstream few-shot retrieval and its ability to capture visually grounded semantics in complex domains such as scientific articles.

[Arxiv](https://arxiv.org/abs/2509.11465)