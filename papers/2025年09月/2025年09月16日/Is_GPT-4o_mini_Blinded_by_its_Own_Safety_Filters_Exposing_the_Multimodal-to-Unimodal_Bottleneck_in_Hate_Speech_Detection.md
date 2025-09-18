# GPT-4o mini 是否被自身安全过滤器“蒙蔽双眼”？揭露仇恨言论检测中的多模态转单模态瓶颈

发布时间：2025年09月16日

`LLM应用` `基础理论`

> Is GPT-4o mini Blinded by its Own Safety Filters? Exposing the Multimodal-to-Unimodal Bottleneck in Hate Speech Detection

# 摘要

> 随着大型多模态模型（LMMs）日益融入日常数字生活，理解其安全架构已成为AI对齐领域的关键课题。本文以全球部署的OpenAI模型GPT-4o mini为研究对象，针对多模态仇恨言论检测这一难题展开系统分析。借助Hateful Memes Challenge数据集，我们对500个样本开展多阶段研究，深入探究该模型的推理机制与失效模式。核心发现是通过实验识别出“单模态瓶颈”（Unimodal Bottleneck）——这一架构缺陷会导致模型先进的多模态推理能力被上下文盲安全过滤器系统性压制。对144次内容政策拒绝案例的定量验证表明，这些拦截行为由单模态内容触发的比例各占一半：视觉内容50%，文本内容50%。我们还发现，该安全系统十分脆弱：不仅会拦截高风险图像，还会误判良性、常见的表情包格式，进而产生可预见的误报。这些发现揭示了最先进LMMs在能力与安全之间的根本冲突，凸显了制定更集成、上下文感知的对齐策略的必要性，从而确保AI系统既能安全部署，又能有效发挥作用。

> As Large Multimodal Models (LMMs) become integral to daily digital life, understanding their safety architectures is a critical problem for AI Alignment. This paper presents a systematic analysis of OpenAI's GPT-4o mini, a globally deployed model, on the difficult task of multimodal hate speech detection. Using the Hateful Memes Challenge dataset, we conduct a multi-phase investigation on 500 samples to probe the model's reasoning and failure modes. Our central finding is the experimental identification of a "Unimodal Bottleneck," an architectural flaw where the model's advanced multimodal reasoning is systematically preempted by context-blind safety filters. A quantitative validation of 144 content policy refusals reveals that these overrides are triggered in equal measure by unimodal visual 50% and textual 50% content. We further demonstrate that this safety system is brittle, blocking not only high-risk imagery but also benign, common meme formats, leading to predictable false positives. These findings expose a fundamental tension between capability and safety in state-of-the-art LMMs, highlighting the need for more integrated, context-aware alignment strategies to ensure AI systems can be deployed both safely and effectively.

[Arxiv](https://arxiv.org/abs/2509.13608)