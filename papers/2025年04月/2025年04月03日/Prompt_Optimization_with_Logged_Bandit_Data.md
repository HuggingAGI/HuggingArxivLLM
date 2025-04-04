# 基于日志的多臂老虎机数据进行提示优化

发布时间：2025年04月03日

`LLM应用` `推荐系统`

> Prompt Optimization with Logged Bandit Data

# 摘要

> 我们研究如何利用自然可用的用户反馈（如点击行为）来优化大型语言模型 (LLM) 管道，用于通过提示生成个性化句子。简单直接的方法在提示空间中估计策略梯度，但面临提示动作空间庞大引起的方差问题或奖励预测不准确导致的偏差。为解决这些问题，我们提出了一种基于核函数的离策略梯度方法，通过利用生成句子间的相似性来估计策略梯度，从而大幅降低方差并抑制偏差。我们在新建立的基准测试套件上的实证结果证明了所提方法在为电影推荐生成个性化描述方面的有效性，尤其是在候选提示数量较大时。

> We study how to use naturally available user feedback, such as clicks, to optimize large language model (LLM) pipelines for generating personalized sentences using prompts. Naive approaches, which estimate the policy gradient in the prompt space, suffer either from variance caused by the large action space of prompts or bias caused by inaccurate reward predictions. To circumvent these challenges, we propose a novel kernel-based off-policy gradient method, which estimates the policy gradient by leveraging similarity among generated sentences, substantially reducing variance while suppressing the bias. Empirical results on our newly established suite of benchmarks demonstrate the effectiveness of the proposed approach in generating personalized descriptions for movie recommendations, particularly when the number of candidate prompts is large.

[Arxiv](https://arxiv.org/abs/2504.02646)