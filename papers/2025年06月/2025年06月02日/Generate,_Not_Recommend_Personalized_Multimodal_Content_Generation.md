# 生成，而非推荐：《个性化多模态内容生成》

发布时间：2025年06月02日

`LLM应用` `推荐系统` `多模态生成`

> Generate, Not Recommend: Personalized Multimodal Content Generation

# 摘要

> 面对海量网络内容引发的信息过载问题，推荐系统被广泛应用以检索并为用户提供个性化结果。然而，传统的推荐任务本质上局限于对已有内容进行筛选，缺乏生成新概念的能力，这限制了其充分满足用户需求和偏好的能力。在本文中，我们提出了一种超越内容过滤和选择的新范式：直接为用户生成个性化的多模态内容，如定制化的图像。我们利用任意到任意的大规模多模态模型（LMMs），并通过监督微调和在线强化学习策略进行训练，赋予模型为用户生成定制化下一内容的能力。在两个基准数据集上的实验以及用户研究表明，我们提出的方法具有显著效果。值得注意的是，生成的图像不仅与用户的过往偏好高度契合，还与他们潜在的未来兴趣相关。

> To address the challenge of information overload from massive web contents, recommender systems are widely applied to retrieve and present personalized results for users. However, recommendation tasks are inherently constrained to filtering existing items and lack the ability to generate novel concepts, limiting their capacity to fully satisfy user demands and preferences. In this paper, we propose a new paradigm that goes beyond content filtering and selecting: directly generating personalized items in a multimodal form, such as images, tailored to individual users. To accomplish this, we leverage any-to-any Large Multimodal Models (LMMs) and train them in both supervised fine-tuning and online reinforcement learning strategy to equip them with the ability to yield tailored next items for users. Experiments on two benchmark datasets and user study confirm the efficacy of the proposed method. Notably, the generated images not only align well with users' historical preferences but also exhibit relevance to their potential future interests.

[Arxiv](https://arxiv.org/abs/2506.01704)