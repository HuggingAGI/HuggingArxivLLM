# 无限深度视频探索

发布时间：2025年07月11日

`LLM应用` `多媒体` `多模态`

> Infinite Video Understanding

# 摘要

> 大型语言模型（LLMs）及其多模态扩展（MLLMs）的快速发展为视频理解带来了显著进步。然而，如何有效处理和理解时长超过几分钟或几小时的视频内容仍然是一个根本性挑战。近期，Video-XL-2展示了在极端效率方面的新型架构解决方案，而HoPE和VideoRoPE++等位置编码方法的进步旨在提高对广泛上下文的空间-时间理解。然而，面对长序列产生的大量视觉令牌，当前最先进的模型仍面临显著的计算和内存限制。尽管在Deep Video Discovery等能动推理系统方面取得了进展，但在长时间跨度内保持时间连贯性、跟踪复杂事件以及保留精细细节仍然是一项艰巨的挑战。本文提出，无限视频理解——即模型能够持续处理、理解和推理任意时长、甚至可能无限延续的视频数据——是个多模态研究的合乎逻辑但雄心勃勃的下一个前沿领域。我们主张，将无限视频理解视为一项蓝 sky 研究目标，为多媒体领域乃至更广泛的AI研究社区提供了一个至关重要的指导方向，推动了流式架构、持久化内存机制、层次化与自适应表示、事件中心推理以及新型评估范式等领域的创新。本文从近期关于长/超长视频理解的研究和多个相关领域中汲取灵感，概述了实现这一变革性能力的核心挑战和关键研究方向。

> The rapid advancements in Large Language Models (LLMs) and their multimodal extensions (MLLMs) have ushered in remarkable progress in video understanding. However, a fundamental challenge persists: effectively processing and comprehending video content that extends beyond minutes or hours. While recent efforts like Video-XL-2 have demonstrated novel architectural solutions for extreme efficiency, and advancements in positional encoding such as HoPE and VideoRoPE++ aim to improve spatio-temporal understanding over extensive contexts, current state-of-the-art models still encounter significant computational and memory constraints when faced with the sheer volume of visual tokens from lengthy sequences. Furthermore, maintaining temporal coherence, tracking complex events, and preserving fine-grained details over extended periods remain formidable hurdles, despite progress in agentic reasoning systems like Deep Video Discovery. This position paper posits that a logical, albeit ambitious, next frontier for multimedia research is Infinite Video Understanding -- the capability for models to continuously process, understand, and reason about video data of arbitrary, potentially never-ending duration. We argue that framing Infinite Video Understanding as a blue-sky research objective provides a vital north star for the multimedia, and the wider AI, research communities, driving innovation in areas such as streaming architectures, persistent memory mechanisms, hierarchical and adaptive representations, event-centric reasoning, and novel evaluation paradigms. Drawing inspiration from recent work on long/ultra-long video understanding and several closely related fields, we outline the core challenges and key research directions towards achieving this transformative capability.

[Arxiv](https://arxiv.org/abs/2507.09068)