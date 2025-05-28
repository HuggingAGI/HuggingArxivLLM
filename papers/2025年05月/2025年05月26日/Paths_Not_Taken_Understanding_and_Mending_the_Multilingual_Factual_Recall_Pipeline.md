# 未走的路：修复与理解多语言事实检索管道

发布时间：2025年05月26日

`LLM应用` `多语言处理`

> Paths Not Taken: Understanding and Mending the Multilingual Factual Recall Pipeline

# 摘要

> 多语言大型语言模型（LLMs）在跨语言事实一致性方面表现欠佳，尤其在英语以外的语言中事实回忆能力明显下降。我们通过机制分析揭示了LLMs处理多语言查询的内在逻辑：首先依赖以英语为中心的事实回忆机制进行处理，然后将答案回译成目标语言。这一过程存在两大关键问题：一是对可靠英语机制的调用不足，二是回译过程中的错误。针对这些弱点，我们提出了两种通用的向量干预方法，帮助模型找到更优的事实处理路径。通过这些干预措施，我们成功将最低表现语言的事实回忆准确率提升了35%以上。这一发现证明了机制分析在释放LLMs多语言潜力方面的重要作用。

> Multilingual large language models (LLMs) often exhibit factual inconsistencies across languages, with significantly better performance in factual recall tasks in English than in other languages. The causes of these failures, however, remain poorly understood. Using mechanistic analysis techniques, we uncover the underlying pipeline that LLMs employ, which involves using the English-centric factual recall mechanism to process multilingual queries and then translating English answers back into the target language. We identify two primary sources of error: insufficient engagement of the reliable English-centric mechanism for factual recall, and incorrect translation from English back into the target language for the final answer. To address these vulnerabilities, we introduce two vector interventions, both independent of languages and datasets, to redirect the model toward better internal paths for higher factual consistency. Our interventions combined increase the recall accuracy by over 35 percent for the lowest-performing language. Our findings demonstrate how mechanistic insights can be used to unlock latent multilingual capabilities in LLMs.

[Arxiv](https://arxiv.org/abs/2505.20546)