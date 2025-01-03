# NAT-NL2GQL: 一种创新的多智能体框架，实现自然语言到图查询语言的转换

发布时间：2024年12月10日

`Agent

理由：这篇论文提出了一种创新的多代理框架（NAT-NL2GQL），用于自然语言到图查询语言的转换。该框架由三个协同代理组成：预处理代理、生成代理和优化代理。这些代理各自负责不同的任务，并通过协作来解决复杂的NL2GQL问题。因此，这篇论文的核心内容涉及多代理系统的设计和应用，符合“Agent”分类的定义。` `数据库` `金融市场`

> NAT-NL2GQL: A Novel Multi-Agent Framework for Translating Natural Language to Graph Query Language

# 摘要

> 大型语言模型（LLMs）的出现不仅革新了传统的自然语言处理（NLP）任务，还彻底改变了多个领域。最近，LLMs在数据库领域的应用研究蓬勃发展，尤其是在图数据库研究中，LLMs的应用备受关注。当前的研究重点是利用LLMs将自然语言转换为图查询语言（NL2GQL）。尽管已有一些进展，但这些方法存在明显局限，例如依赖简化流程，忽视了LLMs在自主规划和多LLM协作解决复杂NL2GQL问题中的潜力。为此，我们提出了NAT-NL2GQL，一种创新的多代理框架，用于自然语言到图查询语言的转换。该框架由三个协同代理组成：预处理代理、生成代理和优化代理。预处理代理负责数据处理，包括命名实体识别、查询重写、路径链接和模式提取等任务。生成代理是一个经过NL-GQL数据微调的LLM，负责根据查询及其相关模式生成GQL语句。优化代理则利用GQL执行结果中的错误信息优化GQL或上下文。由于基于nGQL语法的高质量开源NL2GQL数据集稀缺，我们开发了StockGQL，这是一个基于金融市场图数据库构建的数据集，可在https://github.com/leonyuancode/StockGQL获取。在StockGQL和SpCQL数据集上的实验表明，我们的方法显著优于基线方法，展现了其在推动NL2GQL研究中的巨大潜力。

> The emergence of Large Language Models (LLMs) has revolutionized many fields, not only traditional natural language processing (NLP) tasks. Recently, research on applying LLMs to the database field has been booming, and as a typical non-relational database, the use of LLMs in graph database research has naturally gained significant attention. Recent efforts have increasingly focused on leveraging LLMs to translate natural language into graph query language (NL2GQL). Although some progress has been made, these methods have clear limitations, such as their reliance on streamlined processes that often overlook the potential of LLMs to autonomously plan and collaborate with other LLMs in tackling complex NL2GQL challenges. To address this gap, we propose NAT-NL2GQL, a novel multi-agent framework for translating natural language to graph query language. Specifically, our framework consists of three synergistic agents: the Preprocessor agent, the Generator agent, and the Refiner agent. The Preprocessor agent manages data processing as context, including tasks such as name entity recognition, query rewriting, path linking, and the extraction of query-related schemas. The Generator agent is a fine-tuned LLM trained on NL-GQL data, responsible for generating corresponding GQL statements based on queries and their related schemas. The Refiner agent is tasked with refining the GQL or context using error information obtained from the GQL execution results. Given the scarcity of high-quality open-source NL2GQL datasets based on nGQL syntax, we developed StockGQL, a dataset constructed from a financial market graph database. It is available at: https://github.com/leonyuancode/StockGQL. Experimental results on the StockGQL and SpCQL datasets reveal that our method significantly outperforms baseline approaches, highlighting its potential for advancing NL2GQL research.

[Arxiv](https://arxiv.org/abs/2412.10434)