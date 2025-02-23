# AlphaMaze：借助 GRPO 增强大型语言模型的空间智能

发布时间：2025年02月20日

`LLM应用` `机器人学` `自主导航`

> AlphaMaze: Enhancing Large Language Models' Spatial Intelligence via GRPO

# 摘要

> 大型语言模型（LLMs）在语言处理方面表现出色，但在涉及真实视觉空间推理的任务上仍显不足。本文提出了一种创新的两阶段训练框架，旨在赋予标准LLMs迷宫导航所需的视觉推理能力。首先，我们通过监督微调（SFT）在精选的分词化迷宫表示数据集上训练模型，使其掌握逐步预测移动指令的能力。随后，我们采用DeepSeekR1中使用的组相对策略优化（GRPO）技术，结合精心设计的奖励函数，进一步优化模型的序列决策能力，同时促进链式推理行为的自然生成。实验结果显示，在合成生成的迷宫中，基准模型无法完成导航任务，而经过SFT训练的模型准确率达到86%，进一步通过GRPO微调后，准确率提升至93%。质性分析表明，GRPO培养了更为稳健和自我修正的推理能力，凸显了我们的方法在弥合语言模型与视觉空间任务之间差距方面的潜力。这些发现为机器人学、自主导航以及需要结合视觉与序列推理的其他领域带来了令人鼓舞的应用前景。

> Large Language Models (LLMs) have demonstrated impressive capabilities in language processing, yet they often struggle with tasks requiring genuine visual spatial reasoning. In this paper, we introduce a novel two-stage training framework designed to equip standard LLMs with visual reasoning abilities for maze navigation. First, we leverage Supervised Fine Tuning (SFT) on a curated dataset of tokenized maze representations to teach the model to predict step-by-step movement commands. Next, we apply Group Relative Policy Optimization (GRPO)-a technique used in DeepSeekR1-with a carefully crafted reward function to refine the model's sequential decision-making and encourage emergent chain-of-thought behaviors. Experimental results on synthetically generated mazes show that while a baseline model fails to navigate the maze, the SFT-trained model achieves 86% accuracy, and further GRPO fine-tuning boosts accuracy to 93%. Qualitative analyses reveal that GRPO fosters more robust and self-corrective reasoning, highlighting the potential of our approach to bridge the gap between language models and visual spatial tasks. These findings offer promising implications for applications in robotics, autonomous navigation, and other domains that require integrated visual and sequential reasoning.

[Arxiv](https://arxiv.org/abs/2502.14669)