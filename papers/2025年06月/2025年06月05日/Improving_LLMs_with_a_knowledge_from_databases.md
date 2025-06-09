# 从数据库中获取知识来改进大型语言模型

发布时间：2025年06月05日

`RAG` `问答系统` `数据挖掘`

> Improving LLMs with a knowledge from databases

# 摘要

> 大型语言模型（LLMs）几乎在每个时刻都在取得显著进展。许多高级技术已被引入并被广泛接受，例如检索增强生成（RAG）、智能体和工具。工具能够通过查询数据库来回答结构化数据文件中的问题，或者执行分组或其他统计操作。这解锁了巨大的机会，例如可以回答任何问题，但也带来了威胁，例如安全问题，因为无法控制生成的命令。我们希望探讨是否可以创建一种新方法，通过一些可解释的机器学习方法（即增强关联规则）来改进基于数据集/数据库的答案。优势在于，该方法也可以用于一些安全技术，如RAG。关联规则有着悠久的历史。自从引入CN2和Apriori以来，已经进行了许多改进。与此同时，增强关联规则在过去40年中被引入并不断发展。通常的问题是规则数量过多。有一些处理它的技术，但当LLM出现时，事实证明它是LLM中RAG技术的最佳用例。我们提出了一种基于定义的知识模式生成规则集的方法，然后通过规则到文本的转换器将规则转换为文本形式，并将结果作为RAG包含在LLM中。我们将此方法与ChatGPT（甚至使用智能体）进行了比较，并发现基于数据集回答问题有了显著改进。我们还尝试了多种策略来确定生成多少规则。我们发现这种改进很有趣。此外，未来的工作还可以通过多种方式进一步改进，例如引入其他模式、将规则挖掘用作智能体，等等。

> Large language models (LLMs) are achieving significant progress almost every moment now. Many advanced techniques have been introduced and widely accepted, like retrieval-augmentation generation (RAG), agents, and tools. Tools can query the database to answer questions from structured data files or perform groupings or other statistics. This unlocks huge opportunities, such as it can answer any question, but also poses threats, such as safety, because there is no control over the commands that are created. We would like to discuss whether we can create a new method that improves answers based on dataset/database via some interpretable ML methods, namely enhanced association rules. The advantage would be if the method can be also used in some safe technique like RAG. Association rules have a sound history. Since the introduction of CN2 and aproiri, many enhancements have been made. In parallel, enhanced association rules have been introduced and evolved over the last 40 years. The general problem is typically that there are too many rules. There are some techniques for handling it, but when LLM emerged, it turned out to be the best use case for the RAG technique for LLMs. We proposed a method that generates a ruleset based on defined knowledge patterns, then converts rules into text form via a rule-to-text converter, and includes the result as an RAG into LLM. We compared this method with ChatGPT (even with using agents) and we have discovered a significant improvement in answering questions based on the dataset. We have also tried several strategies how much rules to generate. We found this improvement interesting. Moreover, it can also be improved in many ways as future work, like incorporating other patterns, the use of rule mining as an agent, and many others.

[Arxiv](https://arxiv.org/abs/2506.05560)