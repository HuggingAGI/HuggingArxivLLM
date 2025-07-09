# VRAgent-R1：利用多模态大语言模型驱动的智能体与强化学习，提升视频推荐效果

发布时间：2025年07月03日

`Agent` `推荐系统` `视频推荐`

> VRAgent-R1: Boosting Video Recommendation with MLLM-based Agents via Reinforcement Learning

# 摘要

> 大型语言模型 (LLM) 代理凭借强大的自然语言处理和生成能力，成为提升推荐系统性能的有力工具，尤其是在用户模拟方面展现出巨大潜力。然而，在视频推荐领域，现有研究主要依赖基于提示的模拟方法，使用冻结的 LLM 来处理多模态内容理解这一复杂挑战，这常常导致物品建模和用户偏好学习效果欠佳，进而限制了推荐性能的提升。为了解决这些问题，我们提出了 VRAgent-R1，这是一种全新的基于代理的范式，通过将人类-like 智能融入用户模拟，为视频推荐系统带来了革新。VRAgent-R1 由两个核心代理组成：项目感知 (IP) 代理和用户模拟 (US) 代理，专为交互式用户-项目建模而设计。首先，IP 代理基于多模态大语言模型 (MLLMs) 模拟人类-like 的逐步推理过程，能够有效捕捉视频中的隐藏推荐语义。通过 IP 代理提供的更全面的多模态内容理解，视频推荐系统得以提供更高质量的候选项目。随后，US 代理通过深入的链式推理 (CoT) 和强化学习，对推荐视频集进行优化，从而更好地与真实用户偏好对齐。实验结果表明，VRAgent-R1 方法在大规模视频推荐基准上表现优异，例如，IP 代理在 MicroLens-100k 数据集上实现了 NDCG@10 的 6.0\% 的提升，而 US 代理在用户决策模拟的准确性方面比最先进的基线高出约 45.0\%。这些成果充分验证了 VRAgent-R1 在视频推荐领域的显著优势和实际应用价值。

> Owing to powerful natural language processing and generative capabilities, large language model (LLM) agents have emerged as a promising solution for enhancing recommendation systems via user simulation. However, in the realm of video recommendation, existing studies predominantly resort to prompt-based simulation using frozen LLMs and encounter the intricate challenge of multimodal content understanding. This frequently results in suboptimal item modeling and user preference learning, thereby ultimately constraining recommendation performance. To address these challenges, we introduce VRAgent-R1, a novel agent-based paradigm that incorporates human-like intelligence in user simulation. Specifically, VRAgent-R1 comprises two distinct agents: the Item Perception (IP) Agent and the User Simulation (US) Agent, designed for interactive user-item modeling. Firstly, the IP Agent emulates human-like progressive thinking based on MLLMs, effectively capturing hidden recommendation semantics in videos. With a more comprehensive multimodal content understanding provided by the IP Agent, the video recommendation system is equipped to provide higher-quality candidate items. Subsequently, the US Agent refines the recommended video sets based on in-depth chain-of-thought (CoT) reasoning and achieves better alignment with real user preferences through reinforcement learning. Experimental results on a large-scale video recommendation benchmark have demonstrated the effectiveness of our proposed VRAgent-R1 method, e.g., the IP Agent achieves a 6.0\% improvement in NDCG@10 on the MicroLens-100k dataset, while the US Agent shows approximately 45.0\% higher accuracy in user decision simulation compared to state-of-the-art baselines.

[Arxiv](https://arxiv.org/abs/2507.02626)