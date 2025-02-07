# 以少胜多——基于大型语言模型的系统路由策略实现：扩展调查

发布时间：2025年02月04日

`Agent

理由：这篇论文主要讨论了如何通过路由机制将用户查询导向最合适的组件（如小型LLM或特定领域的专家），以优化资源管理和降低成本。这种路由机制是对话代理（Agent）架构中的关键部分，旨在提升响应质量和效率。因此，这篇论文的核心内容与Agent的设计和优化密切相关，适合归类为Agent。` `资源管理`

> Doing More with Less -- Implementing Routing Strategies in Large Language Model-Based Systems: An Extended Survey

# 摘要

> # 摘要
基于大型语言模型（LLM）的系统，如对话代理，通常采用单一静态架构，依赖单个LLM处理所有用户查询。然而，这些系统往往需要不同的预处理策略、推理水平或知识。通用LLM（如GPT-4）在广泛的多主题语料库上训练，能在多种任务中表现出色，但其高昂的财务、能源和硬件资源投入对于简单任务可能并不划算。这意味着用户查询可能会带来不必要的成本。为解决这一问题，路由机制将用户查询导向最合适的组件，如小型LLM或特定领域的专家，从而在提升响应质量的同时降低成本。路由机制还可扩展至对话代理架构的其他部分，如选择最佳嵌入策略。本文探讨了将路由机制集成到LLM系统中的关键因素，重点关注资源管理、成本定义和策略选择。我们的主要贡献包括问题的形式化、现有方法的新分类法（强调相关性和资源效率），以及这些策略与行业实践的比较分析。最后，我们指出了未来研究的关键挑战和方向。

> Large Language Models (LLM)-based systems, i.e. interconnected elements that include an LLM as a central component (e.g., conversational agents), are typically monolithic static architectures that rely on a single LLM for all user queries. However, they often require different preprocessing strategies, levels of reasoning, or knowledge. Generalist LLMs (e.g. GPT-4) trained on very large multi-topic corpora can perform well in a variety of tasks. They require significant financial, energy, and hardware resources that may not be justified for basic tasks. This implies potentially investing in unnecessary costs for a given query. To overcome this problem, a routing mechanism routes user queries to the most suitable components, such as smaller LLMs or experts in specific topics. This approach may improve response quality while minimising costs. Routing can be expanded to other components of the conversational agent architecture, such as the selection of optimal embedding strategies. This paper explores key considerations for integrating routing into LLM-based systems, focusing on resource management, cost definition, and strategy selection. Our main contributions include a formalisation of the problem, a novel taxonomy of existing approaches emphasising relevance and resource efficiency, and a comparative analysis of these strategies in relation to industry practices. Finally, we identify critical challenges and directions for future research.

[Arxiv](https://arxiv.org/abs/2502.00409)