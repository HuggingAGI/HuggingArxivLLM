# RULE：强化无学习实现遗忘与保留的帕累托最优

发布时间：2025年06月08日

`LLM应用` `内容安全`

> RULE: Reinforcement UnLEarning Achieves Forget-Retain Pareto Optimality

# 摘要

> 大规模未经整理数据集训练的大型语言模型（LLMs）广泛应用，引发人们对模型可能包含敏感、版权或非法内容的担忧。这激发了对LLM“遗忘”任务的兴趣：即在不重新训练或降低实用性的情况下，有选择性地移除特定信息。然而，现有方法依赖大规模数据集，且存在响应不自然、泛化能力差等问题。本研究提出强化学习遗忘（RULE），一种高效的框架，将遗忘任务转化为拒绝边界优化问题。仅需少量遗忘数据和合成边界查询，RULE通过可验证奖励函数实现安全拒绝与自然响应的平衡。实验表明，RULE在【12%】遗忘数据和【8%】边界数据下，实现【17.5%】遗忘质量和【16.3%】自然响应的提升，同时保持一般实用性，达到帕累托最优。此外，RULE还提升了模型自然度和训练效率，并展现出强大的泛化能力，能将拒绝行为推广到语义相关但未见过的查询。

> The widespread deployment of Large Language Models (LLMs) trained on massive, uncurated corpora has raised growing concerns about the inclusion of sensitive, copyrighted, or illegal content. This has led to increasing interest in LLM unlearning: the task of selectively removing specific information from a model without retraining from scratch or degrading overall utility. However, existing methods often rely on large-scale forget and retain datasets, and suffer from unnatural responses, poor generalization, or catastrophic utility loss. In this work, we propose Reinforcement UnLearning (RULE), an efficient framework that formulates unlearning as a refusal boundary optimization problem. RULE is trained with a small portion of the forget set and synthesized boundary queries, using a verifiable reward function that encourages safe refusal on forget--related queries while preserving helpful responses on permissible inputs. We provide both theoretical and empirical evidence demonstrating the effectiveness of RULE in achieving targeted unlearning without compromising model utility. Experimental results show that, with only $12%$ forget set and $8%$ synthesized boundary data, RULE outperforms existing baselines by up to $17.5%$ forget quality and $16.3%$ naturalness response while maintaining general utility, achieving forget--retain Pareto optimality. Remarkably, we further observe that RULE improves the naturalness of model outputs, enhances training efficiency, and exhibits strong generalization ability, generalizing refusal behavior to semantically related but unseen queries.

[Arxiv](https://arxiv.org/abs/2506.07171)