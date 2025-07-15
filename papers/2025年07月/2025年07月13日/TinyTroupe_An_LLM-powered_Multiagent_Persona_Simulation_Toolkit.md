# TinyTroupe：基于LLM的多智能体角色模拟工具包

发布时间：2025年07月13日

`Agent` `多智能体系统` `社会仿真`

> TinyTroupe: An LLM-powered Multiagent Persona Simulation Toolkit

# 摘要

> 大型语言模型 (LLM) 的突破性进展催生了新一代自主代理，重新激发了人们对这一领域的兴趣。由此，兼具辅助功能与仿真能力的 LLM 驱动型多智能体系统 (MAS) 应运而生。然而，尽管前景广阔，用于模拟人类行为的现实工具仍处于初级开发阶段，面临着独特挑战与机遇。现有的 MAS 库与工具在细致人格设定、群体采样功能、实验支持及集成验证等方面存在诸多不足，这限制了它们在行为研究、社会仿真及相关应用中的实用性。

为解决这些问题，本研究推出了 TinyTroupe——一款功能强大的仿真工具包。它支持详细的人格定义（如国籍、年龄、职业、性格、信仰、行为）并通过多种 LLM 驱动机制实现程序化控制。这使得能够简洁地表述具有实际意义的行为问题，无论是在个体层面还是群体层面，并提供了有效的解决手段。

通过代表性的工作示例，如头脑风暴和市场调研会议，我们清晰地展示了 TinyTroupe 各组件的目的及其实际价值。同时，对选定方面的定量和定性评估也突显了其可能性、局限性以及权衡取舍。尽管该方法以特定的 Python 实现呈现，但其旨在作为一项新颖的概念性贡献，可部分或完全融入其他语境。该库作为开源代码可在 https://github.com/microsoft/tinytroupe 获取。

> Recent advances in Large Language Models (LLM) have led to a new class of autonomous agents, renewing and expanding interest in the area. LLM-powered Multiagent Systems (MAS) have thus emerged, both for assistive and simulation purposes, yet tools for realistic human behavior simulation -- with its distinctive challenges and opportunities -- remain underdeveloped. Existing MAS libraries and tools lack fine-grained persona specifications, population sampling facilities, experimentation support, and integrated validation, among other key capabilities, limiting their utility for behavioral studies, social simulation, and related applications. To address these deficiencies, in this work we introduce TinyTroupe, a simulation toolkit enabling detailed persona definitions (e.g., nationality, age, occupation, personality, beliefs, behaviors) and programmatic control via numerous LLM-driven mechanisms. This allows for the concise formulation of behavioral problems of practical interest, either at the individual or group level, and provides effective means for their solution. TinyTroupe's components are presented using representative working examples, such as brainstorming and market research sessions, thereby simultaneously clarifying their purpose and demonstrating their usefulness. Quantitative and qualitative evaluations of selected aspects are also provided, highlighting possibilities, limitations, and trade-offs. The approach, though realized as a specific Python implementation, is meant as a novel conceptual contribution, which can be partially or fully incorporated in other contexts. The library is available as open source at https://github.com/microsoft/tinytroupe.

[Arxiv](https://arxiv.org/abs/2507.09788)