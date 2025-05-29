# 可视化在基于LLM的知识图谱系统中的作用：对用户信任、探索行为及工作流程的影响

发布时间：2025年05月20日

`LLM应用` `知识图谱` `可视化分析系统`

> The Role of Visualization in LLM-Assisted Knowledge Graph Systems: Effects on User Trust, Exploration, and Workflows

# 摘要

> 知识图谱（KGs）作为强大的数据结构，尽管功能强大，但即使是经验丰富的专家用户，也常常感到难以高效地进行探索。大型语言模型（LLMs）正被越来越多地用于弥补这一差距，然而，从实证角度而言，我们对将LLMs与KGs结合使用如何影响用户的信任度、探索策略或下游决策过程知之甚少。这一现状为基于LLMs的知识图谱可视化分析系统的设计带来了关键挑战。

为了研究这些影响，我们开发了LinkQ，一个能够将自然语言问题转化为结构化查询的KG探索系统，该系统采用了LLMs技术。我们与KG专家合作，设计了五种可视化机制，旨在帮助用户评估KG查询和LLMs响应的准确性：

1. **LLM-KG状态图**：展示LinkQ当前所处的探索管道阶段。
2. **查询编辑器**：显示生成的查询并附带LLMs的解释。
3. **实体-关系ID表**：展示从KG中提取的实体和关系及其语义描述。
4. **查询结构图**：展示在KG中遍历的路径。
5. **交互式图表**：用于可视化查询结果。

在对14名实践者的定性评估中，我们发现，用户——甚至包括KG专家——往往会过度信任LinkQ的输出结果，这归因于其“有用”的可视化效果，即使LLMs的回答有误。用户的操作流程因他们对KGs和LLMs的先前熟悉程度而异，这挑战了这些系统是“万能钥匙”的假设——尽管它们通常被设计成这样。我们的研究发现突显了对LLM辅助数据分析工具产生过度信任的风险，并强调了进一步研究可视化在缓解此类风险中的作用的必要性。


> Knowledge graphs (KGs) are powerful data structures, but exploring them effectively remains difficult for even expert users. Large language models (LLMs) are increasingly used to address this gap, yet little is known empirically about how their usage with KGs shapes user trust, exploration strategies, or downstream decision-making - raising key design challenges for LLM-based KG visual analysis systems. To study these effects, we developed LinkQ, a KG exploration system that converts natural language questions into structured queries with an LLM. We collaborated with KG experts to design five visual mechanisms that help users assess the accuracy of both KG queries and LLM responses: an LLM-KG state diagram that illustrates which stage of the exploration pipeline LinkQ is in, a query editor displaying the generated query paired with an LLM explanation, an entity-relation ID table showing extracted KG entities and relations with semantic descriptions, a query structure graph that depicts the path traversed in the KG, and an interactive graph visualization of query results. From a qualitative evaluation with 14 practitioners, we found that users - even KG experts - tended to overtrust LinkQ's outputs due to its "helpful" visualizations, even when the LLM was incorrect. Users exhibited distinct workflows depending on their prior familiarity with KGs and LLMs, challenging the assumption that these systems are one-size-fits-all - despite often being designed as if they are. Our findings highlight the risks of false trust in LLM-assisted data analysis tools and the need for further investigation into the role of visualization as a mitigation technique.

[Arxiv](https://arxiv.org/abs/2505.21512)