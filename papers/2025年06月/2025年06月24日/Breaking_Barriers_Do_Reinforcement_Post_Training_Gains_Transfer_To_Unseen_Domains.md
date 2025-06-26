# 突破界限：强化训练后的提升能否迁移到未知领域？

发布时间：2025年06月24日

`LLM理论` `大型语言模型` `机器学习`

> Breaking Barriers: Do Reinforcement Post Training Gains Transfer To Unseen Domains?

# 摘要

> 强化后训练（RPT）在提升大型语言模型（LLMs）推理能力方面展现出潜力。然而，目前尚不清楚这些改进在新领域中的泛化效果如何，因为先前研究仅在与微调相同领域的数据上评估RPT模型。为了探究RPT的泛化能力，我们进行了两项研究：1）观察性：我们对比了多种开放权重的RPT模型与其基础模型，在多个领域上的表现，包括微调数据中见过和未见过的领域。2）干预性：我们使用RPT在单一领域微调LLMs，并评估其在多个领域中的表现。两项研究均得出相同结论：尽管RPT在与微调数据相似的任务上带来显著提升，但这些提升在不同推理模式的领域中泛化不一致，甚至可能消失。

> Reinforcement post training (RPT) has recently shown promise in improving the reasoning abilities of large language models (LLMs). However, it remains unclear how well these improvements generalize to new domains, as prior work evaluates RPT models on data from the same domains used for fine-tuning. To understand the generalizability of RPT, we conduct two studies. (1) Observational: We compare a wide range of open-weight RPT models against their corresponding base models across multiple domains, including both seen and unseen domains in their fine-tuning data. (2) Interventional: we fine-tune LLMs with RPT on single domains and evaluate their performance across multiple domains. Both studies converge on the same conclusion that, although RPT brings substantial gains on tasks similar to the fine-tuning data, the gains generalize inconsistently and can vanish on domains with different reasoning patterns.

[Arxiv](https://arxiv.org/abs/2506.19733)