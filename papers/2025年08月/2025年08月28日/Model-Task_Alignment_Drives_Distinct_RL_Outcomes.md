# 模型-任务对齐驱动强化学习的不同结果

发布时间：2025年08月28日

`强化学习` `基础理论`

> Model-Task Alignment Drives Distinct RL Outcomes

# 摘要

> 强化学习（RL）在大型语言模型（LLMs）中的应用近期取得了显著进展。尤其是，LLMs中出现了一系列令人瞩目的反直觉现象，这些现象呈现出传统RL场景中罕见的规律。例如，有观点称单个训练样本就能媲美全数据集训练的效果，奖励信号无需高度精确，仅用负样本训练甚至能比肩乃至超越复杂的基于奖励的方法——这些说法虽引人注目，却与直觉相悖。但这些现象成立的确切条件，尤其是它们何时会失效，目前仍不明确。本研究发现，区分这些RL现象的关键在于：预训练模型是否已具备强模型-任务对齐能力（通过评估任务的pass@k准确率衡量）。我们通过系统全面地考察这些反直觉观点，并在不同模型架构和任务领域进行严格实验验证后发现：标准RL训练在各类场景中始终稳健有效，而那些反直觉结果往往只在模型与任务已高度对齐时才会产生。相反，在更具挑战性的场景中，这些技术难以实现有效学习，此时标准RL方法反而更为可靠。

> Recent advances in applying reinforcement learning (RL) to large language models (LLMs) have led to substantial progress. In particular, a series of remarkable yet often counterintuitive phenomena have been reported in LLMs, exhibiting patterns not typically observed in traditional RL settings. For example, notable claims include that a single training example can match the performance achieved with an entire dataset, that the reward signal does not need to be very accurate, and that training solely with negative samples can match or even surpass sophisticated reward-based methods. However, the precise conditions under which these observations hold - and, critically, when they fail - remain unclear. In this work, we identify a key factor that differentiates RL observations: whether the pretrained model already exhibits strong Model-Task Alignment, as measured by pass@k accuracy on the evaluated task. Through a systematic and comprehensive examination of a series of counterintuitive claims, supported by rigorous experimental validation across different model architectures and task domains, our findings show that while standard RL training remains consistently robust across settings, many of these counterintuitive results arise only when the model and task already exhibit strong model-task alignment. In contrast, these techniques fail to drive substantial learning in more challenging regimes, where standard RL methods remain effective.

[Arxiv](https://arxiv.org/abs/2508.21188)