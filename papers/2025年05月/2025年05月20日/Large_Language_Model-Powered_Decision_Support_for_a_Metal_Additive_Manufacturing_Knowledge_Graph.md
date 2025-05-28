# # 大型语言模型赋能的金属增材制造知识图谱决策支持

发布时间：2025年05月20日

`LLM应用` `制造业` `知识图谱`

> Large Language Model-Powered Decision Support for a Metal Additive Manufacturing Knowledge Graph

# 摘要

> # 金属增材制造（AM）知识图谱与大语言模型接口  
金属增材制造涉及工艺、材料、送粉和后处理步骤之间的复杂相互依赖关系。然而，这些潜在关系和专业知识在文献和静态数据库中分散且难以获取，通常需要专家级查询，限制了其在设计和规划中的应用。  
为了填补这一空白，我们在 Neo4j 中开发了一个新颖且可查询的知识图谱（KG），涵盖七种材料家族的 53 种金属和合金、九种 AM 工艺、四种送粉类型以及相关后处理要求。  
我们还设计了一个由少量提示策略引导的大语言模型（LLM）接口，支持自然语言查询，无需正式语法。该系统可执行兼容性检查、多约束过滤和增材制造设计（DfAM）指导等任务。用户的自然语言查询经过处理后转化为 Cypher 查询语句，并在知识图谱上执行，结果以结构化形式呈现。  
这是首个实时交互式系统，将特定领域的金属 AM 知识图谱与 LLM 接口相结合，为工程师提供可访问、可解释的决策支持，推动以人为中心的制造智能工具的发展。

> Metal additive manufacturing (AM) involves complex interdependencies among processes, materials, feedstock, and post-processing steps. However, the underlying relationships and domain knowledge remain fragmented across literature and static databases that often demand expert-level queries, limiting their applicability in design and planning. To address these gaps, we develop a novel and queryable knowledge graph (KG) in Neo4j, encoding 53 distinct metals and alloys across seven material families, nine AM processes, four feedstock types, and associated post-processing requirements. A large language model (LLM) interface, guided by a few-shot prompting strategy, enables natural language querying without the need for formal query syntax. The system supports a range of tasks, including compatibility checks, multi-constraint filtering, and design for AM (DfAM) guidance. User natural language queries are normalized, translated into Cypher, and executed over the KG, with results reformatted into structured responses. This work presents the first real-time, interactive system that integrates a domain-specific metal AM KG with an LLM interface, offering accessible, explainable decision support for engineers and advancing human-centric tools in manufacturing intelligence.

[Arxiv](https://arxiv.org/abs/2505.20308)