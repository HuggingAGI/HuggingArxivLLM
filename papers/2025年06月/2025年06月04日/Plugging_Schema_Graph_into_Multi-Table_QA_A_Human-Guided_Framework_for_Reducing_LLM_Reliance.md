# 将模式图融入多表格问答：一个降低LLM依赖的人类引导框架

发布时间：2025年06月04日

`LLM应用` `表格问答` `工业应用`

> Plugging Schema Graph into Multi-Table QA: A Human-Guided Framework for Reducing LLM Reliance

# 摘要

> 大型语言模型（LLMs）在表格问答（Table QA）领域展现出巨大潜力。然而，多表问答的扩展仍具挑战性，主要源于复杂表格间不可靠的模式关联。现有基于语义相似性的方法仅适用于简化的人工设计数据集，在处理复杂、现实场景中拥有众多多样列的情况时表现乏力。为解决这一难题，我们提出了一种基于图的框架，利用人工整理的关系知识显式编码模式关联和连接路径。面对自然语言查询，我们的方法通过剪枝和子路径合并策略辅助，在此图中搜索以构建可解释的推理链，从而提升效率和连贯性。在标准基准测试和一个真实大规模数据集上的实验结果验证了我们方法的有效性。据我们所知，这是首个成功应用于真正复杂工业表格数据的多表问答系统。

> Large language models (LLMs) have shown promise in table Question Answering (Table QA). However, extending these capabilities to multi-table QA remains challenging due to unreliable schema linking across complex tables. Existing methods based on semantic similarity work well only on simplified hand-crafted datasets and struggle to handle complex, real-world scenarios with numerous and diverse columns. To address this, we propose a graph-based framework that leverages human-curated relational knowledge to explicitly encode schema links and join paths. Given a natural language query, our method searches this graph to construct interpretable reasoning chains, aided by pruning and sub-path merging strategies to enhance efficiency and coherence. Experiments on both standard benchmarks and a realistic, large-scale dataset demonstrate the effectiveness of our approach. To our knowledge, this is the first multi-table QA system applied to truly complex industrial tabular data.

[Arxiv](https://arxiv.org/abs/2506.04427)