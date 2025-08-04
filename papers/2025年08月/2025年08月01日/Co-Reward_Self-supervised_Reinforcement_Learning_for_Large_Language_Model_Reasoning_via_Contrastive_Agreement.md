# 协作奖励：对比一致性驱动的大型语言模型自监督推理强化学习

发布时间：2025年08月01日

`LLM应用` `人工智能`

> Co-Reward: Self-supervised Reinforcement Learning for Large Language Model Reasoning via Contrastive Agreement

# 摘要

> 尽管基于可验证奖励的强化学习（RLVR）在提升大型语言模型（LLMs）的推理能力方面展现出潜力，但因依赖于人工标注的标签，尤其是在处理复杂任务时，扩展性问题依然存在。近期探索各种自奖励信号的替代方法虽然揭示了LLM推理的潜力，却未能忽视不可忽视的坍塌问题。受自监督学习成功的启发，我们提出了	extit{Co-Reward}，这是一种全新的RL框架，它利用语义类比问题之间的对比一致性作为奖励基础。具体而言，我们为每个训练样本（无需标签）构建一个相似的问题，并通过简单的 rollout 投票合成各自的代理标签，然后通过参考每对问题的标签来构建奖励，以强制实现类比输入之间的内部推理一致性。从直觉上看，这种自监督的奖励塑造机制增加了学习过程中避免陷入简单解决方案的难度，并通过扩展输入样本变体促进了稳定推理的激发和提升。实证研究表明，与其它自奖励基线相比，Co-Reward 在多个推理基准测试和 LLM 系列中表现出色，甚至达到或超越了基于真实标签（GT）的奖励水平，在 Llama-3.2-3B-Instruct 上，MATH500 的表现较 GT 奖励提升了高达 $+6.8\%$。我们的代码已公开发布于 https://github.com/tmlr-group/Co-Reward。

> Although reinforcement learning with verifiable rewards (RLVR) shows promise in improving the reasoning ability of large language models (LLMs), the scaling up dilemma remains due to the reliance on human annotated labels especially for complex tasks. Recent alternatives that explore various self-reward signals exhibit the eliciting potential of LLM reasoning, but suffer from the non-negligible collapse issue. Inspired by the success of self-supervised learning, we propose \textit{Co-Reward}, a novel RL framework that leverages contrastive agreement across semantically analogical questions as a reward basis. Specifically, we construct a similar question for each training sample (without labels) and synthesize their individual surrogate labels through a simple rollout voting, and then the reward is constructed by cross-referring the labels of each question pair to enforce the internal reasoning consistency across analogical inputs. Intuitively, such a self-supervised reward-shaping mechanism increases the difficulty of learning collapse into a trivial solution, and promotes stable reasoning elicitation and improvement through expanding the input sample variants. Empirically, Co-Reward achieves superior performance compared to other self-reward baselines on multiple reasoning benchmarks and LLM series, and reaches or even surpasses ground-truth (GT) labeled reward, with improvements of up to $+6.8\%$ on MATH500 over GT reward on Llama-3.2-3B-Instruct. Our code is publicly available at https://github.com/tmlr-group/Co-Reward.

[Arxiv](https://arxiv.org/abs/2508.00410)