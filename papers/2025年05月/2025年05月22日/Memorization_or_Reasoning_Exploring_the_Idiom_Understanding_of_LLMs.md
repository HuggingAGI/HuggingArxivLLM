# 记忆还是推理？大型语言模型如何理解习语

发布时间：2025年05月22日

`LLM理论` `语言处理`

> Memorization or Reasoning? Exploring the Idiom Understanding of LLMs

# 摘要

> 习语因其独特的语言特性，长期以来一直是语言处理中的难题，与其他表达方式截然不同。尽管近期研究利用大型语言模型（LLMs）在习语生成和翻译等任务中取得进展，但 LLMs 在多语言环境下处理习语的内在机制仍鲜为人知。为此，我们推出了包含六种语言习语的大型数据集 MIDAS，每种语言均附带其对应含义。基于这一数据集，我们对 LLMs 的习语处理能力进行了全面评估，揭示了影响其表现的关键因素。研究发现，LLMs 不仅依赖记忆，还采用结合上下文线索与推理的混合方法，尤其在处理组合性习语时表现突出。这表明，LLMs 对习语的理解源于内部知识检索与推理推断的协同作用。

> Idioms have long posed a challenge due to their unique linguistic properties, which set them apart from other common expressions. While recent studies have leveraged large language models (LLMs) to handle idioms across various tasks, e.g., idiom-containing sentence generation and idiomatic machine translation, little is known about the underlying mechanisms of idiom processing in LLMs, particularly in multilingual settings. To this end, we introduce MIDAS, a new large-scale dataset of idioms in six languages, each paired with its corresponding meaning. Leveraging this resource, we conduct a comprehensive evaluation of LLMs' idiom processing ability, identifying key factors that influence their performance. Our findings suggest that LLMs rely not only on memorization, but also adopt a hybrid approach that integrates contextual cues and reasoning, especially when processing compositional idioms. This implies that idiom understanding in LLMs emerges from an interplay between internal knowledge retrieval and reasoning-based inference.

[Arxiv](https://arxiv.org/abs/2505.16216)