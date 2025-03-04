# RAPID：高效检索增强长文本生成，结合写作规划与信息发现

发布时间：2025年03月02日

`LLM应用` `百科全书编写`

> RAPID: Efficient Retrieval-Augmented Long Text Generation with Writing Planning and Information Discovery

# 摘要

> 生成知识密集型的长文本（如百科全书文章）仍是大型语言模型面临的重要挑战。这不仅要求精准整合事实，还需确保文章主题连贯。现有方法（如直接生成和多智能体讨论）常受幻觉、主题不连贯和延迟等问题困扰。为解决这些难题，我们提出RAPID——一个高效增强型长文本生成框架。RAPID由三大核心模块构成：(1) 增强的检索式提纲生成，有效降低幻觉；(2) 属性约束搜索，实现高效信息挖掘；(3) 计划引导生成，提升文章连贯性。在全新基准数据集FreshWiki-2024上的实验证明，RAPID在长文本生成质量、提纲准确度及生成效率等多方面显著优于现有最优方法。我们的研究为自动化长文本生成提供了强大且高效的解决方案。

> Generating knowledge-intensive and comprehensive long texts, such as encyclopedia articles, remains significant challenges for Large Language Models. It requires not only the precise integration of facts but also the maintenance of thematic coherence throughout the article. Existing methods, such as direct generation and multi-agent discussion, often struggle with issues like hallucinations, topic incoherence, and significant latency. To address these challenges, we propose RAPID, an efficient retrieval-augmented long text generation framework. RAPID consists of three main modules: (1) Retrieval-augmented preliminary outline generation to reduce hallucinations, (2) Attribute-constrained search for efficient information discovery, (3) Plan-guided article generation for enhanced coherence. Extensive experiments on our newly compiled benchmark dataset, FreshWiki-2024, demonstrate that RAPID significantly outperforms state-of-the-art methods across a wide range of evaluation metrics (e.g. long-text generation, outline quality, latency, etc). Our work provides a robust and efficient solution to the challenges of automated long-text generation.

[Arxiv](https://arxiv.org/abs/2503.00751)