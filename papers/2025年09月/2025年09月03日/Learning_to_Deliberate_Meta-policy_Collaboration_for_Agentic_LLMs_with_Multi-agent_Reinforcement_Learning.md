# 学会深思熟虑：基于多智能体强化学习的智能体LLM元策略协作

发布时间：2025年09月03日

`Agent` `基础理论`

> Learning to Deliberate: Meta-policy Collaboration for Agentic LLMs with Multi-agent Reinforcement Learning

# 摘要

> 大型语言模型（LLMs）的多智能体系统在复杂推理领域颇具潜力，但其效能常受限于固定协作协议。这些框架往往聚焦宏观层面的流程编排，却忽视了智能体的内部审慎能力。这一关键的元认知盲区将智能体视作被动执行者，使其无法依据不确定性或信心等内在认知状态调整策略。为此，我们提出元策略审慎框架（MPDF）：智能体可针对坚持（Persist）、优化（Refine）、让步（Concede）这三类高级元认知动作，自主学习去中心化策略。为解决传统策略梯度在此场景下的不稳定性，我们研发了新型强化学习算法SoftRankPO。该算法通过平滑正态分位数映射奖励排序并据此塑造优势，有效稳定训练过程，增强了学习对奖励波动的鲁棒性。实验显示，与六种最先进的启发式及学习型多智能体推理算法相比，集成SoftRankPO的MPDF在五个数学与通用推理基准测试中，平均准确率绝对值提升4-5%。本研究为多智能体LLM系统开辟了自适应元认知策略学习的新范式，将研究重心从固定协议设计转向动态审慎策略的学习。

> Multi-agent systems of large language models (LLMs) show promise for complex reasoning, but their effectiveness is often limited by fixed collaboration protocols. These frameworks typically focus on macro-level orchestration while overlooking agents' internal deliberative capabilities. This critical meta-cognitive blindspot treats agents as passive executors unable to adapt their strategy based on internal cognitive states like uncertainty or confidence. We introduce the Meta-Policy Deliberation Framework (MPDF), where agents learn a decentralized policy over a set of high-level meta-cognitive actions: Persist, Refine, and Concede. To overcome the instability of traditional policy gradients in this setting, we develop SoftRankPO, a novel reinforcement learning algorithm. SoftRankPO stabilizes training by shaping advantages based on the rank of rewards mapped through smooth normal quantiles, making the learning process robust to reward variance. Experiments show that MPDF with SoftRankPO achieves a a 4-5% absolute gain in average accuracy across five mathematical and general reasoning benchmarks compared to six state-of-the-art heuristic and learning-based multi-agent reasoning algorithms. Our work presents a paradigm for learning adaptive, meta-cognitive policies for multi-agent LLM systems, shifting the focus from designing fixed protocols to learning dynamic, deliberative strategies.

[Arxiv](https://arxiv.org/abs/2509.03817)