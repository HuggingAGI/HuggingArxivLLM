# 谱系策略优化：在 GRPO 中为你的错误推理着色

发布时间：2025年05月16日

`LLM应用` `人工智能`

> Spectral Policy Optimization: Coloring your Incorrect Reasoning in GRPO

# 摘要

> 强化学习（Reinforcement Learning, RL）在提升大型语言模型的推理能力方面取得了显著的成功。其中，组相对策略优化（Group Relative Policy Optimization, GRPO）~\cite{Shao-2024-Deepseekmath} 是应用最广泛的RL方法之一，因其卓越的内存效率和成功训练DeepSeek-R1~\cite{Guo-2025-Deepseek}而备受关注。然而，当所有采样的响应在一个组中均为错误时，GRPO会出现停滞现象——这种情况被称为\emph{全负样本组}——因为它无法更新策略，从而阻碍了学习进程。本文的贡献分为两个方面。首先，我们提出了一种简单而有效的框架，通过引入AI反馈，在GRPO的全负样本组中实现响应多样性。我们还通过一个简化的模型提供了理论分析，展示了这种多样化如何改善学习动力学。其次，我们通过实证验证了我们的方法，在离线和在线学习设置下，使用10个基准测试（包括基础和蒸馏变体），在不同规模的模型（7B、14B、32B）上均表现出改进的性能。我们的研究结果表明，从全负样本组中学习不仅是可行的，而且是有益的，这进一步支持了\citet{Xiong-2025-Minimalist}的最新见解。

> Reinforcement learning (RL) has demonstrated significant success in enhancing reasoning capabilities in large language models (LLMs). One of the most widely used RL methods is Group Relative Policy Optimization (GRPO)~\cite{Shao-2024-Deepseekmath}, known for its memory efficiency and success in training DeepSeek-R1~\cite{Guo-2025-Deepseek}. However, GRPO stalls when all sampled responses in a group are incorrect -- referred to as an \emph{all-negative-sample} group -- as it fails to update the policy, hindering learning progress. The contributions of this paper are two-fold. First, we propose a simple yet effective framework that introduces response diversity within all-negative-sample groups in GRPO using AI feedback. We also provide a theoretical analysis, via a stylized model, showing how this diversification improves learning dynamics. Second, we empirically validate our approach, showing the improved performance across various model sizes (7B, 14B, 32B) in both offline and online learning settings with 10 benchmarks, including base and distilled variants. Our findings highlight that learning from all-negative-sample groups is not only feasible but beneficial, advancing recent insights from \citet{Xiong-2025-Minimalist}.

[Arxiv](https://arxiv.org/abs/2505.11595)