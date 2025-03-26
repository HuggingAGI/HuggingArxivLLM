# OpenVLThinker：迭代自我改进驱动的复杂视觉语言推理早期探索

发布时间：2025年03月21日

`LLM应用` `计算机视觉` `多模态推理`

> OpenVLThinker: An Early Exploration to Complex Vision-Language Reasoning via Iterative Self-Improvement

# 摘要

> DeepSeek-R1近期的研究成果表明，大型语言模型（LLMs）的复杂推理能力，包括自我验证和自我纠错等高级行为，可以通过带有可验证奖励的强化学习（RL）实现，并显著提升模型在如AIME等具有挑战性任务上的性能。受此启发，我们的研究旨在探索是否能将类似推理能力成功整合到大型视觉-语言模型（LVLMs）中，并评估其对复杂多模态推理任务的影响。

我们采用了一种迭代方法，结合轻量级训练数据上的监督微调（SFT）与强化学习（RL），以进一步提升模型的泛化能力。最初，我们通过生成高质量图像描述（源自多样化的视觉数据集）来提取纯文本R1模型的推理能力。随后，迭代RL训练进一步增强了推理技能，每次迭代中经RL优化的模型生成更优质的SFT数据集用于下一轮训练。这一迭代过程最终孕育出OpenVLThinker——一款LVLM，在MathVista、MathVerse和MathVision等具有挑战性的基准测试中展现出持续提升的推理性能，彰显了我们策略在强健视觉-语言推理方面的潜力。

代码、模型及数据已托管于：https://github.com/yihedeng9/OpenVLThinker。


> Recent advancements demonstrated by DeepSeek-R1 have shown that complex reasoning abilities in large language models (LLMs), including sophisticated behaviors such as self-verification and self-correction, can be achieved by RL with verifiable rewards and significantly improves model performance on challenging tasks such as AIME. Motivated by these findings, our study investigates whether similar reasoning capabilities can be successfully integrated into large vision-language models (LVLMs) and assesses their impact on challenging multimodal reasoning tasks. We consider an approach that iteratively leverages supervised fine-tuning (SFT) on lightweight training data and Reinforcement Learning (RL) to further improve model generalization. Initially, reasoning capabilities were distilled from pure-text R1 models by generating reasoning steps using high-quality captions of the images sourced from diverse visual datasets. Subsequently, iterative RL training further enhance reasoning skills, with each iteration's RL-improved model generating refined SFT datasets for the next round. This iterative process yielded OpenVLThinker, a LVLM exhibiting consistently improved reasoning performance on challenging benchmarks such as MathVista, MathVerse, and MathVision, demonstrating the potential of our strategy for robust vision-language reasoning. The code, model and data are held at https://github.com/yihedeng9/OpenVLThinker.

[Arxiv](https://arxiv.org/abs/2503.17352)