# 基于 LLM 的可解释表格问答

发布时间：2024年12月16日

`LLM应用` `医疗保健`

> Interpretable LLM-based Table Question Answering

# 摘要

> 对于表格问答（Table QA）而言，可解释性至关重要，尤其是在金融或医疗保健等高风险行业。尽管运用大型语言模型（LLMs）的最新方法大幅提升了表格问答的性能，但其对于答案生成方式的解释却含糊不清。为弥补这一空缺，我们推出了 SQL 计划（或 POS），这是一种可解释、高效且有效的表格问答方法，仅依靠 SQL 执行来回应输入的查询。通过与人类及 LLM 评委进行定性和定量评估，我们发现，在解释方法中，POS 最受青睐，有助于人类用户理解模型的决策边界，也有利于模型成功和错误的识别。此外，在标准基准（TabFact、WikiTQ 和 FetaQA）中评估时，POS 与现有方法相比，实现了具有竞争力甚至更优的准确率，同时通过大幅减少 LLM 调用和数据库查询，保持了更高的效率。

> Interpretability for Table Question Answering (Table QA) is critical, particularly in high-stakes industries like finance or healthcare. Although recent approaches using Large Language Models (LLMs) have significantly improved Table QA performance, their explanations for how the answers are generated are ambiguous. To fill this gap, we introduce Plan-of-SQLs ( or POS), an interpretable, effective, and efficient approach to Table QA that answers an input query solely with SQL executions. Through qualitative and quantitative evaluations with human and LLM judges, we show that POS is most preferred among explanation methods, helps human users understand model decision boundaries, and facilitates model success and error identification. Furthermore, when evaluated in standard benchmarks (TabFact, WikiTQ, and FetaQA), POS achieves competitive or superior accuracy compared to existing methods, while maintaining greater efficiency by requiring significantly fewer LLM calls and database queries.

[Arxiv](https://arxiv.org/abs/2412.12386)