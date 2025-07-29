# 开放智能体智能：Kimi K2

发布时间：2025年07月28日

`Agent` `软件工程` `人工智能`

> Kimi K2: Open Agentic Intelligence

# 摘要

> 重磅推出 Kimi K2！这是一款拥有320亿激活参数和1万亿总参数的专家混合（MoE）大型语言模型。我们创新性地提出了MuonClip优化器，它基于Muon优化器，并通过独特的QK-clip技术解决了训练过程中的不稳定问题，同时保留了Muon的高效分词能力。基于MuonClip优化器，K2在15.5万亿tokens的数据集上进行预训练，全程零损失波动。

K2的后训练流程亮点纷呈，包括大规模智能体数据合成管道和联合强化学习（RL）阶段，在此过程中，模型通过与真实和合成环境的交互不断提升能力。Kimi K2在开源非思考型模型中表现卓越，尤其在智能体能力方面独树一帜。在多项基准测试中，K2均超越了现有开源和闭源模型，展现了强大的编码、数学和推理能力。

Kimi K2在软件工程和智能体任务方面表现尤为突出，是迄今为止最具能力的开源大型语言模型之一。我们发布了K2的基础模型和后训练模型检查点，诚邀各界共同探索智能体智能的未来！

> We introduce Kimi K2, a Mixture-of-Experts (MoE) large language model with 32 billion activated parameters and 1 trillion total parameters. We propose the MuonClip optimizer, which improves upon Muon with a novel QK-clip technique to address training instability while enjoying the advanced token efficiency of Muon. Based on MuonClip, K2 was pre-trained on 15.5 trillion tokens with zero loss spike. During post-training, K2 undergoes a multi-stage post-training process, highlighted by a large-scale agentic data synthesis pipeline and a joint reinforcement learning (RL) stage, where the model improves its capabilities through interactions with real and synthetic environments.
  Kimi K2 achieves state-of-the-art performance among open-source non-thinking models, with strengths in agentic capabilities. Notably, K2 obtains 66.1 on Tau2-Bench, 76.5 on ACEBench (En), 65.8 on SWE-Bench Verified, and 47.3 on SWE-Bench Multilingual -- surpassing most open and closed-sourced baselines in non-thinking settings. It also exhibits strong capabilities in coding, mathematics, and reasoning tasks, with a score of 53.7 on LiveCodeBench v6, 49.5 on AIME 2025, 75.1 on GPQA-Diamond, and 27.1 on OJBench, all without extended thinking. These results position Kimi K2 as one of the most capable open-source large language models to date, particularly in software engineering and agentic tasks. We release our base and post-trained model checkpoints to facilitate future research and applications of agentic intelligence.

[Arxiv](https://arxiv.org/abs/2507.20534)