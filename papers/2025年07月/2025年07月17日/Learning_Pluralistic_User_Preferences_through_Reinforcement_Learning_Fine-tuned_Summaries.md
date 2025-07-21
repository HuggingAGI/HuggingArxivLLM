# 利用强化学习微调摘要，探索多元用户偏好

发布时间：2025年07月17日

`LLM应用

理由：这篇论文主要探讨了如何通过创新的框架（PLUS）来提升大型语言模型在个性化响应方面的应用效果，属于LLM的应用层面。` `人工智能`

> Learning Pluralistic User Preferences through Reinforcement Learning Fine-tuned Summaries

# 摘要

> # 摘要
随着大型语言模型 (LLM) 人工智能助手在日常场景中的广泛应用，个性化响应以满足不同用户的偏好和目标变得至关重要。虽然基于人类反馈的强化学习 (RLHF) 在提升 LLM 的通用性能方面卓有成效，但它未能充分考虑用户间的差异性，因为它依赖单一奖励模型来统一建模所有用户。为此，我们提出了一种名为Preference Learning Using Summarization (PLUS) 的创新框架，该框架通过学习每个用户的偏好、特征和历史对话的文本摘要，实现了更精细的个性化响应。

PLUS框架通过强化学习训练用户摘要模型，并与奖励模型同步更新，形成一个在线协同适应机制。实验表明，与现有的个性化 RLHF 技术或基于上下文学习的用户信息方法相比，PLUS 生成的用户摘要能够更精准地捕捉用户偏好中的关键特征。在多个多元用户数据集上的测试结果表明，我们的方法不仅对新用户表现出良好的适应性，还能在多样化对话主题中保持稳定性能。此外，PLUS 生成的文本摘要还能够迁移至零样本场景，用于个性化训练更强大的专有模型，如 GPT-4。值得一提的是，PLUS 生成的用户摘要不仅简洁明了、易于传输，还具备良好的可解释性和可修改性，从而为 LLM 的对齐过程提供了更高的透明度和用户控制权。

> As everyday use cases of large language model (LLM) AI assistants have expanded, it is becoming increasingly important to personalize responses to align to different users' preferences and goals. While reinforcement learning from human feedback (RLHF) is effective at improving LLMs to be generally more helpful and fluent, it does not account for variability across users, as it models the entire user population with a single reward model. We present a novel framework, Preference Learning Using Summarization (PLUS), that learns text-based summaries of each user's preferences, characteristics, and past conversations. These summaries condition the reward model, enabling it to make personalized predictions about the types of responses valued by each user. We train the user-summarization model with reinforcement learning, and update the reward model simultaneously, creating an online co-adaptation loop. We show that in contrast with prior personalized RLHF techniques or with in-context learning of user information, summaries produced by PLUS capture meaningful aspects of a user's preferences. Across different pluralistic user datasets, we show that our method is robust to new users and diverse conversation topics. Additionally, we demonstrate that the textual summaries generated about users can be transferred for zero-shot personalization of stronger, proprietary models like GPT-4. The resulting user summaries are not only concise and portable, they are easy for users to interpret and modify, allowing for more transparency and user control in LLM alignment.

[Arxiv](https://arxiv.org/abs/2507.13579)