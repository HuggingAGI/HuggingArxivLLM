# LLMs 时代的法律引用预测方法：澳大利亚法律案例研究

发布时间：2024年12月09日

`LLM应用` `人工智能`

> Methods for Legal Citation Prediction in the Age of LLMs: An Australian Law Case Study

# 摘要

> 近年来，大型语言模型（LLMs）在众多法律任务中展现出极大的潜力。不过，尽管有这些进步，减少幻觉仍是重大挑战，最前沿的LLMs仍时常给出错误的法律引用。在本文里，我们聚焦于澳大利亚法律情境下的法律引用预测问题，在这种情境中，正确识别和引用相关立法或先例极为关键。我们对比了若干方法：提示通用和法律专业的LLMs、具备通用和领域特定嵌入的仅检索管道、对LLMs进行特定任务的指令调整，以及将LLMs与检索增强、查询扩展或投票集成相结合的混合策略。我们的发现表明，即便经过法律专业的预训练，仅靠领域特定的预训练也难以达到令人满意的引用准确率。相比之下，针对我们的特定任务数据集进行指令调整能大幅提升性能，在所有设定中都取得了最佳成果。我们还指出，数据库粒度以及嵌入的类型在检索系统的性能中发挥着关键作用。在基于检索的方法中，混合方法始终优于仅检索的模式，其中，集成投票通过将指令调整的LLMs的预测质量与检索系统相结合，实现了最优结果。

> In recent years, Large Language Models (LLMs) have shown great potential across a wide range of legal tasks. Despite these advances, mitigating hallucination remains a significant challenge, with state-of-the-art LLMs still frequently generating incorrect legal references. In this paper, we focus on the problem of legal citation prediction within the Australian law context, where correctly identifying and citing relevant legislations or precedents is critical. We compare several approaches: prompting general purpose and law-specialised LLMs, retrieval-only pipelines with both generic and domain-specific embeddings, task-specific instruction-tuning of LLMs, and hybrid strategies that combine LLMs with retrieval augmentation, query expansion, or voting ensembles. Our findings indicate that domain-specific pre-training alone is insufficient for achieving satisfactory citation accuracy even after law-specialised pre-training. In contrast, instruction tuning on our task-specific dataset dramatically boosts performance reaching the best results across all settings. We also highlight that database granularity along with the type of embeddings play a critical role in the performance of retrieval systems. Among retrieval-based approaches, hybrid methods consistently outperform retrieval-only setups, and among these, ensemble voting delivers the best result by combining the predictive quality of instruction-tuned LLMs with the retrieval system.

[Arxiv](https://arxiv.org/abs/2412.06272)