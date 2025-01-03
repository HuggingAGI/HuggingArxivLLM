# # 展开头条：迭代自问自答助力新闻检索与时间线摘要

发布时间：2025年01月01日

`LLM应用

理由：这篇论文讨论了如何利用大型语言模型（LLMs）来解决时间线摘要（TLS）任务，具体提出了CHRONOS方法，通过迭代自我提问来生成和更新时间线摘要。这属于LLM在实际应用中的使用，因此归类为LLM应用。` `时间线摘要`

> Unfolding the Headline: Iterative Self-Questioning for News Retrieval and Timeline Summarization

# 摘要

> 在信息瞬息万变的时代，从海量事件内容中构建连贯时间线的能力愈发重要且充满挑战。关键在于如何聚合相关文档，围绕核心主题构建有意义的事件图。本文提出CHRONOS - 通过迭代自我提问实现开放领域新闻时间线摘要的因果标题检索，为利用大型语言模型（LLMs）解决时间线摘要（TLS）任务提供了新思路。通过不断反思事件关联并提出新问题，LLMs能够在线或从离线知识库中收集信息，并基于每轮检索的文档生成和更新时间线摘要。我们还推出了Open-TLS，这是一个由专业记者撰写的近期新闻时间线数据集，用于评估开放领域的TLS，其中信息过载使得从网络上获取全面相关文档变得困难。实验表明，CHRONOS不仅在开放领域时间线摘要上表现出色，而且在封闭领域应用中也能与现有最先进系统一较高下，后者通常提供相关新闻语料库进行摘要。

> In the fast-changing realm of information, the capacity to construct coherent timelines from extensive event-related content has become increasingly significant and challenging. The complexity arises in aggregating related documents to build a meaningful event graph around a central topic. This paper proposes CHRONOS - Causal Headline Retrieval for Open-domain News Timeline SummarizatiOn via Iterative Self-Questioning, which offers a fresh perspective on the integration of Large Language Models (LLMs) to tackle the task of Timeline Summarization (TLS). By iteratively reflecting on how events are linked and posing new questions regarding a specific news topic to gather information online or from an offline knowledge base, LLMs produce and refresh chronological summaries based on documents retrieved in each round. Furthermore, we curate Open-TLS, a novel dataset of timelines on recent news topics authored by professional journalists to evaluate open-domain TLS where information overload makes it impossible to find comprehensive relevant documents from the web. Our experiments indicate that CHRONOS is not only adept at open-domain timeline summarization, but it also rivals the performance of existing state-of-the-art systems designed for closed-domain applications, where a related news corpus is provided for summarization.

[Arxiv](https://arxiv.org/abs/2501.00888)