# NyayaRAG：基于印度普通法系的现实法律判决预测与RAG方法

发布时间：2025年08月01日

`RAG`

> NyayaRAG: Realistic Legal Judgment Prediction with RAG under the Indian Common Law System

# 摘要

> 法律判决预测（LJP）作为AI在法律领域中的重要研究方向，旨在实现司法结果的自动化预测并提升法律推理的可解释性。然而，先前在印度语境下的研究主要依赖于案件内部内容，如事实、争议点和推理过程，却常常忽视普通法系中的核心要素——即对成文法条款和司法先例的依赖。针对这一问题，我们提出了一种名为NyayaRAG的检索增强生成（RAG）框架。该框架通过为模型提供事实性的案件描述、相关法律条文以及语义检索得到的先前案例，模拟真实的法庭场景。我们采用专门针对印度法律体系设计的领域特定pipeline，评估了这些综合输入在预测法院判决和生成法律解释方面的有效性。通过标准的词汇和语义指标，以及基于LLM的评估器（如G-Eval），我们对不同输入配置下的性能进行了全面评估。实验结果表明，将事实性输入与结构化的法律知识相结合，能够显著提升预测准确性和解释质量。

> Legal Judgment Prediction (LJP) has emerged as a key area in AI for law, aiming to automate judicial outcome forecasting and enhance interpretability in legal reasoning. While previous approaches in the Indian context have relied on internal case content such as facts, issues, and reasoning, they often overlook a core element of common law systems, which is reliance on statutory provisions and judicial precedents. In this work, we propose NyayaRAG, a Retrieval-Augmented Generation (RAG) framework that simulates realistic courtroom scenarios by providing models with factual case descriptions, relevant legal statutes, and semantically retrieved prior cases. NyayaRAG evaluates the effectiveness of these combined inputs in predicting court decisions and generating legal explanations using a domain-specific pipeline tailored to the Indian legal system. We assess performance across various input configurations using both standard lexical and semantic metrics as well as LLM-based evaluators such as G-Eval. Our results show that augmenting factual inputs with structured legal knowledge significantly improves both predictive accuracy and explanation quality.

[Arxiv](https://arxiv.org/abs/2508.00709)