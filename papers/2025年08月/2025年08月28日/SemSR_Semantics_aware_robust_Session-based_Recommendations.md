# SemSR：语义感知的鲁棒基于会话推荐

发布时间：2025年08月28日

`LLM应用` `零售与电商`

> SemSR: Semantics aware robust Session-based Recommendations

# 摘要

> 基于会话的推荐（SR）模型旨在根据匿名用户当前会话的行为为其推荐物品。尽管现有SR模型通过物品序列预测下一个物品，却常忽略物品标题或描述中的语义信息，从而影响了会话意图的识别与模型的可解释性。近期研究将大型语言模型（LLMs）视为提升基于会话推荐性能的潜力方案，相关研究广泛探索了基于提示与基于微调两种方式。然而，基于提示的方法难寻能引导正确推理的最佳提示，测试阶段又缺乏任务专属反馈，因此推荐效果欠佳；微调方法虽能融入领域知识，却需承担实施与维护的高昂计算成本。为此，本文提出多种利用LLMs优化基于会话推荐的策略：（i）将上下文LLMs用作推荐智能体；（ii）利用LLM生成的表示对深度学习SR模型进行语义初始化；（iii）将LLMs与数据驱动SR模型融合。在两个真实公开数据集上的综合实验表明：基于LLM的方法擅长粗粒度检索（召回率高），而传统数据驱动技术则在细粒度排序上更具优势（平均倒数排名高）。此外，将LLMs与数据驱动SR模型融合后，在召回率和MRR指标上均显著优于独立LLM方法、数据驱动深度学习模型及基线SR模型。

> Session-based recommendation (SR) models aim to recommend items to anonymous users based on their behavior during the current session. While various SR models in the literature utilize item sequences to predict the next item, they often fail to leverage semantic information from item titles or descriptions impeding session intent identification and interpretability. Recent research has explored Large Language Models (LLMs) as promising approaches to enhance session-based recommendations, with both prompt-based and fine-tuning based methods being widely investigated. However, prompt-based methods struggle to identify optimal prompts that elicit correct reasoning and lack task-specific feedback at test time, resulting in sub-optimal recommendations. Fine-tuning methods incorporate domain-specific knowledge but incur significant computational costs for implementation and maintenance. In this paper, we present multiple approaches to utilize LLMs for session-based recommendation: (i) in-context LLMs as recommendation agents, (ii) LLM-generated representations for semantic initialization of deep learning SR models, and (iii) integration of LLMs with data-driven SR models. Through comprehensive experiments on two real-world publicly available datasets, we demonstrate that LLM-based methods excel at coarse-level retrieval (high recall values), while traditional data-driven techniques perform well at fine-grained ranking (high Mean Reciprocal Rank values). Furthermore, the integration of LLMs with data-driven SR models significantly out performs both standalone LLM approaches and data-driven deep learning models, as well as baseline SR models, in terms of both Recall and MRR metrics.

[Arxiv](https://arxiv.org/abs/2508.20587)