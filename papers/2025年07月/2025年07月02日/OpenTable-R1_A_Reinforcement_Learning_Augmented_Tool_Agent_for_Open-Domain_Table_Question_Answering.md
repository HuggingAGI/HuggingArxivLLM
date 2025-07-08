# OpenTable-R1：强化学习增强的工具代理，助力开放领域表格问答

发布时间：2025年07月02日

`Agent` `问答系统` `结构化数据`

> OpenTable-R1: A Reinforcement Learning Augmented Tool Agent for Open-Domain Table Question Answering

# 摘要

> 传统上，开放领域的表格问答依赖于一个两阶段的流水线：静态表格检索后进行封闭域的回答。而我们提出了一种端到端的代理框架，直接将多轮工具调用嵌入到大型语言模型中，使用基于 BM25+ 的搜索 API 和 SQLite SQL 执行器。为了更好地适应一个紧凑的 40 亿参数模型，我们设计了一个两阶段的微调流程：首先在简单问题上进行监督冷启动，然后在复杂问题上采用带有 LoRA 适配器和回滚缓冲区的异步 GRPO 强化学习。这种统一的方法使模型能够同时完成检索、推理和执行查询，从而在保留测试集上的精确匹配准确率从个位数的零样本性能提升到超过 0.86。我们的研究结果表明，将结构化工具调用与强化学习微调相结合，对于实现可扩展且准确的表格问答具有显著效果。代码已在 https://github.com/TabibitoQZP/OpenTableR1 开源。

> Open-domain table question answering traditionally relies on a two-stage pipeline: static table retrieval followed by a closed-domain answer. In contrast, we propose an end-to-end agentic framework that embeds multi-turn tool calls-using a BM25+-based search API and a SQLite SQL executor-directly into a large language model. To further adapt a compact 4B-parameter model, we introduce a two-stage fine-tuning process: supervised cold-start on easy questions, then Async GRPO reinforcement learning on harder cases with LoRA adapters and a rollout buffer. This unified approach enables the model to jointly retrieve, reason, and execute queries, yielding a dramatic accuracy improvement from single-digit zero-shot performance to over 0.86 exact match on a held-out test set. Our results underscore the effectiveness of integrating structured tool calls with targeted RL fine-tuning for scalable, accurate table QA. The code is available at https://github.com/TabibitoQZP/OpenTableR1.

[Arxiv](https://arxiv.org/abs/2507.03018)