# 基于大型语言模型的对话推荐系统中的协作检索方法

发布时间：2025年02月19日

`LLM应用

理由：这篇论文探讨了大型语言模型 (LLMs) 在对话推荐系统中的应用，特别是通过结合协同过滤方法来提升推荐效果。它展示了LLM在实际应用中的具体应用和改进，因此归类为LLM应用。` `推荐系统` `对话系统`

> Collaborative Retrieval for Large Language Model-based Conversational Recommender Systems

# 摘要

> 对话推荐系统 (CRS) 通过与用户的互动对话提供个性化推荐服务。虽然大型语言模型 (LLMs) 凭借其对上下文感知用户偏好的卓越理解提升了 CRS 的性能，但它们通常难以有效利用行为数据，而行为数据对经典的基于协同过滤 (CF) 的方法至关重要。为此，我们提出了 CRAG（协作检索增强生成），一种结合 LLM 和 CF 的对话推荐方法。据我们所知，CRAG 是首个将先进 LLM 与 CF 结合用于对话推荐的方案。我们在两个公开的电影对话推荐数据集——优化版 Reddit 数据集（命名为 Reddit-v2）和 Redial 数据集——上的实验表明，CRAG 在项目覆盖率和推荐性能方面优于多个 CRS 基线方法。进一步分析发现，这种提升主要得益于对近期上映电影推荐准确性的显著提高。相关代码和数据已在 https://github.com/yaochenzhu/CRAG 上开放。

> Conversational recommender systems (CRS) aim to provide personalized recommendations via interactive dialogues with users. While large language models (LLMs) enhance CRS with their superior understanding of context-aware user preferences, they typically struggle to leverage behavioral data, which have proven to be important for classical collaborative filtering (CF)-based approaches. For this reason, we propose CRAG, Collaborative Retrieval Augmented Generation for LLM-based CRS. To the best of our knowledge, CRAG is the first approach that combines state-of-the-art LLMs with CF for conversational recommendations. Our experiments on two publicly available movie conversational recommendation datasets, i.e., a refined Reddit dataset (which we name Reddit-v2) as well as the Redial dataset, demonstrate the superior item coverage and recommendation performance of CRAG, compared to several CRS baselines. Moreover, we observe that the improvements are mainly due to better recommendation accuracy on recently released movies. The code and data are available at https://github.com/yaochenzhu/CRAG.

[Arxiv](https://arxiv.org/abs/2502.14137)