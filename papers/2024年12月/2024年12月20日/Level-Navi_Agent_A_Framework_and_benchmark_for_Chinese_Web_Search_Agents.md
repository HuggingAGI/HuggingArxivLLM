# Level-Navi 代理：中文网络搜索代理的框架与基准

发布时间：2024年12月20日

`Agent

论文摘要：大型语言模型（LLMs）推动了人工智能网络搜索代理的发展，与传统搜索引擎相比，基于LLMs的AI搜索代理能够更深入地理解和回应复杂查询，实现更精准的操作和更好的上下文识别。然而，中文网络搜索却未得到应有的关注，开源模型的能力未能得到统一和公平的评估。这一问题的难点在于缺乏统一的代理框架、准确标注的数据集以及合适的评估指标。为此，我们提出了一种基于层次感知导航的通用无训练网络搜索代理——Level-Navi Agent，并附带了一个标注良好的数据集（Web24）和一个合适的评估指标。Level-Navi Agent能够通过复杂用户问题进行思考，并在互联网上跨多个层次进行搜索以收集信息。同时，我们在公平的设置下对最先进的LLMs进行了全面评估。为了进一步促进未来研究，源代码可在Github上获取。

Agent` `搜索引擎` `人工智能`

> Level-Navi Agent: A Framework and benchmark for Chinese Web Search Agents

# 摘要

> 大型语言模型（LLMs）推动了人工智能网络搜索代理的发展，与传统搜索引擎相比，基于LLMs的AI搜索代理能够更深入地理解和回应复杂查询，实现更精准的操作和更好的上下文识别。然而，中文网络搜索却未得到应有的关注，开源模型的能力未能得到统一和公平的评估。这一问题的难点在于缺乏统一的代理框架、准确标注的数据集以及合适的评估指标。为此，我们提出了一种基于层次感知导航的通用无训练网络搜索代理——Level-Navi Agent，并附带了一个标注良好的数据集（Web24）和一个合适的评估指标。Level-Navi Agent能够通过复杂用户问题进行思考，并在互联网上跨多个层次进行搜索以收集信息。同时，我们在公平的设置下对最先进的LLMs进行了全面评估。为了进一步促进未来研究，源代码可在Github上获取。

> Large language models (LLMs), adopted to understand human language, drive the development of artificial intelligence (AI) web search agents. Compared to traditional search engines, LLM-powered AI search agents are capable of understanding and responding to complex queries with greater depth, enabling more accurate operations and better context recognition. However, little attention and effort has been paid to the Chinese web search, which results in that the capabilities of open-source models have not been uniformly and fairly evaluated. The difficulty lies in lacking three aspects: an unified agent framework, an accurately labeled dataset, and a suitable evaluation metric. To address these issues, we propose a general-purpose and training-free web search agent by level-aware navigation, Level-Navi Agent, accompanied by a well-annotated dataset (Web24) and a suitable evaluation metric. Level-Navi Agent can think through complex user questions and conduct searches across various levels on the internet to gather information for questions. Meanwhile, we provide a comprehensive evaluation of state-of-the-art LLMs under fair settings. To further facilitate future research, source code is available at Github.

[Arxiv](https://arxiv.org/abs/2502.15690)