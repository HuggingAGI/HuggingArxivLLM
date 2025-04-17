# SFT 与 RL：探索训练类 R1 推理的大视觉-语言模型的早期研究

发布时间：2025年04月10日

`LLM理论` `计算机视觉` `推理系统`

> SFT or RL? An Early Investigation into Training R1-Like Reasoning Large Vision-Language Models

# 摘要

> 本研究重新审视了大型视觉语言模型（LVLMs）训练中主流的监督微调（SFT）后强化学习（RL）范式，并揭示了一个重要发现：SFT会诱导模仿专家模型生成的“伪推理路径”，从而严重削弱后续强化学习的效果。尽管这些路径看似与RL模型的原生推理路径相似，但它们往往包含冗长、犹豫、信息量较少的步骤以及错误的推理过程。为了系统研究这一现象，我们引入了VLAA-Thinking，一个全新的多模态数据集，旨在支持LVLMs的推理能力。该数据集通过包含图像描述、推理蒸馏、答案重写与验证等六个步骤的流水线构建而成，包含适用于SFT的高质量、分步式视觉推理轨迹，以及来自同一数据源更具挑战性的RL划分。借助这一数据集，我们进行了广泛的实验，比较了SFT、RL及其组合的表现。结果表明，尽管SFT有助于模型学习推理格式，但它常常将对齐后的模型锁定在模仿性和僵化的推理模式中，阻碍了进一步的学习。相比之下，基于群体相对策略优化（GRPO）并结合新型混合奖励模块（整合感知和认知信号）的强化学习方法，能够促进更加真实、灵活的推理行为。值得注意的是，我们的模型VLAA-Thinker（基于Qwen2.5VL 3B）在Open LMM Reasoning Leaderboard（https://huggingface.co/spaces/opencompass/Open_LMM_Reasoning_Leaderboard）中，于40亿规模的LVLMs中排名第一，较先前的最先进模型提升了1.8%的性能。我们希望本研究的发现能为开发具备推理能力的LVLMs提供有价值的见解，并为未来的研究方向提供参考。

> This work revisits the dominant supervised fine-tuning (SFT) then reinforcement learning (RL) paradigm for training Large Vision-Language Models (LVLMs), and reveals a key finding: SFT can significantly undermine subsequent RL by inducing ``pseudo reasoning paths'' imitated from expert models. While these paths may resemble the native reasoning paths of RL models, they often involve prolonged, hesitant, less informative steps, and incorrect reasoning. To systematically study this effect, we introduce VLAA-Thinking, a new multimodal dataset designed to support reasoning in LVLMs. Constructed via a six-step pipeline involving captioning, reasoning distillation, answer rewrite and verification, VLAA-Thinking comprises high-quality, step-by-step visual reasoning traces for SFT, along with a more challenging RL split from the same data source. Using this dataset, we conduct extensive experiments comparing SFT, RL and their combinations. Results show that while SFT helps models learn reasoning formats, it often locks aligned models into imitative, rigid reasoning modes that impede further learning. In contrast, building on the Group Relative Policy Optimization (GRPO) with a novel mixed reward module integrating both perception and cognition signals, our RL approach fosters more genuine, adaptive reasoning behavior. Notably, our model VLAA-Thinker, based on Qwen2.5VL 3B, achieves top-1 performance on Open LMM Reasoning Leaderboard (https://huggingface.co/spaces/opencompass/Open_LMM_Reasoning_Leaderboard) among 4B scale LVLMs, surpassing the previous state-of-the-art by 1.8%. We hope our findings provide valuable insights in developing reasoning-capable LVLMs and can inform future research in this area.

[Arxiv](https://arxiv.org/abs/2504.11468)