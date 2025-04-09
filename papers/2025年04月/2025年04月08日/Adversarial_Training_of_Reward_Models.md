# # 奖励模型的对抗训练方法

发布时间：2025年04月08日

`LLM理论` `人工智能` `机器学习`

> Adversarial Training of Reward Models

# 摘要

> 奖励建模作为一种有前景的方法，近年来被广泛用于实现语言模型的大规模对齐。然而，当代奖励模型（RMs）往往缺乏鲁棒性，容易对低质量的、分布外（OOD）样本赋予高奖励。这种现象可能导致奖励黑客问题，即策略利用未预期的捷径来最大化奖励，从而破坏模型的对齐效果。为了解决这一问题，我们提出了一种新型的对抗训练框架Adv-RM，该框架能够自动识别对抗样本——那些从目标RM获得高奖励但实际上是OOD且质量低劣的响应。

通过利用强化学习，Adv-RM训练一个策略生成对抗样本，这些样本能够可靠地揭示如Nemotron 340B RM等大型先进奖励模型的漏洞。将这些对抗样本纳入奖励训练流程中，可以提升RMs的鲁棒性，减少奖励黑客的发生，并在RLHF中提升下游性能。实验结果表明，Adv-RM在合成数据和真实数据设置下，显著优于传统的RM训练方法，不仅提高了稳定性，还实现了更有效的RLHF训练。


> Reward modeling has emerged as a promising approach for the scalable alignment of language models. However, contemporary reward models (RMs) often lack robustness, awarding high rewards to low-quality, out-of-distribution (OOD) samples. This can lead to reward hacking, where policies exploit unintended shortcuts to maximize rewards, undermining alignment. To address this challenge, we introduce Adv-RM, a novel adversarial training framework that automatically identifies adversarial examples -- responses that receive high rewards from the target RM but are OOD and of low quality. By leveraging reinforcement learning, Adv-RM trains a policy to generate adversarial examples that reliably expose vulnerabilities in large state-of-the-art reward models such as Nemotron 340B RM. Incorporating these adversarial examples into the reward training process improves the robustness of RMs, mitigating reward hacking and enhancing downstream performance in RLHF. We demonstrate that Adv-RM significantly outperforms conventional RM training, increasing stability and enabling more effective RLHF training in both synthetic and real-data settings.

[Arxiv](https://arxiv.org/abs/2504.06141)