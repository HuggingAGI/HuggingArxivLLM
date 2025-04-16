# RankAlign：以排序视角审视大型语言模型中的生成器与验证器差距

发布时间：2025年04月15日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLMs）内部的一致性问题，特别是生成器和验证器之间的差距，并提出了一种新的训练方法RankAlign来解决这一问题。研究的重点在于模型的内在机制和训练方法，属于LLM理论的范畴。` `问答系统`

> RankAlign: A Ranking View of the Generator-Validator Gap in Large Language Models

# 摘要

> 尽管大型语言模型（LLMs）在各项任务中表现出更高的通用性和准确性，但其行为仍存在根本性的不可靠性。一个关键问题是，当提示发生变化时，模型对同一信息的报告往往缺乏一致性。在本研究中，我们聚焦于生成器-验证器差距——即模型生成答案与其自身验证之间存在的不一致。我们以比以往研究更严格的标准定义这一差距：生成器和验证器需在整个候选答案集中实现分数相关性。通过这一衡量标准，我们发现问答任务、词汇语义任务以及下一个单词预测等不同场景下均存在显著差距。为此，我们提出了RankAlign——一种基于排名的训练方法，结果显示该方法能将差距平均缩小31.8%，超越所有基线方法。值得注意的是，这一方法不仅在跨领域任务中表现出色，对词汇项的泛化能力也尤为突出。

> Although large language models (LLMs) have become generally more capable and accurate across many tasks, some fundamental sources of unreliability remain in their behavior. One key limitation is their inconsistency at reporting the the same information when prompts are changed. In this paper, we consider the discrepancy between a model's generated answer and their own verification of that answer, the generator-validator gap. We define this gap in a more stringent way than prior work: we expect correlation of scores from a generator and a validator over the entire set of candidate answers. We show that according to this measure, a large gap exists in various settings, including question answering, lexical semantics tasks, and next-word prediction. We then propose RankAlign, a ranking-based training method, and show that it significantly closes the gap by 31.8% on average, surpassing all baseline methods. Moreover, this approach generalizes well to out-of-domain tasks and lexical items.

[Arxiv](https://arxiv.org/abs/2504.11381)