# WALL-E 2.0：神经符号学习实现世界对齐，提升基于世界模型的LLM智能体性能

发布时间：2025年04月22日

`LLM应用` `机器人` `环境建模`

> WALL-E 2.0: World Alignment by NeuroSymbolic Learning improves World Model-based LLM Agents

# 摘要

> 我们能否利用大型语言模型 (LLMs) 构建准确的世界模型？世界模型又将如何赋能 LLM 代理？LLMs 的先验知识与实际环境动态之间的鸿沟通常限制了其作为世界模型的性能。为突破这一限制，我们提出了一种无需训练的“世界对齐”方法，用于学习与 LLMs 相辅相成的环境符号知识。这些符号知识涵盖动作规则、知识图谱和场景图谱，由 LLMs 从探索轨迹中提取，并编码为可执行代码，从而规范 LLM 代理的行为策略。我们进一步通过模型预测控制 (MPC) 框架提出了一种无需强化学习、基于模型的代理“WALL-E 2.0”。与传统 MPC 需要实时进行昂贵优化不同，我们采用 LLM 代理作为与神经符号世界模型交互的高效未来动作 lookahead 优化器。虽然 LLM 代理的强启发性使其成为 MPC 中的高效规划器，但其规划动作的质量也得到了对齐后世界模型准确预测的保障。这种结合在新环境中显著提升了学习效率。在火星（类似 Minecraft）和 ALFWorld（具身化室内环境）的开放世界挑战中，WALL-E 2.0 远超现有方法，例如在火星上的成功率比基准高出 16.1%-51.6%，得分至少高出 61.7%。在 ALFWorld 中，仅经过 4 次迭代，它就达到了 98% 的成功率新纪录。

> Can we build accurate world models out of large language models (LLMs)? How can world models benefit LLM agents? The gap between the prior knowledge of LLMs and the specified environment's dynamics usually bottlenecks LLMs' performance as world models. To bridge the gap, we propose a training-free "world alignment" that learns an environment's symbolic knowledge complementary to LLMs. The symbolic knowledge covers action rules, knowledge graphs, and scene graphs, which are extracted by LLMs from exploration trajectories and encoded into executable codes to regulate LLM agents' policies. We further propose an RL-free, model-based agent "WALL-E 2.0" through the model-predictive control (MPC) framework. Unlike classical MPC requiring costly optimization on the fly, we adopt an LLM agent as an efficient look-ahead optimizer of future steps' actions by interacting with the neurosymbolic world model. While the LLM agent's strong heuristics make it an efficient planner in MPC, the quality of its planned actions is also secured by the accurate predictions of the aligned world model. They together considerably improve learning efficiency in a new environment. On open-world challenges in Mars (Minecraft like) and ALFWorld (embodied indoor environments), WALL-E 2.0 significantly outperforms existing methods, e.g., surpassing baselines in Mars by 16.1%-51.6% of success rate and by at least 61.7% in score. In ALFWorld, it achieves a new record 98% success rate after only 4 iterations.

[Arxiv](https://arxiv.org/abs/2504.15785)