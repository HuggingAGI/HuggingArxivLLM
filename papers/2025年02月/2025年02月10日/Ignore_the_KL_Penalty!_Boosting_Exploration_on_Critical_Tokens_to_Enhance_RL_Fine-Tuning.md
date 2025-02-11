# 别再顾虑 KL 惩罚！聚焦关键标记的探索，助力强化学习微调更上一层楼！

发布时间：2025年02月10日

`LLM理论

理由：这篇论文探讨了通过强化学习（RL）对预训练的大型语言模型（LLMs）进行微调的方法，以提高其在实现长期目标方面的能力。论文详细分析了探索与保持预训练模型能力之间的平衡问题，并提出了对KL惩罚项的修改以促进关键令牌的探索。这些内容属于大型语言模型的训练和优化方法，属于LLM理论的范畴。` `语言模型`

> Ignore the KL Penalty! Boosting Exploration on Critical Tokens to Enhance RL Fine-Tuning

# 摘要

> 实现长期目标的能力是当前大型语言模型 (LLMs) 发展中的关键挑战。为了解决这一问题，可以通过强化学习 (RL) 对预训练的 LLMs 进行微调，以探索能够优化给定目标的解决方案。然而，使用 LLMs 进行探索具有难度，因为需要在发现新解决方案和保持与预训练模型足够接近之间取得平衡，以免削弱其基础能力。这一平衡通常通过 Kullback-Leibler (KL) 惩罚项来控制。本文中，我们研究了小型语言模型在简单算术任务中的探索动态。我们展示了不同程度的预训练如何影响探索，并强调了“关键令牌”的重要性，这些令牌对最终结果有着显著影响。因此，我们引入了对 KL 惩罚项的简单修改，以促进对关键令牌的探索，从而提高 RL 微调阶段的效率。

> The ability to achieve long-term goals is a key challenge in the current development of large language models (LLMs). To address this, pre-trained LLMs can be fine-tuned with reinforcement learning (RL) to explore solutions that optimize a given goal. However, exploration with LLMs is difficult, as a balance has to be struck between discovering new solutions and staying close enough to the pre-trained model, so as not to degrade basic capabilities. This is typically controlled with a Kullback-Leibler (KL) penalty. In this paper, we investigate the exploration dynamics of a small language model on a simple arithmetic task. We show how varying degrees of pre-training influence exploration and demonstrate the importance of "critical tokens" which have a dramatic impact on the final outcome. Consequently, we introduce a simple modification to the KL penalty that favors exploration on critical tokens, increasing the efficiency of the RL fine-tuning stage.

[Arxiv](https://arxiv.org/abs/2502.06533)