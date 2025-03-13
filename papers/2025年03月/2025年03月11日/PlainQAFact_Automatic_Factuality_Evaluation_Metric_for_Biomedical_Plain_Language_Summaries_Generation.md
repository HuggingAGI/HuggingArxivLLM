# PlainQAFact: 用于生物医学PLAIN语言摘要生成的自动事实性评估指标

发布时间：2025年03月11日

`LLM应用` `事实性评估`

> PlainQAFact: Automatic Factuality Evaluation Metric for Biomedical Plain Language Summaries Generation

# 摘要

> 语言模型的幻觉输出在医疗领域存在风险，尤其是对普通用户在做出健康相关决策时。现有的事实性评估方法，如基于蕴含关系和问答（QA）的方法，在处理简单语言摘要（PLS）生成时面临困难，这是由于详尽解释现象引入了源文档中不存在的外部内容（例如定义、背景、示例），以增强理解。为了解决这一问题，我们引入了PlainQAFact框架，该框架基于细粒度的人工标注数据集PlainFact进行训练，用于评估源简化和详尽解释句子的事实性。PlainQAFact首先对事实性类型进行分类，然后采用基于检索增强的问答评分方法评估事实性。我们的方法轻量且计算高效。实证结果表明，现有事实性评估指标无法有效评估PLS的事实性，尤其是在详尽解释方面，而PlainQAFact实现了最先进的性能。我们进一步分析了其在外部知识来源、答案提取策略、重叠度量和文档粒度级别上的有效性，并完善了其整体事实性评估。

> Hallucinated outputs from language models pose risks in the medical domain, especially for lay audiences making health-related decisions. Existing factuality evaluation methods, such as entailment- and question-answering-based (QA), struggle with plain language summary (PLS) generation due to elaborative explanation phenomenon, which introduces external content (e.g., definitions, background, examples) absent from the source document to enhance comprehension. To address this, we introduce PlainQAFact, a framework trained on a fine-grained, human-annotated dataset PlainFact, to evaluate the factuality of both source-simplified and elaboratively explained sentences. PlainQAFact first classifies factuality type and then assesses factuality using a retrieval-augmented QA-based scoring method. Our approach is lightweight and computationally efficient. Empirical results show that existing factuality metrics fail to effectively evaluate factuality in PLS, especially for elaborative explanations, whereas PlainQAFact achieves state-of-the-art performance. We further analyze its effectiveness across external knowledge sources, answer extraction strategies, overlap measures, and document granularity levels, refining its overall factuality assessment.

[Arxiv](https://arxiv.org/abs/2503.08890)