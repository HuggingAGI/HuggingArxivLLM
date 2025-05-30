# # 基于效用反馈的LLM讨价还价代理
大型语言模型 (LLM) 在基于效用反馈的讨价还价中的应用研究

发布时间：2025年05月28日

`LLM应用

理由：这篇论文探讨了如何将大型语言模型（LLMs）应用于现实世界的讨价还价场景，提出了一种基于效用反馈的框架，包括新的数据集、评估指标和反馈机制。其核心是提升LLMs在谈判中的策略性和对手感知推理能力，属于LLM的具体应用。` `电子商务`

> LLM Agents for Bargaining with Utility-based Feedback

# 摘要

> 讨价还价是现实世界互动中至关重要的一环，但大型语言模型（LLMs）在这一领域面临着战略深度和对复杂人类因素适应能力的局限。现有的基准测试往往无法捕捉到这种现实世界的复杂性。为了解决这一问题并提升LLMs在现实讨价还价中的能力，我们提出了一套基于效用反馈的综合性框架。

我们的贡献有三：首先，我们开发了BargainArena，一个包含六种复杂场景（如欺骗行为、垄断等）的新型基准数据集，旨在促进多样化的策略建模；其次，我们设计了以效用理论为灵感的与人类行为一致且具有经济基础的评估指标，这些指标结合了代理效用和谈判能力，能够隐式地反映并促进对手感知推理（OAR）；最后，我们提出了一种结构化的反馈机制，使LLMs能够迭代优化其讨价还价策略。该机制可以与上下文学习（ICL）提示协同工作，包括那些专门设计用于促进OAR的提示。

实验结果表明，LLMs经常表现出与人类偏好不一致的谈判策略，而我们的结构化反馈机制显著提升了其性能，带来了更深入的战略性和对手感知推理能力。

> Bargaining, a critical aspect of real-world interactions, presents challenges for large language models (LLMs) due to limitations in strategic depth and adaptation to complex human factors. Existing benchmarks often fail to capture this real-world complexity. To address this and enhance LLM capabilities in realistic bargaining, we introduce a comprehensive framework centered on utility-based feedback. Our contributions are threefold: (1) BargainArena, a novel benchmark dataset with six intricate scenarios (e.g., deceptive practices, monopolies) to facilitate diverse strategy modeling; (2) human-aligned, economically-grounded evaluation metrics inspired by utility theory, incorporating agent utility and negotiation power, which implicitly reflect and promote opponent-aware reasoning (OAR); and (3) a structured feedback mechanism enabling LLMs to iteratively refine their bargaining strategies. This mechanism can positively collaborate with in-context learning (ICL) prompts, including those explicitly designed to foster OAR. Experimental results show that LLMs often exhibit negotiation strategies misaligned with human preferences, and that our structured feedback mechanism significantly improves their performance, yielding deeper strategic and opponent-aware reasoning.

[Arxiv](https://arxiv.org/abs/2505.22998)