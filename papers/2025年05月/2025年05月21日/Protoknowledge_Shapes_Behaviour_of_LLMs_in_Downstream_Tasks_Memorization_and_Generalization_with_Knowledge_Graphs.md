# 知识原型对LLMs下游任务行为的影响：基于知识图谱的记忆与泛化能力

发布时间：2025年05月21日

`LLM理论` `知识图谱`

> Protoknowledge Shapes Behaviour of LLMs in Downstream Tasks: Memorization and Generalization with Knowledge Graphs

# 摘要

> 我们提出“proto知识”这一概念，用于形式化和量化大型语言模型（LLMs）在预训练过程中如何内化知识图谱的代号序列，以及在推理时如何运用这些序列。LLMs在预训练中展现出记住大量代号序列的能力，但如何通过泛化将这些记忆转化为可复用的知识仍是未解之谜。我们根据需要激活的知识类型，将proto知识划分为词汇、层次和拓扑三种形式。通过知识激活任务（KATs），我们分析了proto知识的语义偏差等特性。随后，我们研究了不同提示策略对Text-to-SPARQL性能的影响，根据输入条件调整策略。为此，我们采用了一种新型分析框架，评估模型预测是否与相关proto知识的成功激活相匹配。此方法为探索语义级别数据污染提供了实用工具，并成为闭式预训练模型的有效策略。

> We introduce the concept of protoknowledge to formalize and measure how sequences of tokens encoding Knowledge Graphs are internalized during pretraining and utilized at inference time by Large Language Models (LLMs). Indeed, LLMs have demonstrated the ability to memorize vast amounts of token sequences during pretraining, and a central open question is how they leverage this memorization as reusable knowledge through generalization. We then categorize protoknowledge into lexical, hierarchical, and topological forms, varying on the type of knowledge that needs to be activated. We measure protoknowledge through Knowledge Activation Tasks (KATs), analyzing its general properties such as semantic bias. We then investigate the impact of protoknowledge on Text-to-SPARQL performance by varying prompting strategies depending on input conditions. To this end, we adopt a novel analysis framework that assesses whether model predictions align with the successful activation of the relevant protoknowledge for each query. This methodology provides a practical tool to explore Semantic-Level Data Contamination and serves as an effective strategy for Closed-Pretraining models.

[Arxiv](https://arxiv.org/abs/2505.15501)