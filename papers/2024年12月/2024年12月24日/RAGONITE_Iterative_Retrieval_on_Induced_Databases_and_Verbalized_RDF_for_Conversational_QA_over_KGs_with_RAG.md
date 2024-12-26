# RAGONITE：针对基于 RAG 对知识图谱进行对话式问答，在诱导数据库上进行迭代检索以及语言化 RDF

发布时间：2024年12月24日

`RAG` `知识图谱`

> RAGONITE: Iterative Retrieval on Induced Databases and Verbalized RDF for Conversational QA over KGs with RAG

# 摘要

> 对话式问答（ConvQA）是在 RDF 知识图谱（KGs）上进行搜索的便捷手段，常见做法是把自然语言问题转化为 SPARQL 查询。然而，SPARQL 存在一些缺陷：（一）面对复杂意图和对话问题时表现脆弱；（二）难以满足更抽象的需求。为此，我们提出了一个全新的双管齐下的系统，融合了：（一）从 KG 自动衍生的数据库上的 SQL 查询结果；（二）KG 事实表述的文本搜索结果。我们的流程支持迭代检索，若任何分支的结果不令人满意，系统会自动选择进行更多轮次。我们将所有内容整合在一个检索增强生成（RAG）的架构中，由大型语言模型（LLM）根据累积的搜索结果生成连贯的响应。在宝马汽车的知识图谱上，我们证明了所提系统优于多个基线。

> Conversational question answering (ConvQA) is a convenient means of searching over RDF knowledge graphs (KGs), where a prevalent approach is to translate natural language questions to SPARQL queries. However, SPARQL has certain shortcomings: (i) it is brittle for complex intents and conversational questions, and (ii) it is not suitable for more abstract needs. Instead, we propose a novel two-pronged system where we fuse: (i) SQL-query results over a database automatically derived from the KG, and (ii) text-search results over verbalizations of KG facts. Our pipeline supports iterative retrieval: when the results of any branch are found to be unsatisfactory, the system can automatically opt for further rounds. We put everything together in a retrieval augmented generation (RAG) setup, where an LLM generates a coherent response from accumulated search results. We demonstrate the superiority of our proposed system over several baselines on a knowledge graph of BMW automobiles.

[Arxiv](https://arxiv.org/abs/2412.17690)