# 大型语言模型于事实核查中的逻辑一致性

发布时间：2024年12月20日

`LLM应用` `知识图谱`

> Logical Consistency of Large Language Models in Fact-checking

# 摘要

> 近年来，大型语言模型（LLMs）在诸如语言翻译、问答、总结、事实核查等各类自然语言任务中表现出色。尽管LLMs生成类人文本的能力出众，但却因回答的不一致性饱受诟病——输入查询中意义不变的变化会引发不一致的回答，这归因于LLMs的诸如幻觉、越狱等漏洞。所以，现有的研究聚焦于对LLMs基于简单改写的一致性评估，而忽视了复杂查询，而复杂查询需要LLMs具备更强的逻辑推理理解能力。正因如此，我们的工作致力于解决LLMs在具有原始逻辑运算符（如否定、合取和析取）的复杂逻辑查询下的逻辑不一致问题。作为测试基础，我们在涉及来自真实世界知识图谱（KGs）的命题逻辑查询的事实核查任务中，考虑使用检索增强型LLMs。我们的贡献主要有三个方面。基准：我们为社区开发引入了三个基于KGs的逻辑事实核查数据集，以助力实现逻辑一致的LLMs。评估：我们提出了LLMs对于作为输入的命题逻辑查询的一致性衡量标准，并表明现有的LLMs缺乏逻辑一致性，尤其是在复杂查询方面。改进：我们运用监督微调来提升LLMs在具有KG上下文的复杂事实核查任务中的逻辑一致性。

> In recent years, large language models (LLMs) have demonstrated significant success in performing varied natural language tasks such as language translation, question-answering, summarizing, fact-checking, etc. Despite LLMs' impressive ability to generate human-like texts, LLMs are infamous for their inconsistent responses -- a meaning-preserving change in the input query results in an inconsistent response and attributes to vulnerabilities of LLMs such as hallucination, jailbreaking, etc. Consequently, existing research focuses on simple paraphrasing-based consistency assessment of LLMs, and ignores complex queries that necessitates an even better understanding of logical reasoning by an LLM. Our work therefore addresses the logical inconsistency of LLMs under complex logical queries with primitive logical operators, e.g., negation, conjunction, and disjunction. As a test bed, we consider retrieval-augmented LLMs on a fact-checking task involving propositional logic queries from real-world knowledge graphs (KGs). Our contributions are three-fold. Benchmark: We introduce three logical fact-checking datasets over KGs for community development towards logically consistent LLMs. Assessment: We propose consistency measures of LLMs on propositional logic queries as input and demonstrate that existing LLMs lack logical consistency, specially on complex queries. Improvement: We employ supervised fine-tuning to improve the logical consistency of LLMs on the complex fact-checking task with KG contexts.

[Arxiv](https://arxiv.org/abs/2412.16100)