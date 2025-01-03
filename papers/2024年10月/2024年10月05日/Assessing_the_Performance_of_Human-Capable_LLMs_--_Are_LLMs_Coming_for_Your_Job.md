# 评估具备人类能力的LLMs的性能——LLMs会抢走你的饭碗吗？

发布时间：2024年10月05日

`Agent

理由：这篇论文主要讨论了自动化LLM代理在帮助台和专业咨询任务中的表现，并开发了一个新的基准（SelfScore）来评估这些代理的表现。论文的重点在于自动化代理的开发、评估及其在特定任务中的应用，因此属于Agent类别。虽然论文也提到了RAG（Retrieval-Augmented Generation）在特定领域任务中的优势，但核心内容仍然是关于自动化代理的评估和应用，因此更适合归类为Agent。` `客户服务` `人工智能`

> Assessing the Performance of Human-Capable LLMs -- Are LLMs Coming for Your Job?

# 摘要

> 本文介绍了SelfScore的开发和验证，这是一个旨在评估自动化LLM代理在帮助台和专业咨询任务中表现的新基准。随着AI在行业中的广泛应用，特别是在客户服务领域，SelfScore填补了自动化代理与人类工作者之间比较的空白。该基准从问题复杂性和响应有用性两个维度评估代理，确保评分系统的透明和简洁。研究还开发了自动化LLM代理来测试SelfScore，并探索了RAG在特定领域任务中的优势，结果表明结合RAG的自动化LLM代理表现更优。所有自动化LLM代理的表现均超过人类对照组。基于这些结果，研究提出了AI可能取代人类工作者的担忧，特别是在AI技术擅长的领域。最终，SelfScore为理解AI在帮助台环境中的影响提供了基础工具，同时呼吁在自动化转型中重视伦理问题。

> The current paper presents the development and validation of SelfScore, a novel benchmark designed to assess the performance of automated Large Language Model (LLM) agents on help desk and professional consultation tasks. Given the increasing integration of AI in industries, particularly within customer service, SelfScore fills a crucial gap by enabling the comparison of automated agents and human workers. The benchmark evaluates agents on problem complexity and response helpfulness, ensuring transparency and simplicity in its scoring system. The study also develops automated LLM agents to assess SelfScore and explores the benefits of Retrieval-Augmented Generation (RAG) for domain-specific tasks, demonstrating that automated LLM agents incorporating RAG outperform those without. All automated LLM agents were observed to perform better than the human control group. Given these results, the study raises concerns about the potential displacement of human workers, especially in areas where AI technologies excel. Ultimately, SelfScore provides a foundational tool for understanding the impact of AI in help desk environments while advocating for ethical considerations in the ongoing transition towards automation.

[Arxiv](https://arxiv.org/abs/2410.16285)