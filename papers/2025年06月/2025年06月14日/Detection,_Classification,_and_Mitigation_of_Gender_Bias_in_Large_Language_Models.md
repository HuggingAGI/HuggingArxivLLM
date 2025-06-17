# 大型语言模型中的性别偏见检测、分类与缓解

发布时间：2025年06月14日

`LLM应用

摘要中提到的论文主要关注于大型语言模型（LLMs）在性别偏见检测、分类和缓解方面的应用。研究采用了强化学习、链式思维推理和监督微调等技术来提升LLMs在这些任务中的表现。这些方法和应用都属于LLM的应用层面，因此分类为LLM应用。` `性别偏见` `社会影响`

> Detection, Classification, and Mitigation of Gender Bias in Large Language Models

# 摘要

> 随着大型语言模型（LLMs）的快速发展，其在众多领域中显著提升了效率。然而，近期研究表明，LLMs常常表现出性别偏见，带来了严重的社会影响。因此，检测、分类和缓解LLMs中的性别偏见已成为关键研究重点。在NLPCC 2025共享任务7：中文语料库性别偏见检测、分类与缓解挑战中，我们研究如何提升LLMs在性别偏见检测、分类和缓解方面的能力。我们采用强化学习、链式思维推理和监督微调来处理不同的子任务。具体而言，对于子任务1和2，我们利用LLMs的内部推理能力，分阶段引导多步骤思考，从而简化复杂的偏见查询并提高响应准确性。对于子任务3，我们采用基于强化学习的方法，使用GPT-4标注偏好数据集。然后，我们应用直接偏好优化（DPO），通过引入一个损失函数，显式地偏好较少偏见的完成结果，从而缓解性别偏见。在NLPCC 2025共享任务7的所有三个子任务中，我们的方法均排名第一。

> With the rapid development of large language models (LLMs), they have significantly improved efficiency across a wide range of domains. However, recent studies have revealed that LLMs often exhibit gender bias, leading to serious social implications. Detecting, classifying, and mitigating gender bias in LLMs has therefore become a critical research focus. In the NLPCC 2025 Shared Task 7: Chinese Corpus for Gender Bias Detection, Classification and Mitigation Challenge, we investigate how to enhance the capabilities of LLMs in gender bias detection, classification, and mitigation. We adopt reinforcement learning, chain-of-thoughts (CoT) reasoning, and supervised fine-tuning to handle different Subtasks. Specifically, for Subtasks 1 and 2, we leverage the internal reasoning capabilities of LLMs to guide multi-step thinking in a staged manner, which simplifies complex biased queries and improves response accuracy. For Subtask 3, we employ a reinforcement learning-based approach, annotating a preference dataset using GPT-4. We then apply Direct Preference Optimization (DPO) to mitigate gender bias by introducing a loss function that explicitly favors less biased completions over biased ones. Our approach ranked first across all three subtasks of the NLPCC 2025 Shared Task 7.

[Arxiv](https://arxiv.org/abs/2506.12527)