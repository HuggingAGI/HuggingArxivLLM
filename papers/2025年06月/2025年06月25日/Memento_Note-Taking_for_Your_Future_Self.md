# # Memento：为未来的你，记录当下

**留住此刻，照亮未来**

发布时间：2025年06月25日

`RAG` `问答系统` `智能体`

> Memento: Note-Taking for Your Future Self

# 摘要

> 大型语言模型（LLMs）擅长纯推理任务，但在需要推理与检索紧密结合的场景下（如多跳问答）往往表现欠佳。为突破这一限制，我们提出了一种名为Memento的提示策略，该策略通过三步走来提升模型能力：首先将复杂问题拆解为更小的子任务，然后利用LLMs动态构建事实数据库，最后将这些事实整合起来解决问题。

我们通过实验展示了Memento策略的强大效果：在9步PhantomWiki基准测试中，当所有信息均在上下文中提供时，Memento使思维链（CoT）的性能实现翻倍。在开放领域的2WikiMultiHopQA数据集上，配备Memento的CoT-RAG比基础CoT-RAG提升了超过20个F1百分点，比多跳RAG基线IRCoT更是提升了超过13个F1百分点。在具有挑战性的MuSiQue数据集上，Memento使ReAct的性能提升了超过3个F1百分点，充分证明了其在智能体场景中的实用价值。

> Large language models (LLMs) excel at reasoning-only tasks, but struggle when reasoning must be tightly coupled with retrieval, as in multi-hop question answering. To overcome these limitations, we introduce a prompting strategy that first decomposes a complex question into smaller steps, then dynamically constructs a database of facts using LLMs, and finally pieces these facts together to solve the question. We show how this three-stage strategy, which we call Memento, can boost the performance of existing prompting strategies across diverse settings. On the 9-step PhantomWiki benchmark, Memento doubles the performance of chain-of-thought (CoT) when all information is provided in context. On the open-domain version of 2WikiMultiHopQA, CoT-RAG with Memento improves over vanilla CoT-RAG by more than 20 F1 percentage points and over the multi-hop RAG baseline, IRCoT, by more than 13 F1 percentage points. On the challenging MuSiQue dataset, Memento improves ReAct by more than 3 F1 percentage points, demonstrating its utility in agentic settings.

[Arxiv](https://arxiv.org/abs/2506.20642)