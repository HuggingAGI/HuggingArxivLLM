# 高效资源利用的动态增强链，助力多跳问答

发布时间：2025年06月21日

`LLM应用` `问答系统` `知识工程`

> Resource-Friendly Dynamic Enhancement Chain for Multi-Hop Question Answering

# 摘要

> 知识密集型多跳问答（QA）任务通常需要大语言模型（LLMs）进行多轮检索和迭代生成，以整合多来源证据解决复杂查询。然而，整合大量文档和扩展上下文对轻量级LLMs来说充满挑战，例如幻觉和语义漂移等问题。本研究提出了一种名为DEC（动态增强链）的新型框架。DEC首先将复杂问题分解为逻辑连贯的子问题，形成无幻觉推理链。然后通过上下文感知重写迭代优化这些子问题，生成有效的查询表达。在检索方面，我们引入了一种轻量级判别式关键词提取模块，利用提取的关键词实现针对性、精准的文档召回，同时保持相对较低的计算开销。在三个多跳QA数据集上的大量实验表明，DEC在性能上可与或超越现有最优基准，同时大幅减少令牌消耗。值得注意的是，我们的方法在8B参数模型上达到了最优结果，展示了其在各种场景下的有效性，特别是在资源受限的环境中。

> Knowledge-intensive multi-hop question answering (QA) tasks, which require integrating evidence from multiple sources to address complex queries, often necessitate multiple rounds of retrieval and iterative generation by large language models (LLMs). However, incorporating many documents and extended contexts poses challenges -such as hallucinations and semantic drift-for lightweight LLMs with fewer parameters. This work proposes a novel framework called DEC (Dynamic Enhancement Chain). DEC first decomposes complex questions into logically coherent subquestions to form a hallucination-free reasoning chain. It then iteratively refines these subquestions through context-aware rewriting to generate effective query formulations. For retrieval, we introduce a lightweight discriminative keyword extraction module that leverages extracted keywords to achieve targeted, precise document recall with relatively low computational overhead. Extensive experiments on three multi-hop QA datasets demonstrate that DEC performs on par with or surpasses state-of-the-art benchmarks while significantly reducing token consumption. Notably, our approach attains state-of-the-art results on models with 8B parameters, showcasing its effectiveness in various scenarios, particularly in resource-constrained environments.

[Arxiv](https://arxiv.org/abs/2506.17692)