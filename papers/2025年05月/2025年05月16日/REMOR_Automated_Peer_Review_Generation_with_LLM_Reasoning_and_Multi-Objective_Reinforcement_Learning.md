# REMOR: 基于 LLM 推理与多目标强化学习的自动化同行评审生成技术

发布时间：2025年05月16日

`LLM应用` `学术出版` `人工智能`

> REMOR: Automated Peer Review Generation with LLM Reasoning and Multi-Objective Reinforcement Learning

# 摘要

> 基于AI的同行评审系统与人类反馈相比，往往会产生肤浅且过度溢美的建议。我们研究了通过多目标强化学习（REMOR）训练的推理LLM能否克服这些局限性。首先，我们设计了一个多方面的奖励函数，该函数与人类对评审的评价相一致，涵盖评审本身（如批评、新颖性）及评审与手稿的相关性。

我们使用LoRA在PeerRT数据集上对DeepSeek-R1-Distill-Qwen-7B进行监督微调，该数据集包含高质量顶级AI会议评审及推理轨迹。随后，我们应用组相对策略优化（GRPO）训练了两个模型：REMOR-H（采用与人类对齐的奖励）和REMOR-U（采用均匀奖励）。有趣的是，与人类对齐的奖励机制惩罚了通常与优质评审相关的方面，这导致REMOR-U能够生成更具实质性的反馈意见。

实验结果显示，REMOR-U和REMOR-H的平均奖励是人类评审、非推理的最先进代理多模态AI评审系统以及通用商业LLM基线的两倍以上。尽管最好的AI和人类评审在质量上相当，但REMOR避免了低质量人类评审的长尾问题。我们发现，推理是实现这些改进的关键。我们发布了与人类对齐的同行评审奖励（HPRR）函数、同行评审推理增强轨迹（PeerRT）数据集以及REMOR模型，这些资源将助力该领域进一步发展。

> AI-based peer review systems tend to produce shallow and overpraising suggestions compared to human feedback. Here, we evaluate how well a reasoning LLM trained with multi-objective reinforcement learning (REMOR) can overcome these limitations. We start by designing a multi-aspect reward function that aligns with human evaluation of reviews. The aspects are related to the review itself (e.g., criticisms, novelty) and the relationship between the review and the manuscript (i.e., relevance). First, we perform supervised fine-tuning of DeepSeek-R1-Distill-Qwen-7B using LoRA on PeerRT, a new dataset of high-quality top AI conference reviews enriched with reasoning traces. We then apply Group Relative Policy Optimization (GRPO) to train two models: REMOR-H (with the human-aligned reward) and REMOR-U (with a uniform reward). Interestingly, the human-aligned reward penalizes aspects typically associated with strong reviews, leading REMOR-U to produce qualitatively more substantive feedback. Our results show that REMOR-U and REMOR-H achieve more than twice the average rewards of human reviews, non-reasoning state-of-the-art agentic multi-modal AI review systems, and general commercial LLM baselines. We found that while the best AI and human reviews are comparable in quality, REMOR avoids the long tail of low-quality human reviews. We discuss how reasoning is key to achieving these improvements and release the Human-aligned Peer Review Reward (HPRR) function, the Peer Review Reasoning-enriched Traces (PeerRT) dataset, and the REMOR models, which we believe can help spur progress in the area.

[Arxiv](https://arxiv.org/abs/2505.11718)