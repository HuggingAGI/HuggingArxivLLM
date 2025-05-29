# # 可视化在LLM驱动的知识图系统中的作用：对用户信任、探索行为及工作流的影响

发布时间：2025年05月20日

`LLM应用` `知识图谱` `可视化分析`

> The Role of Visualization in LLM-Assisted Knowledge Graph Systems: Effects on User Trust, Exploration, and Workflows

# 摘要

> 知识图谱（KGs）是一种强大的数据结构，但即使是专家用户，有效探索它们仍然充满挑战。大型语言模型（LLMs）越来越多地被用来填补这一空白，然而，关于它们与KGs结合使用如何影响用户的信任、探索策略或下游决策，目前还缺乏实证研究——这为基于LLM的知识图谱可视化分析系统提出了关键的设计挑战。为了研究这些影响，我们开发了LinkQ，一个将自然语言问题转化为结构化查询的KG探索系统。我们与KG专家合作，设计了五种视觉机制，帮助用户评估KG查询和LLM响应的准确性：一个显示LinkQ处于探索管道哪个阶段的LLM-KG状态图，一个显示生成的查询并附带LLM解释的查询编辑器，一个显示提取的KG实体和关系及其语义描述的实体-关系ID表，一个展示在KG中遍历路径的查询结构图，以及一个交互式的查询结果图形可视化。通过与14位实践者的定性评估，我们发现，用户——即使是KG专家——往往会过度信任LinkQ的输出，因为其“有用”的可视化，即使LLM是错误的。用户的操作流程因他们对KGs和LLMs的先前熟悉程度而异，这挑战了这些系统是“万能钥匙”的假设——尽管它们通常被设计成这样。我们的研究结果突显了对LLM辅助数据分析工具的虚假信任的风险，并强调了进一步研究可视化作为缓解技术作用的必要性。

> Knowledge graphs (KGs) are powerful data structures, but exploring them effectively remains difficult for even expert users. Large language models (LLMs) are increasingly used to address this gap, yet little is known empirically about how their usage with KGs shapes user trust, exploration strategies, or downstream decision-making - raising key design challenges for LLM-based KG visual analysis systems. To study these effects, we developed LinkQ, a KG exploration system that converts natural language questions into structured queries with an LLM. We collaborated with KG experts to design five visual mechanisms that help users assess the accuracy of both KG queries and LLM responses: an LLM-KG state diagram that illustrates which stage of the exploration pipeline LinkQ is in, a query editor displaying the generated query paired with an LLM explanation, an entity-relation ID table showing extracted KG entities and relations with semantic descriptions, a query structure graph that depicts the path traversed in the KG, and an interactive graph visualization of query results. From a qualitative evaluation with 14 practitioners, we found that users - even KG experts - tended to overtrust LinkQ's outputs due to its "helpful" visualizations, even when the LLM was incorrect. Users exhibited distinct workflows depending on their prior familiarity with KGs and LLMs, challenging the assumption that these systems are one-size-fits-all - despite often being designed as if they are. Our findings highlight the risks of false trust in LLM-assisted data analysis tools and the need for further investigation into the role of visualization as a mitigation technique.

[Arxiv](https://arxiv.org/abs/2505.21512)