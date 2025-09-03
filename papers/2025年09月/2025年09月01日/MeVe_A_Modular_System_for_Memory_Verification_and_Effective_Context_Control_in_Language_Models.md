# MeVe：面向语言模型的记忆验证与有效上下文控制模块化系统

发布时间：2025年09月01日

`RAG` `基础理论`

> MeVe: A Modular System for Memory Verification and Effective Context Control in Language Models

# 摘要

> 检索增强生成（RAG）系统往往受限于其固有机制——简单的top-k语义搜索[1]。这种方式容易让上下文中混入无关或冗余信息，进而影响性能与效率[10][11]。为此，本文提出了MeVe——一种用于记忆验证与智能上下文组合的新型模块化架构。MeVe重新构想了RAG范式，提出五阶段模块化设计，将检索与上下文组合流程清晰拆分为五个独立、可审计且可单独调优的阶段：初始检索、相关性验证、后备检索、上下文优先级排序及令牌预算分配。该架构可对LLM获取的知识进行细粒度把控，支持基于任务的过滤与适配。我们发布了MeVe的参考实现以作概念验证，并在英语维基百科子集上，针对知识密集型问答任务评估了其性能[22]。结果显示，通过在组合前主动验证信息，MeVe大幅提升了上下文效率——与标准RAG实现相比，维基百科数据集上的上下文信息减少57%，而在更复杂的HotpotQA数据集上减少75%[25]。这项研究为更具扩展性和可靠性的LLM应用提供了框架。通过精炼和提纯上下文信息，MeVe为LLM奠定更扎实的基础、提供更准确的事实支撑开辟了新路径[16]。

> Retrieval-Augmented Generation (RAG) systems typically face constraints because of their inherent mechanism: a simple top-k semantic search [1]. The approach often leads to the incorporation of irrelevant or redundant information in the context, degrading performance and efficiency [10][11]. This paper presents MeVe, a novel modular architecture intended for Memory Verification and smart context composition. MeVe rethinks the RAG paradigm by proposing a five-phase modular design that distinctly breaks down the retrieval and context composition process into distinct, auditable, and independently tunable phases: initial retrieval, relevance verification, fallback retrieval, context prioritization, and token budgeting. This architecture enables fine-grained control of what knowledge is made available to an LLM, enabling task-dependent filtering and adaptation. We release a reference implementation of MeVe as a proof of concept and evaluate its performance on knowledge-heavy QA tasks over a subset of English Wikipedia [22]. Our results demonstrate that by actively verifying information before composition, MeVe significantly improves context efficiency, achieving a 57% reduction on the Wikipedia dataset and a 75% reduction on the more complex HotpotQA dataset compared to standard RAG implementations [25]. This work provides a framework for more scalable and reliable LLM applications. By refining and distilling contextual information, MeVe offers a path toward better grounding and more accurate factual support [16].

[Arxiv](https://arxiv.org/abs/2509.01514)