# 利用交互蒸馏缓解基于偏好奖励建模中的注意力攻击

发布时间：2025年08月04日

`LLM理论` `人工智能`

> Mitigating Attention Hacking in Preference-Based Reward Modeling via Interaction Distillation

# 摘要

> 奖励模型（RM）作为大型语言模型（LLMs）中基于人类反馈的强化学习（RLHF）的核心，负责为生成响应提供奖励信号。然而，主流的偏好建模方法在基于标记的交互层面表现不足，导致其判断信号易受上下文注意力分配不当的攻击。这一问题源于两个根本性限制：（1）当前的偏好建模采用解码器-only架构，单向因果注意力机制导致提示-响应序列内部注意力呈前向衰减趋势。（2）独立的Siamese编码范式导致选择序列与拒绝序列间缺乏基于标记的跨序列注意力。为解决这一“注意力攻击”问题，我们提出“交互蒸馏”这一新型训练框架，通过注意力层面的优化实现更充分的偏好建模。该方法引入基于交互的自然语言理解模型作为教师模型，通过全面注意力机制提供复杂标记交互模式，并引导偏好建模通过注意力对齐目标模拟教师模型的交互模式。通过广泛实验，交互蒸馏展示了相较于针对数据噪声的最先进RM优化方法，它能提供更稳定和通用的奖励信号，凸显出注意力攻击构成RM中的更根本性限制。

> The reward model (RM), as the core component of reinforcement learning from human feedback (RLHF) for large language models (LLMs), responsible for providing reward signals to generated responses. However, mainstream preference modeling in RM is inadequate in terms of token-level interaction, making its judgment signals vulnerable to being hacked by misallocated attention to context. This stems from two fundamental limitations: (1) Current preference modeling employs decoder-only architectures, where the unidirectional causal attention mechanism leads to forward-decaying intra-sequence attention within the prompt-response sequence. (2) The independent Siamese-encoding paradigm induces the absence of token-level inter-sequence attention between chosen and rejected sequences. To address this "attention hacking", we propose "Interaction Distillation", a novel training framework for more adequate preference modeling through attention-level optimization. The method introduces an interaction-based natural language understanding model as the teacher to provide sophisticated token interaction patterns via comprehensive attention, and guides the preference modeling to simulate teacher model's interaction pattern through an attentional alignment objective. Through extensive experiments, interaction distillation has demonstrated its ability to provide more stable and generalizable reward signals compared to state-of-the-art RM optimization methods that target data noise, highlighting the attention hacking constitute a more fundamental limitation in RM.

[Arxiv](https://arxiv.org/abs/2508.02618)