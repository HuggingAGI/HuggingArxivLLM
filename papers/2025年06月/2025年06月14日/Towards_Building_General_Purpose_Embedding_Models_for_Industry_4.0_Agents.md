# # 摘要
最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年06月14日

`LLM应用` `工业4.0`

> Towards Building General Purpose Embedding Models for Industry 4.0 Agents

# 摘要

> 本研究聚焦于提升语言模型在资产维护领域的理解能力，以辅助工程师决策并减少资产停机时间。针对工业4.0领域中以自然语言描述的任务，每个任务都与特定资产相关联的查询相关，我们致力于推荐相关项目并将其推广到类似资产的查询。例如，一个任务可能涉及在给定资产故障模式相关查询时识别相关传感器。

我们的方法始于构建一个定性、专家审核的知识库，以形成九个特定于资产的任务数据集。为了生成更具上下文信息的嵌入，我们利用大型语言模型（LLMs）增强输入任务，提供查询中涉及实体的简洁描述。随后，将此嵌入模型与推理和行动代理（ReAct）集成，该代理能够高效处理需要多步骤推理、规划和知识推断的复杂用户查询。

通过消融研究，我们发现：(a) LLM查询增强显著提升了嵌入质量，(b) 对于涉及多个项目的查询数据集，对比损失和其他避免批量内负样本的方法表现更优，(c) 平衡批量内的正负样本至关重要。在我们的数据集上训练和测试后，各项指标均显著提升：HIT@1提高了+54.2%，MAP@100提高了+50.1%，NDCG@10提高了+54.7%，所有任务和模型的平均值。此外，实验证明了模型在回答与工业资产维护相关的复杂问题时的规划和工具调用能力，充分展现了其在支持主题专家（SMEs）日常运营中的有效性。


> In this work we focus on improving language models' understanding for asset maintenance to guide the engineer's decisions and minimize asset downtime. Given a set of tasks expressed in natural language for Industry 4.0 domain, each associated with queries related to a specific asset, we want to recommend relevant items and generalize to queries of similar assets. A task may involve identifying relevant sensors given a query about an asset's failure mode.
  Our approach begins with gathering a qualitative, expert-vetted knowledge base to construct nine asset-specific task datasets. To create more contextually informed embeddings, we augment the input tasks using Large Language Models (LLMs), providing concise descriptions of the entities involved in the queries. This embedding model is then integrated with a Reasoning and Acting agent (ReAct), which serves as a powerful tool for answering complex user queries that require multi-step reasoning, planning, and knowledge inference.
  Through ablation studies, we demonstrate that: (a) LLM query augmentation improves the quality of embeddings, (b) Contrastive loss and other methods that avoid in-batch negatives are superior for datasets with queries related to many items, and (c) It is crucial to balance positive and negative in-batch samples. After training and testing on our dataset, we observe a substantial improvement: HIT@1 increases by +54.2%, MAP@100 by +50.1%, and NDCG@10 by +54.7%, averaged across all tasks and models. Additionally, we empirically demonstrate the model's planning and tool invocation capabilities when answering complex questions related to industrial asset maintenance, showcasing its effectiveness in supporting Subject Matter Experts (SMEs) in their day-to-day operations.

[Arxiv](https://arxiv.org/abs/2506.12607)