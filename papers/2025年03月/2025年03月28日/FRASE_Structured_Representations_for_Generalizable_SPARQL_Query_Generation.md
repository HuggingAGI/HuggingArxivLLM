# FRASE：面向可泛化 SPARQL 查询生成的结构化表示

发布时间：2025年03月28日

`LLM应用` `知识图谱`

> FRASE: Structured Representations for Generalizable SPARQL Query Generation

# 摘要

> 将自然语言问题转化为SPARQL查询，能够实现知识库的查询，从而获取事实性且最新的回答。然而，现有用于此任务的数据集主要基于模板，导致模型学习的往往是问题与查询模板之间的表层映射，而非真正具备泛化能力。因此，当模型面对自然表达且无模板的问题时，往往表现挣扎。本文引入了FRASE（基于框架的语义增强）这一创新方法，该方法借助框架语义角色标注（FSRL），旨在克服这一局限。同时，我们推出了LC-QuAD 3.0，这一基于LC-QuAD 2.0的新数据集，其中每个问题均通过FRASE进行了增强，具体方法是通过框架检测以及将框架元素映射至其论元实现的。我们通过在近期大型语言模型（LLMs）上进行广泛实验，评估了该方法在不同微调配置下的效果。实验结果表明，融合基于框架的结构化表示能够显著提升SPARQL生成性能，尤其在面对具有未见模板（未知模板分割）或完全自然表达（重新表述的问题）的测试问题时，展现出更强的泛化能力。

> Translating natural language questions into SPARQL queries enables Knowledge Base querying for factual and up-to-date responses. However, existing datasets for this task are predominantly template-based, leading models to learn superficial mappings between question and query templates rather than developing true generalization capabilities. As a result, models struggle when encountering naturally phrased, template-free questions. This paper introduces FRASE (FRAme-based Semantic Enhancement), a novel approach that leverages Frame Semantic Role Labeling (FSRL) to address this limitation. We also present LC-QuAD 3.0, a new dataset derived from LC-QuAD 2.0, in which each question is enriched using FRASE through frame detection and the mapping of frame-elements to their argument. We evaluate the impact of this approach through extensive experiments on recent large language models (LLMs) under different fine-tuning configurations. Our results demonstrate that integrating frame-based structured representations consistently improves SPARQL generation performance, particularly in challenging generalization scenarios when test questions feature unseen templates (unknown template splits) and when they are all naturally phrased (reformulated questions).

[Arxiv](https://arxiv.org/abs/2503.22144)