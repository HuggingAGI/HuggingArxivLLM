# 基于大型语言模型的金属增材制造知识图谱决策支持

发布时间：2025年05月20日

`LLM应用

理由：这篇论文主要探讨了大型语言模型（LLM）在金属增材制造领域的应用，通过构建知识图谱和自然语言接口，为工程师提供决策支持。这属于LLM的实际应用案例，因此归类为LLM应用。` `制造业` `工程设计`

> Large Language Model-Powered Decision Support for a Metal Additive Manufacturing Knowledge Graph

# 摘要

> 金属增材制造（AM）涉及工艺、材料、粉末类型和后处理步骤之间的复杂相互作用。然而，这些底层关系和专业知识在文献和静态数据库中仍然分散，通常需要专家级查询，限制了它们在设计和规划中的应用。为了解决这些问题，我们开发了一个新颖且可查询的知识图谱（KG），使用Neo4j编码了七种材料家族中的53种不同金属和合金、九种AM工艺、四种粉末类型及其相关的后处理要求。一个大型语言模型（LLM）界面，由少量样本提示策略引导，支持自然语言查询，无需正式查询语法。该系统支持多种任务，包括兼容性检查、多约束过滤和增材制造设计（DfAM）指导。用户自然语言查询经过规范化处理，翻译成Cypher，然后在KG上执行，结果重新格式化为结构化响应。这项工作首次提出了一种实时交互系统，将特定领域的金属AM知识图谱与LLM界面相结合，为工程师提供可解释的决策支持，并推动以人为中心的制造智能工具的发展。

> Metal additive manufacturing (AM) involves complex interdependencies among processes, materials, feedstock, and post-processing steps. However, the underlying relationships and domain knowledge remain fragmented across literature and static databases that often demand expert-level queries, limiting their applicability in design and planning. To address these gaps, we develop a novel and queryable knowledge graph (KG) in Neo4j, encoding 53 distinct metals and alloys across seven material families, nine AM processes, four feedstock types, and associated post-processing requirements. A large language model (LLM) interface, guided by a few-shot prompting strategy, enables natural language querying without the need for formal query syntax. The system supports a range of tasks, including compatibility checks, multi-constraint filtering, and design for AM (DfAM) guidance. User natural language queries are normalized, translated into Cypher, and executed over the KG, with results reformatted into structured responses. This work presents the first real-time, interactive system that integrates a domain-specific metal AM KG with an LLM interface, offering accessible, explainable decision support for engineers and advancing human-centric tools in manufacturing intelligence.

[Arxiv](https://arxiv.org/abs/2505.20308)