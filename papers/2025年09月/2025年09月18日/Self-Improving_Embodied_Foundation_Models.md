# # 自改进的具身基础模型

发布时间：2025年09月18日

`强化学习` `工业与制造`

> Self-Improving Embodied Foundation Models

# 摘要

> 基于网络规模数据训练的基础模型虽已彻底革新机器人技术，但其在低级控制领域的应用仍主要局限于行为克隆。借鉴大型语言模型微调中强化学习阶段的成功经验，我们提出了一种机器人技术的两阶段后训练方法。第一阶段为监督微调（SFT），它通过两种方式微调预训练基础模型：a) 行为克隆；b) 剩余步骤预测目标。第二阶段为自我改进，剩余步骤预测能够提取出形状良好的奖励函数和稳健的成功检测器，从而使机器人集群能在最少的人类监督下自主练习下游任务。通过在真实世界和模拟机器人实体上的大量实验，我们新颖的后训练方案在具身基础模型上取得了显著成果。首先，我们发现SFT与自我改进的结合在样本效率上显著优于扩大监督学习的模仿数据收集，且能产生成功率显著更高的策略。进一步的消融实验表明，网络规模预训练与自我改进的结合是实现这种样本效率的关键。其次，我们证明该结合方案还独特地实现了当前方法无法企及的能力：自主练习并习得新技能，且这些技能的泛化能力远超训练时所用模仿学习数据集中观察到的行为。这些发现凸显了预训练基础模型与在线自我改进相结合的变革潜力，有望实现机器人的自主技能获取。项目网站详见https://self-improving-efms.github.io。

> Foundation models trained on web-scale data have revolutionized robotics, but their application to low-level control remains largely limited to behavioral cloning. Drawing inspiration from the success of the reinforcement learning stage in fine-tuning large language models, we propose a two-stage post-training approach for robotics. The first stage, Supervised Fine-Tuning (SFT), fine-tunes pretrained foundation models using both: a) behavioral cloning, and b) steps-to-go prediction objectives. In the second stage, Self-Improvement, steps-to-go prediction enables the extraction of a well-shaped reward function and a robust success detector, enabling a fleet of robots to autonomously practice downstream tasks with minimal human supervision. Through extensive experiments on real-world and simulated robot embodiments, our novel post-training recipe unveils significant results on Embodied Foundation Models. First, we demonstrate that the combination of SFT and Self-Improvement is significantly more sample-efficient than scaling imitation data collection for supervised learning, and that it leads to policies with significantly higher success rates. Further ablations highlight that the combination of web-scale pretraining and Self-Improvement is the key to this sample-efficiency. Next, we demonstrate that our proposed combination uniquely unlocks a capability that current methods cannot achieve: autonomously practicing and acquiring novel skills that generalize far beyond the behaviors observed in the imitation learning datasets used during training. These findings highlight the transformative potential of combining pretrained foundation models with online Self-Improvement to enable autonomous skill acquisition in robotics. Our project website can be found at https://self-improving-efms.github.io .

[Arxiv](https://arxiv.org/abs/2509.15155)