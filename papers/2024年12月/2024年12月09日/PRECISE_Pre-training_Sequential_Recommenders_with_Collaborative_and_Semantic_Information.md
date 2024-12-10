# PRECISE：借助协作和语义信息对序列推荐器开展预训练

发布时间：2024年12月09日

`LLM应用` `推荐系统` `工业平台`

> PRECISE: Pre-training Sequential Recommenders with Collaborative and Semantic Information

# 摘要

> 在现实世界中，推荐系统通常为用户提供丰富多样的内容场景以供互动。鉴于工业平台上用户众多，使用单一统一的推荐模型来满足所有场景的需求是不现实的。通常，会为每个不同的场景设立单独的推荐管道。但这样做会导致难以全面把握用户的兴趣。近期的研究致力于通过预训练模型来封装用户的整体兴趣，以解决此问题。传统的预训练推荐模型主要借助协作信号来捕捉用户兴趣。然而，这类系统普遍存在无法处理长尾项目和冷启动场景的缺陷。随着大型语言模型的新近出现，利用 LLMs 为用户和项目提取语义信息的研究显著增多。不过，基于文本的推荐严重依赖精细的特征工程，且常常难以捕捉协作相似性。为克服这些局限，我们提出了一种用于序列推荐的新型预训练框架，名为 PRECISE。该框架将协作信号与语义信息相融合。此外，PRECISE 采用了一种学习框架，先对所有推荐场景中的用户综合兴趣进行建模，再聚焦于目标场景行为的特定兴趣。我们证明，PRECISE 能精准捕捉用户兴趣的全貌，并有效地将其转移到目标兴趣上。实证结果显示，PRECISE 框架在公共和工业数据集上均表现出色。

> Real-world recommendation systems commonly offer diverse content scenarios for users to interact with. Considering the enormous number of users in industrial platforms, it is infeasible to utilize a single unified recommendation model to meet the requirements of all scenarios. Usually, separate recommendation pipelines are established for each distinct scenario. This practice leads to challenges in comprehensively grasping users' interests. Recent research endeavors have been made to tackle this problem by pre-training models to encapsulate the overall interests of users. Traditional pre-trained recommendation models mainly capture user interests by leveraging collaborative signals. Nevertheless, a prevalent drawback of these systems is their incapacity to handle long-tail items and cold-start scenarios. With the recent advent of large language models, there has been a significant increase in research efforts focused on exploiting LLMs to extract semantic information for users and items. However, text-based recommendations highly rely on elaborate feature engineering and frequently fail to capture collaborative similarities. To overcome these limitations, we propose a novel pre-training framework for sequential recommendation, termed PRECISE. This framework combines collaborative signals with semantic information. Moreover, PRECISE employs a learning framework that initially models users' comprehensive interests across all recommendation scenarios and subsequently concentrates on the specific interests of target-scene behaviors. We demonstrate that PRECISE precisely captures the entire range of user interests and effectively transfers them to the target interests. Empirical findings reveal that the PRECISE framework attains outstanding performance on both public and industrial datasets.

[Arxiv](https://arxiv.org/abs/2412.06308)