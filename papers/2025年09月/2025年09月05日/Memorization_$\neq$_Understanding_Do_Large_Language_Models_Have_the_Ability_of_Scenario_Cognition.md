# 记忆≠理解：大型语言模型真的具备场景认知能力吗？

发布时间：2025年09月05日

`LLM理论` `基础理论`

> Memorization $\neq$ Understanding: Do Large Language Models Have the Ability of Scenario Cognition?

# 摘要

> 在海量多样的文本数据驱动下，大型语言模型（LLMs）在众多自然语言处理（NLP）任务中展现出令人瞩目的性能。然而，一个核心问题始终存在：它们的泛化能力究竟源于对训练数据的简单记忆，还是源于深层语义理解？为探究这一问题，我们提出了一个双视角评估框架，用于评估LLMs的场景认知能力——即把语义场景元素与上下文中的论点关联起来的能力。具体而言，我们构建了一个全新的基于场景的数据集，其中包含对虚构事实的多样化文本描述，并标注了场景元素。对LLMs的评估从两个方面展开：一是其回答场景相关问题的能力（模型输出视角），二是探测其内部表示中是否编码了场景元素与论点的关联（内部表示视角）。实验结果表明，当前的LLMs主要依赖表面记忆，即便在简单场景中也无法实现稳健的语义场景认知。这些发现揭示了LLMs在语义理解方面的关键局限，并为提升其能力提供了认知层面的启示。

> Driven by vast and diverse textual data, large language models (LLMs) have demonstrated impressive performance across numerous natural language processing (NLP) tasks. Yet, a critical question persists: does their generalization arise from mere memorization of training data or from deep semantic understanding? To investigate this, we propose a bi-perspective evaluation framework to assess LLMs' scenario cognition - the ability to link semantic scenario elements with their arguments in context. Specifically, we introduce a novel scenario-based dataset comprising diverse textual descriptions of fictional facts, annotated with scenario elements. LLMs are evaluated through their capacity to answer scenario-related questions (model output perspective) and via probing their internal representations for encoded scenario elements-argument associations (internal representation perspective). Our experiments reveal that current LLMs predominantly rely on superficial memorization, failing to achieve robust semantic scenario cognition, even in simple cases. These findings expose critical limitations in LLMs' semantic understanding and offer cognitive insights for advancing their capabilities.

[Arxiv](https://arxiv.org/abs/2509.04866)