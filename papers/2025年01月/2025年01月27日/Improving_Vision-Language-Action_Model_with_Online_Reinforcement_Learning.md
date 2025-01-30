# 通过在线强化学习提升视觉-语言-动作模型

发布时间：2025年01月27日

`Agent

理由：这篇论文主要讨论了如何通过强化学习（RL）进一步优化视觉-语言-动作（VLA）模型，以提升机器人在环境中的交互能力。虽然涉及大型视觉-语言模型（VLMs），但核心关注点是通过强化学习来改进机器人的控制能力，属于智能体（Agent）的范畴。因此，将其分类为Agent更为合适。` `机器人`

> Improving Vision-Language-Action Model with Online Reinforcement Learning

# 摘要

> # 摘要
最近的研究通过专家机器人数据集的监督微调（SFT），成功将大型视觉-语言模型（VLMs）融入低级机器人控制，形成了视觉-语言-动作（VLA）模型。尽管VLA模型表现强大，但在与环境交互时如何进一步提升这些模型仍是一个未解难题。本文探索了如何通过强化学习（RL）进一步优化VLA模型，RL是大型模型常用的微调技术。然而，直接将在线RL应用于大型VLA模型面临显著挑战，包括训练不稳定性和超出本地机器计算能力的负担。为此，我们提出了iRe-VLA框架，通过迭代强化学习和监督学习，有效改进VLA模型，既发挥RL的探索优势，又保持监督学习的稳定性。实验在两个模拟基准和一个真实世界操作套件中验证了该方法的有效性。

> Recent studies have successfully integrated large vision-language models (VLMs) into low-level robotic control by supervised fine-tuning (SFT) with expert robotic datasets, resulting in what we term vision-language-action (VLA) models. Although the VLA models are powerful, how to improve these large models during interaction with environments remains an open question. In this paper, we explore how to further improve these VLA models via Reinforcement Learning (RL), a commonly used fine-tuning technique for large models. However, we find that directly applying online RL to large VLA models presents significant challenges, including training instability that severely impacts the performance of large models, and computing burdens that exceed the capabilities of most local machines. To address these challenges, we propose iRe-VLA framework, which iterates between Reinforcement Learning and Supervised Learning to effectively improve VLA models, leveraging the exploratory benefits of RL while maintaining the stability of supervised learning. Experiments in two simulated benchmarks and a real-world manipulation suite validate the effectiveness of our method.

[Arxiv](https://arxiv.org/abs/2501.16664)