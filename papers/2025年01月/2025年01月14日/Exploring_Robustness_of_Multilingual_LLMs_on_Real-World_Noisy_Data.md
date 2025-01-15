# 多语言LLMs在现实噪声数据中的鲁棒性探索

发布时间：2025年01月14日

`LLM理论

**理由**：这篇论文主要探讨了大型语言模型（LLMs）在现实世界噪声（如拼写错误）下的鲁棒性，并进行了实验验证。研究内容涉及模型的理论性能分析，特别是对不同模型在噪声环境下的表现进行比较。因此，这篇论文更适合归类为LLM理论。` `语言模型`

> Exploring Robustness of Multilingual LLMs on Real-World Noisy Data

# 摘要

> 大型语言模型（LLMs）基于可能包含人类拼写错误的网络数据进行训练，但它们是否对现实世界的噪声具有鲁棒性？本文探讨了现实世界拼写错误对9个语言模型（参数范围0.2B至13B）在自然语言推理（NLI）、命名实体识别（NER）和意图分类（IC）等3种NLP任务中的影响。我们在6种语言上进行了实验，并利用维基百科编辑历史构建了现实世界噪声的字典。结果显示，模型在干净和噪声数据上的性能差距平均为2.3到4.3个百分点。此外，mT5模型整体上比BLOOM、Falcon和类似BERT的模型更具鲁棒性，尤其是mT5（13B），在3个任务和6种语言中的4种中表现最为稳定。

> Large Language Models (LLMs) are trained on Web data that might contain spelling errors made by humans. But do they become robust to similar real-world noise? In this paper, we investigate the effect of real-world spelling mistakes on the performance of 9 language models, with parameters ranging from 0.2B to 13B, in 3 different NLP tasks, namely Natural Language Inference (NLI), Name Entity Recognition (NER), and Intent Classification (IC). We perform our experiments on 6 different languages and build a dictionary of real-world noise for them using the Wikipedia edit history. We show that the performance gap of the studied models on the clean and noisy test data averaged across all the datasets and languages ranges from 2.3 to 4.3 absolute percentage points. In addition, mT5 models, in general, show more robustness compared to BLOOM, Falcon, and BERT-like models. In particular, mT5 (13B), was the most robust on average overall, across the 3 tasks, and in 4 of the 6 languages.

[Arxiv](https://arxiv.org/abs/2501.08322)