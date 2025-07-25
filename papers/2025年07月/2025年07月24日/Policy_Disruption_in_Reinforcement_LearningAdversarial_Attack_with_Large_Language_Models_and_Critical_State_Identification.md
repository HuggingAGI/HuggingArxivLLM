# 强化学习中的策略破坏：基于大型语言模型的对抗攻击与关键状态识别

发布时间：2025年07月24日

`LLM应用` `机器人学` `对抗攻击`

> Policy Disruption in Reinforcement Learning:Adversarial Attack with Large Language Models and Critical State Identification

# 摘要

> 强化学习（RL）在机器人学和自动驾驶等领域取得了显著成功，但针对RL系统的对抗攻击仍然是一个难题。现有方法通常依赖于修改环境或策略，这限制了它们的实际应用。本文提出了一种新的对抗攻击方法：通过环境中的现有代理引导目标策略输出次优动作，而无需改变环境。我们提出了一种基于奖励迭代优化的框架，利用大型语言模型（LLMs）生成专门针对目标代理漏洞的对抗奖励，从而更有效地诱导目标代理做出次优决策。此外，我们设计了一种关键状态识别算法，能够精准定位目标代理最容易受到攻击的状态。在这些状态下，受害者的次优行为会导致整体性能显著下降。实验结果表明，我们的方法在多种环境中均优于现有方法。

> Reinforcement learning (RL) has achieved remarkable success in fields like robotics and autonomous driving, but adversarial attacks designed to mislead RL systems remain challenging. Existing approaches often rely on modifying the environment or policy, limiting their practicality. This paper proposes an adversarial attack method in which existing agents in the environment guide the target policy to output suboptimal actions without altering the environment. We propose a reward iteration optimization framework that leverages large language models (LLMs) to generate adversarial rewards explicitly tailored to the vulnerabilities of the target agent, thereby enhancing the effectiveness of inducing the target agent toward suboptimal decision-making. Additionally, a critical state identification algorithm is designed to pinpoint the target agent's most vulnerable states, where suboptimal behavior from the victim leads to significant degradation in overall performance. Experimental results in diverse environments demonstrate the superiority of our method over existing approaches.

[Arxiv](https://arxiv.org/abs/2507.18113)