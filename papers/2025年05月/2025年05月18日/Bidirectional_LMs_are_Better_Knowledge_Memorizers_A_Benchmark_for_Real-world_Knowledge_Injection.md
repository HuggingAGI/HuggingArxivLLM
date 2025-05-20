# 双向LMs更擅长知识记忆？现实世界知识注入能力的基准测试

发布时间：2025年05月18日

`LLM应用

摘要中讨论了知识记忆能力的基准测试、模型结构对知识记忆的影响以及提出了一种协作框架来提升性能，这些都是在应用层面优化大型语言模型的表现。` `人工智能` `知识基准测试`

> Bidirectional LMs are Better Knowledge Memorizers? A Benchmark for Real-world Knowledge Injection

# 摘要

> 尽管大型语言模型（LLMs）取得了显著进展，但其知识记忆能力仍未得到充分探索，主要因为缺乏标准化和高质量的测试基准。本文提出了一种新型、现实世界且大规模的知识注入基准，能够随时间持续演进，无需人工干预。具体来说，我们推出了WikiDYK，该基准利用了维基百科“你知道吗...”条目中最近添加且由人工编写的事实。这些条目由经验丰富的维基百科编辑根据可验证性和清晰度等标准精心挑选。每个条目被转化为多种问答对，涵盖了从简单填空提示到复杂多跳问题等多样化的任务格式。WikiDYK包含12,290个事实和77,180个问题，并能够通过维基百科编辑的未来更新无缝扩展。通过持续预训练进行的广泛实验揭示了一个令人惊讶的发现：尽管因果语言模型（CLMs）在现代LLMs中普遍存在，但与双向语言模型（BiLMs）相比，它们表现出明显较弱的知识记忆能力，可靠性准确度降低了23%。为了解决当前BiLMs规模较小的问题，我们提出了一种模块化的协作框架，利用BiLMs集合作为外部知识库与LLMs集成。实验表明，我们的框架进一步将可靠性准确度提高了29.1%。

> Despite significant advances in large language models (LLMs), their knowledge memorization capabilities remain underexplored, due to the lack of standardized and high-quality test ground. In this paper, we introduce a novel, real-world and large-scale knowledge injection benchmark that evolves continuously over time without requiring human intervention. Specifically, we propose WikiDYK, which leverages recently-added and human-written facts from Wikipedia's "Did You Know..." entries. These entries are carefully selected by expert Wikipedia editors based on criteria such as verifiability and clarity. Each entry is converted into multiple question-answer pairs spanning diverse task formats from easy cloze prompts to complex multi-hop questions. WikiDYK contains 12,290 facts and 77,180 questions, which is also seamlessly extensible with future updates from Wikipedia editors. Extensive experiments using continued pre-training reveal a surprising insight: despite their prevalence in modern LLMs, Causal Language Models (CLMs) demonstrate significantly weaker knowledge memorization capabilities compared to Bidirectional Language Models (BiLMs), exhibiting a 23% lower accuracy in terms of reliability. To compensate for the smaller scales of current BiLMs, we introduce a modular collaborative framework utilizing ensembles of BiLMs as external knowledge repositories to integrate with LLMs. Experiment shows that our framework further improves the reliability accuracy by up to 29.1%.

[Arxiv](https://arxiv.org/abs/2505.12306)