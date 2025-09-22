# Best-of-L：面向数学推理的跨语言奖励建模

发布时间：2025年09月19日

`LLM应用` `基础理论`

> Best-of-L: Cross-Lingual Reward Modeling for Mathematical Reasoning

# 摘要

> 尽管大型语言模型（LLMs）的推理能力持续进步，但多语言模型的推理能力在不同语言间的差异，以及不同语言是否会产生互补的推理路径，这些问题仍有待厘清。为此，我们训练了一个奖励模型，用于对特定问题在多语言环境下生成的回答进行排序。结果显示，与单语言奖励模型相比，我们的跨语言奖励模型大幅提升了数学推理表现，就连高资源语言也能从中获益。虽然英语在多语言模型中通常表现最佳，但我们发现，在采样预算有限时，跨语言采样对英语的增益尤为突出。研究结果为利用多语言互补优势提升跨语言推理能力开辟了新方向。

> While the reasoning abilities of large language models (LLMs) continue to advance, it remains unclear how such ability varies across languages in multilingual LLMs and whether different languages produce reasoning paths that complement each other. To investigate this question, we train a reward model to rank generated responses for a given question across languages. Our results show that our cross-lingual reward model substantially improves mathematical reasoning performance compared to using reward modeling within a single language, benefiting even high-resource languages. While English often exhibits the highest performance in multilingual models, we find that cross-lingual sampling particularly benefits English under low sampling budgets. Our findings reveal new opportunities to improve multilingual reasoning by leveraging the complementary strengths of diverse languages.

[Arxiv](https://arxiv.org/abs/2509.15811)