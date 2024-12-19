# 设计一个基于 LLM 的制造设备选型副驾驶

发布时间：2024年12月18日

`LLM应用` `自动化`

> Designing an LLM-Based Copilot for Manufacturing Equipment Selection

# 摘要

> 在自动化设备的选择中，做出有效的决策对于缩短爬坡时间、维持生产质量极为关键，尤其在产品变化增多、市场需求增长的情况下。然而，专业知识有限和资源受限常致使新产品融入生产线的爬坡阶段效率低下。现有的方法往往缺少结构化和定制化的解决方案，难以协助自动化工程师缩短爬坡时间，进而造成质量上的让步。本研究探究大型语言模型（LLMs）与检索增强生成（RAG）相结合能否助力爬坡规划中的设备选择流程简化。我们提出了一个事实驱动的副驾驶，将 LLMs 与结构化和半结构化知识检索相融合，应用于三种组件类型（机器人、送料器和视觉系统），为自动化设备选择的决策提供了一个有引导且可追溯的状态机流程。该系统向一家工业合作伙伴进行了展示，该伙伴在三个内部用例上对其进行了测试。他们的反馈证实了其为自动化设备提供有逻辑且可行建议的能力。更具体而言，在分析的 22 个设备提示中，有 19 个在考虑多数要求的情况下选对了设备，在 6 个案例中，所有要求均完全得到满足。

> Effective decision-making in automation equipment selection is critical for reducing ramp-up time and maintaining production quality, especially in the face of increasing product variation and market demands. However, limited expertise and resource constraints often result in inefficiencies during the ramp-up phase when new products are integrated into production lines. Existing methods often lack structured and tailored solutions to support automation engineers in reducing ramp-up time, leading to compromises in quality. This research investigates whether large-language models (LLMs), combined with Retrieval-Augmented Generation (RAG), can assist in streamlining equipment selection in ramp-up planning. We propose a factual-driven copilot integrating LLMs with structured and semi-structured knowledge retrieval for three component types (robots, feeders and vision systems), providing a guided and traceable state-machine process for decision-making in automation equipment selection. The system was demonstrated to an industrial partner, who tested it on three internal use-cases. Their feedback affirmed its capability to provide logical and actionable recommendations for automation equipment. More specifically, among 22 equipment prompts analyzed, 19 involved selecting the correct equipment while considering most requirements, and in 6 cases, all requirements were fully met.

[Arxiv](https://arxiv.org/abs/2412.13774)