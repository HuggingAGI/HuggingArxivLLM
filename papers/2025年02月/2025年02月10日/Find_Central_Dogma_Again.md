# 重寻中心法则

发布时间：2025年02月10日

`LLM应用` `大型语言模型`

> Find Central Dogma Again

# 摘要

> 近年来，大型语言模型（LLMs）在序列分类、结构预测和功能预测等生物序列分析任务中表现出色。与人工智能在其他科学领域的进展类似，对生物领域大型语言模型的研究逐渐转向利用这些模型重新发现重要生物规律或挖掘生物序列中的新模式。本研究通过GPT类模型的语言迁移能力，重新发现中心法则的遗传密码规则。实验中，我们将中心法则转化为一个DNA与蛋白质序列对齐的二分类问题，正类是匹配序列，负类是非匹配序列对。首先，我们使用包含蛋白质、DNA及英汉语言序列的数据集，从零开始训练了GPT-2模型。随后，利用PAWS-X的英语相似性数据集进行微调。在DNA与蛋白质序列对齐判断测试中，微调模型达到了76%的准确率。研究还探讨了零样本能力的影响因素，包括训练稳定性和数据类型。这表明，大型语言模型仅通过语言能力迁移和序列分析，无需先验知识即可重新发现中心法则，为人工智能驱动的生物研究开辟了新路径。

> In recent years, large language models (LLMs) have achieved state-of-the-art results in various biological sequence analysis tasks, such as sequence classification, structure prediction, and function prediction. Similar to advancements in AI for other scientific fields, deeper research into biological LLMs has begun to focus on using these models to rediscover important existing biological laws or uncover entirely new patterns in biological sequences.This study leverages GPT-like LLMs to utilize language transfer capabilities to rediscover the genetic code rules of the central dogma. In our experimental design, we transformed the central dogma into a binary classification problem of aligning DNA sequences with protein sequences, where positive examples are matching DNA and protein sequences, and negative examples are non-matching pairs.We first trained a GPT-2 model from scratch using a dataset comprising protein sequences, DNA sequences, and sequences from languages such as English and Chinese. Subsequently, we fine-tuned the model using the English similarity judgment dataset from PAWS-X. When tested on a dataset for DNA and protein sequence alignment judgment, the fine-tuned model achieved a classification accuracy of 76%. The study also analyzed factors contributing to this zero-shot capability, including model training stability and types of training data.This research demonstrates that LLMs can, through the transfer of natural language capabilities and solely relying on the analysis of sequences themselves, rediscover the central dogma without prior knowledge of it. This study opens a new door for AI-driven biological research.

[Arxiv](https://arxiv.org/abs/2502.06253)