# 基于人类在环强化学习的零样本LLM应用：以零样本学习替代人类反馈，实现奖励机制的优化

发布时间：2025年03月25日

`LLM应用` `人工智能`

> Zero-Shot LLMs in Human-in-the-Loop RL: Replacing Human Feedback for Reward Shaping

# 摘要

> 强化学习常常遭遇奖励偏差的挑战：智能体虽能优化给定奖励，却难以展现预期行为。这种偏差源于奖励函数激励了偏离真实目标的代理行为。尽管人机协作（HIL）方法能提供帮助，但人类反馈中的偏见和主观性却可能加剧问题，使学习过程更加复杂。为解决这些问题，我们提出两大创新：首先，我们将零样本、现成的大语言模型（LLMs）的奖励塑造应用从自然语言处理（NLP）扩展至连续控制任务。通过直接利用LLMs作为反馈提供者，我们取代了基于人类反馈训练的代理模型，从而避免了反馈数据中固有偏见的影响。其次，我们推出一个混合框架（LLM-HFBF），使LLMs能够识别并纠正人类反馈中的偏见，同时将这些反馈整合到奖励塑造过程中。LLM-HFBF框架通过同时克服LLMs的局限性（如缺乏领域知识）和人类监督的局限性（如固有偏见），构建了一个更平衡可靠的系统。通过实现对人类反馈偏见的自动标记与校正，我们的方法不仅提升了强化学习的表现，还减少了对可能存在偏见的人类指导的依赖。实证实验表明，偏见反馈显著降低了性能，平均回合奖励（AER）从无偏方法的28.472降至保守偏见情况下的7.039。相比之下，基于LLM的方法即使在极端定制场景中，仍能保持与无偏反馈相当的AER。

> Reinforcement learning often faces challenges with reward misalignment, where agents optimize for given rewards but fail to exhibit the desired behaviors. This occurs when the reward function incentivizes proxy behaviors that diverge from the true objective. While human-in-the-loop (HIL) methods can help, they may exacerbate the problem, as humans are prone to biases that lead to inconsistent, subjective, or misaligned feedback, complicating the learning process. To address these issues, we propose two key contributions. First, we extend the use of zero-shot, off-the-shelf large language models (LLMs) for reward shaping beyond natural language processing (NLP) to continuous control tasks. By leveraging LLMs as direct feedback providers, we replace surrogate models trained on human feedback, which often suffer from the bias inherent in the feedback data it is trained on. Second, we introduce a hybrid framework (LLM-HFBF) that enables LLMs to identify and correct biases in human feedback while incorporating this feedback into the reward shaping process. The LLM-HFBF framework creates a more balanced and reliable system by addressing both the limitations of LLMs (e.g., lack of domain-specific knowledge) and human supervision (e.g., inherent biases). By enabling human feedback bias flagging and correction, our approach improves reinforcement learning performance and reduces reliance on potentially biased human guidance. Empirical experiments show that biased human feedback significantly reduces performance, with average episodic reward (AER) dropping from 28.472 in (unbiased approaches) to 7.039 (biased with conservative bias). In contrast, LLM-based approaches maintain a matching AER like unbiased feedback, even in custom edge case scenarios.

[Arxiv](https://arxiv.org/abs/2503.22723)