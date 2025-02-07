# 隐式奖励驱动的过程强化

发布时间：2025年02月03日

`LLM理论

理由：该论文主要讨论了在大型语言模型（LLM）的强化学习中使用密集过程奖励的潜力，并提出了一种新的方法（PRIME）来在线更新过程奖励模型（PRMs）。论文的核心内容涉及LLM的训练方法、奖励机制和推理扩展，这些都是LLM理论研究的范畴。因此，将其分类为LLM理论是合适的。` `软件开发`

> Process Reinforcement through Implicit Rewards

# 摘要

> 密集过程奖励在LLMs推理扩展中表现优于稀疏结果奖励，尤其在复杂多步推理任务中。尽管密集奖励在LLMs的强化学习中颇具潜力，能解决训练效率和信用分配等问题，但其潜力尚未充分挖掘。这主要源于在线训练过程奖励模型（PRMs）的挑战：高质量过程标签的收集成本高昂，且易受奖励攻击。为此，我们提出PRIME（通过隐式奖励进行过程强化），仅需策略滚动和结果标签即可在线更新PRMs。PRIME兼容多种优势函数，无需专用奖励模型训练，大幅降低开发成本。在竞赛数学和编码任务中，PRIME从Qwen2.5-Math-7B-Base出发，在多个推理基准上平均提升15.1%。最终模型Eurus-2-7B-PRIME在七个推理基准上超越Qwen2.5-Math-7B-Instruct，且仅使用其10%的训练数据。

> Dense process rewards have proven a more effective alternative to the sparse outcome-level rewards in the inference-time scaling of large language models (LLMs), particularly in tasks requiring complex multi-step reasoning. While dense rewards also offer an appealing choice for the reinforcement learning (RL) of LLMs since their fine-grained rewards have the potential to address some inherent issues of outcome rewards, such as training efficiency and credit assignment, this potential remains largely unrealized. This can be primarily attributed to the challenges of training process reward models (PRMs) online, where collecting high-quality process labels is prohibitively expensive, making them particularly vulnerable to reward hacking. To address these challenges, we propose PRIME (Process Reinforcement through IMplicit rEwards), which enables online PRM updates using only policy rollouts and outcome labels through implict process rewards. PRIME combines well with various advantage functions and forgoes the dedicated reward model training phrase that existing approaches require, substantially reducing the development overhead. We demonstrate PRIME's effectiveness on competitional math and coding. Starting from Qwen2.5-Math-7B-Base, PRIME achieves a 15.1% average improvement across several key reasoning benchmarks over the SFT model. Notably, our resulting model, Eurus-2-7B-PRIME, surpasses Qwen2.5-Math-7B-Instruct on seven reasoning benchmarks with 10% of its training data.

[Arxiv](https://arxiv.org/abs/2502.01456)