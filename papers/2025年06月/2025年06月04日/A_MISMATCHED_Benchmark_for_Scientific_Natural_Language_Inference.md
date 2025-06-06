# 科学自然语言推理的基准测试中的不匹配问题

发布时间：2025年06月04日

`LLM应用

LLM应用` `科学文献分析`

> A MISMATCHED Benchmark for Scientific Natural Language Inference

# 摘要

> 科学自然语言推理（NLI）旨在预测研究文章中句子对的语义关系。现有数据集局限于计算机科学领域，而其他领域则未被涉及。本文推出全新科学NLI评估基准——MISMATCHED，涵盖心理学、工程学和公共卫生三个领域，包含2700对人工标注的句子。我们基于预训练的小型语言模型（SLMs）和大型语言模型（LLMs）在MISMATCHED上建立基线，其中表现最佳的基线模型Macro F1仅为78.17%，表明未来提升空间巨大。除了介绍MISMATCHED基准之外，我们还发现，在模型训练中加入具有隐含科学NLI关系的句子对可以提升其在科学NLI任务上的性能。我们的数据集和代码已在GitHub上公开。


> Scientific Natural Language Inference (NLI) is the task of predicting the semantic relation between a pair of sentences extracted from research articles. Existing datasets for this task are derived from various computer science (CS) domains, whereas non-CS domains are completely ignored. In this paper, we introduce a novel evaluation benchmark for scientific NLI, called MISMATCHED. The new MISMATCHED benchmark covers three non-CS domains-PSYCHOLOGY, ENGINEERING, and PUBLIC HEALTH, and contains 2,700 human annotated sentence pairs. We establish strong baselines on MISMATCHED using both Pre-trained Small Language Models (SLMs) and Large Language Models (LLMs). Our best performing baseline shows a Macro F1 of only 78.17% illustrating the substantial headroom for future improvements. In addition to introducing the MISMATCHED benchmark, we show that incorporating sentence pairs having an implicit scientific NLI relation between them in model training improves their performance on scientific NLI. We make our dataset and code publicly available on GitHub.

[Arxiv](https://arxiv.org/abs/2506.04603)