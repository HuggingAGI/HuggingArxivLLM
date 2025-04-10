# FamilyTool：多步骤个性化工具使用基准测试

发布时间：2025年04月09日

`LLM应用` `知识图谱`

> FamilyTool: A Multi-hop Personalized Tool Use Benchmark

# 摘要

> 工具学习与大型语言模型（LLMs）的结合显著提升了其处理复杂任务的能力，通过借助外部工具实现。然而，现有的工具学习基准在应对关键的现实个性化场景时表现不足，尤其在需要多跳推理和动态环境下的归纳知识适应方面。为填补这一空白，我们推出FamilyTool，这是一个基于家庭知识图谱（KG）的新基准，模拟个性化、多跳工具使用场景。FamilyTool通过1到3个关系跳数的查询（如推断家庭关系和偏好）对LLMs提出挑战，并引入归纳KG设置，要求模型在无需重新训练的情况下适应未见的用户偏好和关系，这是先前方法常见的局限性，影响了其泛化能力。我们进一步提出KGETool：一个简单的KG增强评估流水线，系统性评估LLMs在这些设置下的工具使用能力。实验结果揭示了当前先进LLMs性能上的显著差距，准确率随着跳数复杂度增加而急剧下降，归纳场景则暴露了严重的泛化缺陷。这些发现凸显了现有LLMs在处理个性化、动态演变现实情境中的局限性，凸显了工具学习框架取得进展的迫切需求。FamilyTool为评估和提升LLM代理在复杂动态环境中的推理、适应和扩展能力提供了关键资源。代码和数据集可在GitHub上获取。

> The integration of tool learning with Large Language Models (LLMs) has expanded their capabilities in handling complex tasks by leveraging external tools. However, existing benchmarks for tool learning inadequately address critical real-world personalized scenarios, particularly those requiring multi-hop reasoning and inductive knowledge adaptation in dynamic environments. To bridge this gap, we introduce FamilyTool, a novel benchmark grounded in a family-based knowledge graph (KG) that simulates personalized, multi-hop tool use scenarios. FamilyTool challenges LLMs with queries spanning 1 to 3 relational hops (e.g., inferring familial connections and preferences) and incorporates an inductive KG setting where models must adapt to unseen user preferences and relationships without re-training, a common limitation in prior approaches that compromises generalization. We further propose KGETool: a simple KG-augmented evaluation pipeline to systematically assess LLMs' tool use ability in these settings. Experiments reveal significant performance gaps in state-of-the-art LLMs, with accuracy dropping sharply as hop complexity increases and inductive scenarios exposing severe generalization deficits. These findings underscore the limitations of current LLMs in handling personalized, evolving real-world contexts and highlight the urgent need for advancements in tool-learning frameworks. FamilyTool serves as a critical resource for evaluating and advancing LLM agents' reasoning, adaptability, and scalability in complex, dynamic environments. Code and dataset are available at Github.

[Arxiv](https://arxiv.org/abs/2504.06766)