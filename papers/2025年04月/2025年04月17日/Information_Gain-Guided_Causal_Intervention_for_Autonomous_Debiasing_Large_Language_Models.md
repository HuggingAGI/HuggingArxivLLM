# 信息增益引导的因果干预：实现大型语言模型的自主去偏见

发布时间：2025年04月17日

`LLM理论` `人工智能`

> Information Gain-Guided Causal Intervention for Autonomous Debiasing Large Language Models

# 摘要

> 尽管大型语言模型（LLMs）取得了显著进展，但近期研究表明，它们仍可能捕捉到数据集的偏差并在推理过程中加以利用，导致泛化能力不足。由于数据集偏差的多样性和基于上下文学习的偏见抑制方法的局限性，以往基于先验知识和上下文学习的去偏方法效果有限。为解决这一问题，我们结合因果机制与信息理论，提出了一种基于信息增益引导的因果干预去偏框架（IGCIDB）。该框架首先通过信息增益引导的因果干预方法，自动平衡指令微调数据集的分布；然后在去偏后的数据集上进行标准的监督微调训练。实验结果表明，IGCIDB能够有效去除LLMs的偏见，显著提升其跨任务的泛化能力。

> Despite significant progress, recent studies indicate that current large language models (LLMs) may still capture dataset biases and utilize them during inference, leading to the poor generalizability of LLMs. However, due to the diversity of dataset biases and the insufficient nature of bias suppression based on in-context learning, the effectiveness of previous prior knowledge-based debiasing methods and in-context learning based automatic debiasing methods is limited. To address these challenges, we explore the combination of causal mechanisms with information theory and propose an information gain-guided causal intervention debiasing (IGCIDB) framework. This framework first utilizes an information gain-guided causal intervention method to automatically and autonomously balance the distribution of instruction-tuning dataset. Subsequently, it employs a standard supervised fine-tuning process to train LLMs on the debiased dataset. Experimental results show that IGCIDB can effectively debias LLM to improve its generalizability across different tasks.

[Arxiv](https://arxiv.org/abs/2504.12898)