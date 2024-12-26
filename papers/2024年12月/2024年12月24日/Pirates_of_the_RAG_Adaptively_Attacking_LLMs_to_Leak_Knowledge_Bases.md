# 《RAG 之海盗：自适应攻击 LLMs 以泄露知识库》

发布时间：2024年12月24日

`RAG` `信息安全` `隐私保护`

> Pirates of the RAG: Adaptively Attacking LLMs to Leak Knowledge Bases

# 摘要

> 检索增强生成（RAG）系统在众多现实服务中的广泛应用，引发了对其安全性的深切担忧。RAG 系统借助在私有知识库上运作的检索机制提升大型语言模型（LLM）的生成能力，而其意外暴露可能导致严重后果，比如私人及敏感信息的泄露。本文给出了一种黑盒攻击，能迫使 RAG 系统泄漏其私有知识库，与现有方法不同，此攻击具有适应性和自动化特点。基于相关性的机制以及攻击者端的开源 LLM 有助于生成有效的查询，从而泄露大部分（隐藏）知识库。大量实验证实了所提算法在不同 RAG 管道和领域中的质量，与近期相关方法相比，那些方法要么并非完全黑盒，要么不具适应性，要么不是基于开源模型。我们的研究结果凸显了在 RAG 系统的设计和部署中，对更有力的隐私保护措施的迫切需求。

> The growing ubiquity of Retrieval-Augmented Generation (RAG) systems in several real-world services triggers severe concerns about their security. A RAG system improves the generative capabilities of a Large Language Models (LLM) by a retrieval mechanism which operates on a private knowledge base, whose unintended exposure could lead to severe consequences, including breaches of private and sensitive information. This paper presents a black-box attack to force a RAG system to leak its private knowledge base which, differently from existing approaches, is adaptive and automatic. A relevance-based mechanism and an attacker-side open-source LLM favor the generation of effective queries to leak most of the (hidden) knowledge base. Extensive experimentation proves the quality of the proposed algorithm in different RAG pipelines and domains, comparing to very recent related approaches, which turn out to be either not fully black-box, not adaptive, or not based on open-source models. The findings from our study remark the urgent need for more robust privacy safeguards in the design and deployment of RAG systems.

[Arxiv](https://arxiv.org/abs/2412.18295)