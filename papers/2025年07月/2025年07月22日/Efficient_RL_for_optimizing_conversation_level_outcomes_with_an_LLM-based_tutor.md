# 高效强化学习：基于LLM的导师优化对话层面的结果

发布时间：2025年07月22日

`LLM应用` `对话系统`

> Efficient RL for optimizing conversation level outcomes with an LLM-based tutor

# 摘要

> 现有基于强化学习与人类反馈（RLHF）框架的大型语言模型（LLMs）通常根据即时轮次的人类偏好优化回应。然而，在多轮对话场景中，例如在线数学辅导，这种方法效果不佳。为此，我们提出了一种新方法：通过将对话历史表示为学生的低维潜在状态，并基于此优化长期策略，以决定高层动作。这一方法旨在更好地将辅导行为与长期目标——即引导学生自行解决数学问题——保持一致。与以往通过端到端训练策略直接生成下一条回复的方法相比，我们的模型更加轻量级，计算资源需求更低。实验结果表明，在基于LLM的模拟辅导任务中，这些改进带来了更优的长期效果。

> Large language models (LLMs) built on existing reinforcement learning with human feedback (RLHF) frameworks typically optimize responses based on immediate turn-level human preferences. However, this approach falls short in multi-turn dialogue settings, such as online math tutoring. We propose a method to enhance LLM-based tutors by representing the dialogue history with a lower-dimensional latent state representation of a student and optimizing a long-term policy to determine high-level actions based on the latent state. The goal is to better align the tutor's behavior with the long-term objective of guiding the student towards solving a target math problem on their own. Our model is lightweight, requiring less computational resources than prior work of training the tutor policy end-to-end to directly output the tutor's next utterance. Our experiment results demonstrate that these modifications lead to improved long-term outcomes compared to prompting in LLM-simulated tutoring tasks.

[Arxiv](https://arxiv.org/abs/2507.16252)