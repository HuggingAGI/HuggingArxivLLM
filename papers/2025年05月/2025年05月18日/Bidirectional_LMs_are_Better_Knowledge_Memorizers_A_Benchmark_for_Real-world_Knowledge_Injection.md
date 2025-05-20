# 双向语言模型：更好的知识记忆者？真实世界知识注入的基准测试

发布时间：2025年05月18日

`LLM理论` `问答系统`

> Bidirectional LMs are Better Knowledge Memorizers? A Benchmark for Real-world Knowledge Injection

# 摘要

> 尽管大型语言模型（LLMs）取得了显著进展，但其知识记忆能力仍鲜为人知，原因在于缺乏标准化和高质量的测试基准。本文引入了一个新型的、现实世界的大规模知识注入基准，该基准能够随着时间的推移持续演进，无需人工干预。具体而言，我们提出了WikiDYK，它利用了维基百科“你知道吗...”条目中最近添加的、由人工编写的事实。这些条目由经验丰富的维基百科编辑根据可验证性和清晰度等标准精心挑选。每个条目被转化为多种问答对，涵盖了从简单的填空提示到复杂的多跳问题等多样化的任务格式。WikiDYK包含12,290个事实和77,180个问题，并且可以无缝扩展未来维基百科编辑的更新。通过持续预训练进行的广泛实验揭示了一个令人惊讶的见解：尽管因果语言模型（CLMs）在现代LLMs中普遍存在，但与双向语言模型（BiLMs）相比，它们表现出明显较弱的知识记忆能力，可靠性准确度降低了23%。为了弥补当前BiLMs规模较小的不足，我们引入了一个模块化的协作框架，利用BiLMs的集成作为外部知识库，与LLMs相结合。实验表明，我们的框架进一步将可靠性准确度提高了高达29.1%。

> Despite significant advances in large language models (LLMs), their knowledge memorization capabilities remain underexplored, due to the lack of standardized and high-quality test ground. In this paper, we introduce a novel, real-world and large-scale knowledge injection benchmark that evolves continuously over time without requiring human intervention. Specifically, we propose WikiDYK, which leverages recently-added and human-written facts from Wikipedia's "Did You Know..." entries. These entries are carefully selected by expert Wikipedia editors based on criteria such as verifiability and clarity. Each entry is converted into multiple question-answer pairs spanning diverse task formats from easy cloze prompts to complex multi-hop questions. WikiDYK contains 12,290 facts and 77,180 questions, which is also seamlessly extensible with future updates from Wikipedia editors. Extensive experiments using continued pre-training reveal a surprising insight: despite their prevalence in modern LLMs, Causal Language Models (CLMs) demonstrate significantly weaker knowledge memorization capabilities compared to Bidirectional Language Models (BiLMs), exhibiting a 23% lower accuracy in terms of reliability. To compensate for the smaller scales of current BiLMs, we introduce a modular collaborative framework utilizing ensembles of BiLMs as external knowledge repositories to integrate with LLMs. Experiment shows that our framework further improves the reliability accuracy by up to 29.1%.

[Arxiv](https://arxiv.org/abs/2505.12306)