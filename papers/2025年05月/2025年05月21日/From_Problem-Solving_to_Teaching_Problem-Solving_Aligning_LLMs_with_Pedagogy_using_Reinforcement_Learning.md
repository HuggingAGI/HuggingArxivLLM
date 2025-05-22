# # 从问题解决迈向教授问题解决：基于强化学习，将大型语言模型与教学法相融合

发布时间：2025年05月21日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLMs）在教育领域的应用，特别是通过强化学习框架将其转化为有效的导师。它关注的是LLMs在实际教学中的应用和优化，属于LLM的应用层面。` `导师模型`

> From Problem-Solving to Teaching Problem-Solving: Aligning LLMs with Pedagogy using Reinforcement Learning

# 摘要

> 大型语言模型（LLMs）正在变革教育领域，但它们在直接问答方面的优化常常削弱了有效教学法，因为教学需要战略性地保留答案。为了解决这一问题，我们提出了一种基于在线强化学习（RL）的对齐框架，通过模拟师生互动，强调教学质量和引导式问题解决，而非仅仅提供答案，从而快速将LLMs转化为有效的导师。我们使用此方法训练了一个70亿参数的导师模型，无需人工标注，其性能与LearnLM等更大的专有模型相当。我们引入了可控制的奖励加权机制，以平衡教学支持和学生解答准确性，使我们能够追踪这两个目标之间的帕累托前沿。我们的模型比单轮SFT基线更好地保留了推理能力，并可选地通过揭示模型教学规划的思考标签来增强可解释性。

> Large language models (LLMs) can transform education, but their optimization for direct question-answering often undermines effective pedagogy which requires strategically withholding answers. To mitigate this, we propose an online reinforcement learning (RL)-based alignment framework that can quickly adapt LLMs into effective tutors using simulated student-tutor interactions by emphasizing pedagogical quality and guided problem-solving over simply giving away answers. We use our method to train a 7B parameter tutor model without human annotations which reaches similar performance to larger proprietary models like LearnLM. We introduce a controllable reward weighting to balance pedagogical support and student solving accuracy, allowing us to trace the Pareto frontier between these two objectives. Our models better preserve reasoning capabilities than single-turn SFT baselines and can optionally enhance interpretability through thinking tags that expose the model's instructional planning.

[Arxiv](https://arxiv.org/abs/2505.15607)