# 对比反馈对有效用户模拟的作用评估

发布时间：2025年05月05日

`LLM应用` `信息检索`

> Evaluating Contrastive Feedback for Effective User Simulations

# 摘要

> 大型语言模型（LLMs）在交互式信息检索领域用于模拟用户行为的应用近期备受关注。然而，其应用和能力仍存在很大争议且研究不足。本研究探讨了对比训练技术的基本原理是否可以有效应用于用户模拟的提示工程领域，这些原理曾成功用于LLMs的微调。

    以往研究表明，LLMs拥有丰富的世界知识，可用于准确估算相关文档。本研究尝试通过在模拟过程中增强模型获得额外的隐式背景信息来模拟知识状态。这种方法使模型能够进一步缩小所需文档的范围。本研究的主要目标是分析不同类型的背景信息对用户模拟效果的影响。

    我们测试了多种用户配置，其中模型会以对比方式提供已判定的相关、不相关或两类文档的摘要。本研究重点评估了提示技术对模拟用户代理性能的影响。我们在此为更真实地利用LLMs作为模拟用户奠定了基础。

> The use of Large Language Models (LLMs) for simulating user behavior in the domain of Interactive Information Retrieval has recently gained significant popularity. However, their application and capabilities remain highly debated and understudied. This study explores whether the underlying principles of contrastive training techniques, which have been effective for fine-tuning LLMs, can also be applied beneficially in the area of prompt engineering for user simulations.
  Previous research has shown that LLMs possess comprehensive world knowledge, which can be leveraged to provide accurate estimates of relevant documents. This study attempts to simulate a knowledge state by enhancing the model with additional implicit contextual information gained during the simulation. This approach enables the model to refine the scope of desired documents further. The primary objective of this study is to analyze how different modalities of contextual information influence the effectiveness of user simulations.
  Various user configurations were tested, where models are provided with summaries of already judged relevant, irrelevant, or both types of documents in a contrastive manner. The focus of this study is the assessment of the impact of the prompting techniques on the simulated user agent performance. We hereby lay the foundations for leveraging LLMs as part of more realistic simulated users.

[Arxiv](https://arxiv.org/abs/2505.02560)