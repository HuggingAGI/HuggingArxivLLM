# 利用通信游戏实现的自然语言生成，无需额外数据即可提升图像描述能力

发布时间：2025年07月11日

`Agent` `计算机视觉`

> Emergent Natural Language with Communication Games for Improving Image Captioning Capabilities without Additional Data

# 摘要

> 图像描述生成是AI系统开发中的核心任务，但现有标注数据集已被用于训练大型视觉语言模型（VLMs），进一步提升性能极具挑战性。因此，探索无监督图像描述生成具有重要意义。

我们提出了LoGIC（用于图像描述生成的刘易斯通信游戏），这是一个多智能体强化学习框架。该方法包含“说话者”和“倾听者”两个角色，目标是学习自然语言交流策略。采用GRPO算法在合作共同奖励设置下训练智能体，证明图像描述生成性能提升源于智能体学习过程。

实验显示，使用预训练VLM作为“说话者”，LLM作为“倾听者”进行微调，BLEU分数达46，较基础VLM高出2个单位。进一步将VLM替换为轻量级组件（ViT和GPT2）并从头训练，在无监督设置下BLEU分数达31，较现有方法高出10个点。


> Image captioning is an important problem in developing various AI systems, and these tasks require large volumes of annotated images to train the models. Since all existing labelled datasets are already used for training the large Vision Language Models (VLMs), it becomes challenging to improve the performance of the same. Considering this, it is essential to consider the unsupervised image captioning performance, which remains relatively under-explored. To that end, we propose LoGIC (Lewis Communication Game for Image Captioning), a Multi-agent Reinforcement Learning game. The proposed method consists of two agents, a 'speaker' and a 'listener', with the objective of learning a strategy for communicating in natural language. We train agents in the cooperative common-reward setting using the GRPO algorithm and show that improvement in image captioning performance emerges as a consequence of the agents learning to play the game. We show that using pre-trained VLMs as the 'speaker' and Large Language Model (LLM) for language understanding in the 'listener', we achieved a $46$ BLEU score after fine-tuning using LoGIC without additional labels, a $2$ units advantage in absolute metrics compared to the $44$ BLEU score of the vanilla VLM. Additionally, we replace the VLM from the 'speaker' with lightweight components: (i) a ViT for image perception and (ii) a GPT2 language generation, and train them from scratch using LoGIC, obtaining a $31$ BLEU score in the unsupervised setting, a $10$ points advantage over existing unsupervised image-captioning methods.

[Arxiv](https://arxiv.org/abs/2507.08610)