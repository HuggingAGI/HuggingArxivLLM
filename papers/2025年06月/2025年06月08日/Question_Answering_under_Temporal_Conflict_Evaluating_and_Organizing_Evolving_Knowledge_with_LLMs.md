# 时间冲突下的问答任务：利用大语言模型评估与组织动态知识

发布时间：2025年06月08日

`Agent` `问答系统` `知识管理`

> Question Answering under Temporal Conflict: Evaluating and Organizing Evolving Knowledge with LLMs

# 摘要

> 大型语言模型（LLMs）凭借其庞大的参数化记忆，在问答和推理任务中展现出了卓越的能力。然而，它们的知识从根本上受到预训练数据范围的限制，而现实世界的信息却在不断演变。更新这些知识通常需要昂贵且脆弱的重新训练，或者通过上下文学习（ICL）来实现，但考虑到现代信息的规模和波动性，这种方法在大规模应用中变得不切实际。为了解决这些限制，我们研究了当LLMs接触到反映知识随时间演变的文本语料库或文档时（例如体育传记，其中“当前球队”等事实逐年变化），它们的表现如何。为此，我们引入了两个新的基准测试：时间维基（Temporal Wiki）和统一克拉克（Unified Clark）。时间维基捕捉了历史维基百科快照中的事实漂移，而统一克拉克聚合了带有时间戳的新闻文章，以模拟现实世界的信息积累。我们的分析表明，LLMs常常难以调和相互冲突或过时的事实，并且在上下文中出现多个事实版本时可能会被误导。为了解决这些问题，我们提出了一种轻量级的智能体框架，该框架能够从源文档中逐步构建一个结构化的外部记忆，而无需重新训练。这种知识组织策略使模型能够在推理时检索并推理经过时间过滤的相关信息。实证结果显示，我们的方法在两个基准测试中都优于ICL和RAG基线，尤其是在需要更复杂推理或整合冲突事实的问题上表现尤为突出。

> Large language models (LLMs) exhibit remarkable capabilities in question answering and reasoning thanks to their extensive parametric memory. However, their knowledge is inherently limited by the scope of their pre-training data, while real-world information evolves continuously. Updating this knowledge typically requires costly and brittle re-training, or in-context learning (ICL), which becomes impractical at scale given the volume and volatility of modern information. Motivated by these limitations, we investigate how LLMs perform when exposed to temporal text corpora, or documents that reflect evolving knowledge over time, such as sports biographies where facts like a player's "current team" change year by year. To this end, we introduce two new benchmarks: Temporal Wiki, which captures factual drift across historical Wikipedia snapshots, and Unified Clark, which aggregates timestamped news articles to simulate real-world information accumulation. Our analysis reveals that LLMs often struggle to reconcile conflicting or outdated facts and can be misled when multiple versions of a fact appear in context. To address these issues, we propose a lightweight, agentic framework that incrementally builds a structured, external memory from source documents without requiring re-training. This knowledge organization strategy enables models to retrieve and reason over temporally filtered, relevant information at inference time. Empirically, our method outperforms ICL and RAG baselines across both benchmarks, especially on questions requiring more complex reasoning or integration of conflicting facts.

[Arxiv](https://arxiv.org/abs/2506.07270)