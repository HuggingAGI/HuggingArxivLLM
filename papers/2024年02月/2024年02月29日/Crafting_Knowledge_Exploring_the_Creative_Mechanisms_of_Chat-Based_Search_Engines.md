# 精心打造知识：深入探索聊天式搜索引擎背后的创新运作机制

发布时间：2024年02月29日

`RAG`

> Crafting Knowledge: Exploring the Creative Mechanisms of Chat-Based Search Engines

# 摘要

> 搜索引擎作为数字信息传播的核心中介，将信息需求者与供给者紧密相连。以Bing Chat为代表的搭载大型语言模型（LLMs）及检索增强生成（RAG）技术的聊天型搜索引擎，则为搜索生态带来了革新性的跃进。这类引擎展现出类似人类的理解力与创造力，能解读网页信息并精巧回应。然而，LLMs内在的复杂性使得其“思考”过程如同黑箱，即使是设计者也难以完全洞察。本研究致力于深入探究LLM驱动的聊天式搜索引擎（以Bing Chat为例）如何选取信息源生成回答。为了实现这一目标，我们通过与新Bing的实际互动，积累了一个大规模数据集，其中包含它引用的网站及其与常规搜索引擎所列网站的对比情况。运用自然语言处理技术分析发现，Bing Chat更偏好那些既易读、结构规整且困惑度较低的网页内容，这意味着其有独特倾向去选用底层LLM容易预测的文本。我们进一步通过与基于GPT-4知识检索API的互动，收集更多数据，显示了RAG API与Bing Chat在文本偏好的一致性，暗示这类偏好其实源自于底层语言模型的固有特性，而非Bing Chat开发团队刻意编排的结果。此外，我们的研究还揭示了相比传统搜索引擎高排名的网站，RAG技术引用的网站间具有更高的相似度。

> In the domain of digital information dissemination, search engines act as pivotal conduits linking information seekers with providers. The advent of chat-based search engines utilizing Large Language Models (LLMs) and Retrieval Augmented Generation (RAG), exemplified by Bing Chat, marks an evolutionary leap in the search ecosystem. They demonstrate metacognitive abilities in interpreting web information and crafting responses with human-like understanding and creativity. Nonetheless, the intricate nature of LLMs renders their "cognitive" processes opaque, challenging even their designers' understanding. This research aims to dissect the mechanisms through which an LLM-powered chat-based search engine, specifically Bing Chat, selects information sources for its responses. To this end, an extensive dataset has been compiled through engagements with New Bing, documenting the websites it cites alongside those listed by the conventional search engine. Employing natural language processing (NLP) techniques, the research reveals that Bing Chat exhibits a preference for content that is not only readable and formally structured, but also demonstrates lower perplexity levels, indicating a unique inclination towards text that is predictable by the underlying LLM. Further enriching our analysis, we procure an additional dataset through interactions with the GPT-4 based knowledge retrieval API, unveiling a congruent text preference between the RAG API and Bing Chat. This consensus suggests that these text preferences intrinsically emerge from the underlying language models, rather than being explicitly crafted by Bing Chat's developers. Moreover, our investigation documents a greater similarity among websites cited by RAG technologies compared to those ranked highest by conventional search engines.

[Arxiv](https://arxiv.org/abs/2402.19421)