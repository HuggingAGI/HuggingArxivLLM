# FactsR：一种更安全的生成高质量医疗文档的方法

发布时间：2025年05月15日

`LLM应用`

> FactsR: A Safer Method for Producing High Quality Healthcare Documentation

# 摘要

> 如今，医疗领域涌现了众多AI记录工具，承诺借助大型语言模型（LLMs）实现环境文档的生成。然而，这些工具在诊疗结束后生成记录时，仍依赖单次或少量示例提示，推理能力有限。这可能引发冗长的记录、幻觉现象增多、医生意图误述等问题，且依赖医生校对纠错。若因工作压力和疲劳导致警惕性下降，将对患者安全构成威胁。本文提出一种在诊疗过程中实时提取关键临床信息（称为Facts）的方法，并利用这些信息递归生成最终记录。FactsR方法通过让临床医生参与注释生成循环，生成了更准确、更简洁的记录，同时为实时决策支持开辟了新的应用场景。

> There are now a multitude of AI-scribing solutions for healthcare promising the utilization of large language models for ambient documentation. However, these AI scribes still rely on one-shot, or few-shot prompts for generating notes after the consultation has ended, employing little to no reasoning. This risks long notes with an increase in hallucinations, misrepresentation of the intent of the clinician, and reliance on the proofreading of the clinician to catch errors. A dangerous combination for patient safety if vigilance is compromised by workload and fatigue. In this paper, we introduce a method for extracting salient clinical information in real-time alongside the healthcare consultation, denoted Facts, and use that information recursively to generate the final note. The FactsR method results in more accurate and concise notes by placing the clinician-in-the-loop of note generation, while opening up new use cases within real-time decision support.

[Arxiv](https://arxiv.org/abs/2505.10360)