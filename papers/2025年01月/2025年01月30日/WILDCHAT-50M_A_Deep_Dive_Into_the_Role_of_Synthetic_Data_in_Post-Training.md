# WILDCHAT-50M: 合成数据在训练后阶段的作用深度解析

发布时间：2025年01月30日

`LLM应用

**理由**：这篇论文主要讨论了语言模型（LLM）的后训练技术，特别是通过合成数据生成模型和LLM评判者进行大规模比较分析，并推出了一个公开的聊天数据集WILDCHAT-50M。这些内容涉及LLM的实际应用和优化，因此应归类为LLM应用。` `聊天机器人`

> WILDCHAT-50M: A Deep Dive Into the Role of Synthetic Data in Post-Training

# 摘要

> # 语言模型（LLM）的后训练，从DPO到蒸馏，能够优化行为并解锁新技能，但相关开放科学仍处于初期阶段。一个主要挑战在于对合成数据生成模型和LLM评判者进行大规模比较分析的难度。为此，我们推出了WILDCHAT-50M，这是目前最大的公开聊天数据集。我们在现有WildChat数据集的基础上，不仅纳入了GPT的响应，还涵盖了超过50种不同开放权重模型的响应，参数规模从0.5B到104B不等。通过广泛的比较分析，我们展示了该数据集的潜力，并创建了RE-WILD（我们自己的公开SFT混合），该混合在仅使用40%样本的情况下超越了Allen AI的Tulu-3 SFT混合。数据集、样本和代码可在https://github.com/penfever/wildchat-50m获取。

> Language model (LLM) post-training, from DPO to distillation, can refine behaviors and unlock new skills, but the open science supporting these post-training techniques is still in its infancy. One limiting factor has been the difficulty of conducting large-scale comparative analyses of synthetic data generating models and LLM judges. To close this gap, we introduce WILDCHAT-50M, the largest public chat dataset to date. We extend the existing WildChat dataset to include responses not only from GPT, but from over 50 different open-weight models, ranging in size from 0.5B to 104B parameters. We conduct an extensive comparative analysis and demonstrate the potential of this dataset by creating RE-WILD, our own public SFT mix, which outperforms the recent Tulu-3 SFT mixture from Allen AI with only 40% as many samples. Our dataset, samples and code are available at https://github.com/penfever/wildchat-50m.

[Arxiv](https://arxiv.org/abs/2501.18511)