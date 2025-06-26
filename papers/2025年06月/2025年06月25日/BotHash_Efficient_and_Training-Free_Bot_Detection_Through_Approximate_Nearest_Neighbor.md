# BotHash：通过近似最近邻实现高效且无需训练的机器人检测。

发布时间：2025年06月25日

`LLM应用` `在线社交网络` `社交机器人`

> BotHash: Efficient and Training-Free Bot Detection Through Approximate Nearest Neighbor

# 摘要

> # 摘要
在线社交网络（OSNs）是现代社会的基石，为数百万用户提供了一个多元内容消费的平台。然而，在这些平台上确保共享信息的准确性仍然是一个重大挑战，尤其是在虚假信息广泛传播的背景下。社交机器人——这些模仿人类行为的自动化账号，常常传播错误信息，是在线社交网络面临的关键问题之一。大型语言模型（LLMs）的出现进一步复杂化了机器人的行为，使得检测变得更加困难。

本文提出了BotHash，一种创新的、无需训练的社交机器人检测方法。BotHash通过简化用户表示，利用近似最近邻搜索来识别社交机器人，从而避免了深度学习模型训练和创建大型数据集的复杂性。我们证明了即使在使用最先进的LLMs生成帖子内容的情况下，BotHash也能有效区分人类账户和机器人账户。与现有方法相比，BotHash具有无需训练阶段、在少量真实数据下表现稳健以及具备早期检测能力等优势，在各种数据集上均展现出令人鼓舞的结果。


> Online Social Networks (OSNs) are a cornerstone in modern society, serving as platforms for diverse content consumption by millions of users each day. However, the challenge of ensuring the accuracy of information shared on these platforms remains significant, especially with the widespread dissemination of disinformation. Social bots -- automated accounts designed to mimic human behavior, frequently spreading misinformation -- represent one of the critical problems of OSNs. The advent of Large Language Models (LLMs) has further complicated bot behaviors, making detection increasingly difficult. This paper presents BotHash, an innovative, training-free approach to social bot detection. BotHash leverages a simplified user representation that enables approximate nearest-neighbor search to detect bots, avoiding the complexities of Deep-Learning model training and large dataset creation. We demonstrate that BotHash effectively differentiates between human and bot accounts, even when state-of-the-art LLMs are employed to generate posts' content. BotHash offers several advantages over existing methods, including its independence from a training phase, robust performance with minimal ground-truth data, and early detection capabilities, showing promising results across various datasets.

[Arxiv](https://arxiv.org/abs/2506.20503)