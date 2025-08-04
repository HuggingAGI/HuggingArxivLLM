# 探索推荐中的平衡之道：相关性与新颖性的双稳定周期优化

发布时间：2025年08月01日

`LLM应用` `推荐系统`

> When Relevance Meets Novelty: Dual-Stable Periodic Optimization for Exploratory Recommendation

# 摘要

> 传统推荐系统常让用户陷入强烈反馈循环，过度推送历史偏好相关内容，限制了探索机会并导致内容疲劳。大型语言模型（LLMs）虽有潜力，但现有双模型框架存在两大问题：忽视群体身份驱动的长期偏好，导致兴趣建模偏颇；静态优化缺陷，一次性对齐无法利用增量数据闭环优化。为此，我们提出了协同进化对齐（CoEA）方法。为解决兴趣建模偏差，我们引入双稳定兴趣探索（DSIE）模块，通过并行处理行为序列，联合建模长期群体身份和短期个体兴趣。针对静态优化限制，设计了周期性协作优化（PCO）机制。该机制定期用相关性LLM验证增量数据偏好，根据结果引导新颖性LLM微调，并将微调输出反馈相关性LLM重新评估，实现动态闭环优化。线上线下实验验证了CoEA模型在探索性推荐中的有效性。

> Traditional recommendation systems tend to trap users in strong feedback loops by excessively pushing content aligned with their historical preferences, thereby limiting exploration opportunities and causing content fatigue. Although large language models (LLMs) demonstrate potential with their diverse content generation capabilities, existing LLM-enhanced dual-model frameworks face two major limitations: first, they overlook long-term preferences driven by group identity, leading to biased interest modeling; second, they suffer from static optimization flaws, as a one-time alignment process fails to leverage incremental user data for closed-loop optimization. To address these challenges, we propose the Co-Evolutionary Alignment (CoEA) method. For interest modeling bias, we introduce Dual-Stable Interest Exploration (DSIE) module, jointly modeling long-term group identity and short-term individual interests through parallel processing of behavioral sequences. For static optimization limitations, we design a Periodic Collaborative Optimization (PCO) mechanism. This mechanism regularly conducts preference verification on incremental data using the Relevance LLM, then guides the Novelty LLM to perform fine-tuning based on the verification results, and subsequently feeds back the output of the incrementally fine-tuned Novelty LLM to the Relevance LLM for re-evaluation, thereby achieving a dynamic closed-loop optimization. Extensive online and offline experiments verify the effectiveness of the CoEA model in exploratory recommendation.

[Arxiv](https://arxiv.org/abs/2508.00450)