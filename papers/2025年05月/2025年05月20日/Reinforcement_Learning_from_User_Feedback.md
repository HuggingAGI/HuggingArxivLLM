# 基于用户反馈的强化学习

发布时间：2025年05月20日

`LLM应用

理由：这篇论文讨论了如何通过用户反馈来优化大型语言模型（LLMs）的表现，特别是通过基于用户反馈的强化学习（RLUF）来解决实际应用中的问题。这属于LLMs的实际应用和优化，因此归类为LLM应用。` `用户体验` `用户行为分析`

> Reinforcement Learning from User Feedback

# 摘要

> 随着大型语言模型（LLMs）在更多实际应用中落地，与真实用户偏好保持一致变得至关重要。现有的基于人类反馈的强化学习（RLHF）依赖专家标注者，可能无法反映普通用户的实际需求。为此，我们推出基于用户反馈的强化学习（RLUF），通过直接利用用户在实际使用中的隐式信号，帮助LLMs更好地与真实用户偏好对齐。RLUF有效解决了用户反馈中常见的二元性、稀疏性和对抗性问题。通过训练一个名为P[Love]的奖励模型，我们成功预测了LLM响应获得正面反馈的可能性，并将其与帮助性和安全性目标结合，构建了一个多目标策略优化框架。在大规模实验中，P[Love]不仅能够预测更多正面反馈，还成为评估未来用户行为的可靠工具。在实时A/B测试中，使用P[Love]进行策略优化使正面反馈率提升了28%。然而，我们也注意到，过度追求正面反应可能导致奖励黑客问题，需要在优化过程中谨慎平衡。通过直接利用用户隐式反馈，RLUF为在大规模场景下将LLMs与真实用户偏好对齐提供了一条可行路径。

> As large language models (LLMs) are increasingly deployed in diverse user facing applications, aligning them with real user preferences becomes essential. Existing methods like Reinforcement Learning from Human Feedback (RLHF) rely on expert annotators trained on manually defined guidelines, whose judgments may not reflect the priorities of everyday users. We introduce Reinforcement Learning from User Feedback (RLUF), a framework for aligning LLMs directly to implicit signals from users in production. RLUF addresses key challenges of user feedback: user feedback is often binary (e.g., emoji reactions), sparse, and occasionally adversarial. We train a reward model, P[Love], to predict the likelihood that an LLM response will receive a Love Reaction, a lightweight form of positive user feedback, and integrate P[Love] into a multi-objective policy optimization framework alongside helpfulness and safety objectives. In large-scale experiments, we show that P[Love] is predictive of increased positive feedback and serves as a reliable offline evaluator of future user behavior. Policy optimization using P[Love] significantly raises observed positive-feedback rates, including a 28% increase in Love Reactions during live A/B tests. However, optimizing for positive reactions introduces reward hacking challenges, requiring careful balancing of objectives. By directly leveraging implicit signals from users, RLUF offers a path to aligning LLMs with real-world user preferences at scale.

[Arxiv](https://arxiv.org/abs/2505.14946)