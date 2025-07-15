# MIND：多智能体零样本有害网络迷因检测框架

发布时间：2025年07月09日

`LLM应用` `社交媒体` `内容安全`

> MIND: A Multi-agent Framework for Zero-shot Harmful Meme Detection

# 摘要

> 社交媒体上模因的迅速传播凸显了有效检测有害内容的迫切需求。然而，传统数据驱动方法由于模因的不断演变以及缺乏最新标注数据，在检测新模因方面力不从心。为解决这一问题，我们提出了一种名为MIND的多智能体零样本有害模因检测框架，该框架无需依赖标注数据。MIND实现了三大关键策略：1) 从无标注参考集合中检索相似模因以提供上下文信息；2) 提出一种双向洞察推导机制以全面理解相似模因；3) 利用多智能体辩论机制通过合理仲裁确保稳健决策。在三个模因数据集上的大量实验表明，我们的框架不仅超越现有零样本方法，还在不同模型架构和参数规模上展现出强大的泛化能力，为有害模因检测提供了一种可扩展的解决方案。代码可从https://github.com/destroy-lonely/MIND获取。

> The rapid expansion of memes on social media has highlighted the urgent need for effective approaches to detect harmful content. However, traditional data-driven approaches struggle to detect new memes due to their evolving nature and the lack of up-to-date annotated data. To address this issue, we propose MIND, a multi-agent framework for zero-shot harmful meme detection that does not rely on annotated data. MIND implements three key strategies: 1) We retrieve similar memes from an unannotated reference set to provide contextual information. 2) We propose a bi-directional insight derivation mechanism to extract a comprehensive understanding of similar memes. 3) We then employ a multi-agent debate mechanism to ensure robust decision-making through reasoned arbitration. Extensive experiments on three meme datasets demonstrate that our proposed framework not only outperforms existing zero-shot approaches but also shows strong generalization across different model architectures and parameter scales, providing a scalable solution for harmful meme detection. The code is available at https://github.com/destroy-lonely/MIND.

[Arxiv](https://arxiv.org/abs/2507.06908)