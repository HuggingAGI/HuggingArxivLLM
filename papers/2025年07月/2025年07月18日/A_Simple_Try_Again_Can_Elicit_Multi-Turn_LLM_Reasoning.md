# 只需一句"再试一次"，就能激发LLM的多轮推理能力

发布时间：2025年07月18日

`LLM应用` `人工智能`

> A Simple "Try Again" Can Elicit Multi-Turn LLM Reasoning

# 摘要

> 多轮问题解决对大型推理模型 (LRMs) 至关重要，但极具挑战性，因为模型需要反思推理过程并根据反馈进行修正。现有强化学习 (RL) 方法通常基于单轮范式训练推理模型，并使用可验证的奖励。然而，我们发现采用现有 RL 范式训练的模型往往失去在多轮中解决问题的能力，并且难以根据上下文反馈修正答案，导致重复性回应。我们提出疑问：大型推理模型能否在多轮上下文中学会反思其答案？在本研究中，我们发现，仅在错误答案后使用一元反馈（例如，“让我们再试一次”）进行多轮强化学习训练，可以同时提升单轮性能和多轮推理能力。我们引入了一种新的强化学习方法：Unary Feedback as Observation（UFO），它在迭代解决问题过程中使用最少但常见的单元用户反馈。这种方法可以轻松应用于现有的单轮 RL 训练框架。实验结果表明，采用 UFO 进行 RL 训练不仅保持了单轮性能，还将多轮推理准确率提高了高达 14%，从而使语言模型在多轮问题解决中更好地响应反馈。为了进一步减少获得正确答案所需的轮数，同时在出现错误时鼓励多样化的推理，我们设计了奖励结构，引导模型在每一轮中生成谨慎且深思熟虑的回答。代码：https://github.com/lichengliu03/unary-feedback

> Multi-turn problem solving is critical yet challenging for Large Reasoning Models (LRMs) to reflect on their reasoning and revise from feedback. Existing Reinforcement Learning (RL) methods train large reasoning models on a single-turn paradigm with verifiable rewards. However, we observe that models trained with existing RL paradigms often lose their ability to solve problems across multiple turns and struggle to revise answers based on contextual feedback, leading to repetitive responses. We ask: can LRMs learn to reflect their answers in a multi-turn context? In this work, we find that training models with multi-turn RL using only unary feedback (e.g., "Let's try again") after wrong answers can improve both single-turn performance and multi-turn reasoning. We introduce Unary Feedback as Observation (UFO) for reinforcement learning, which uses minimal yet common unary user feedback during iterative problem solving. It can be easily applied to existing single-turn RL training setups. Experimental results show that RL training with UFO keeps single-turn performance and improves multi-turn reasoning accuracy by up to 14%, enabling language models to better react to feedback in multi-turn problem solving. To further minimize the number of turns needed for a correct answer while encouraging diverse reasoning when mistakes occur, we design reward structures that guide models to produce careful and deliberate answers in each turn. Code: https://github.com/lichengliu03/unary-feedback

[Arxiv](https://arxiv.org/abs/2507.14295)