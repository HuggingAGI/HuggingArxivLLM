# Agent-Environment Alignment via Automated Interface Generation
智能体与环境的对齐通过自动生成接口达成

发布时间：2025年05月27日

`Agent

这篇论文讨论了大型语言模型（LLM）代理在交互式决策任务中的应用，并提出了一个名为ALIGN的框架，用于解决智能体与环境之间的对齐问题。研究集中在智能体与环境的交互接口上，强调通过增强接口来提升智能体的性能。因此，这篇论文属于Agent分类。` `人工智能` `机器人学`

> Agent-Environment Alignment via Automated Interface Generation

# 摘要

> 大型语言模型 (LLM) 代理在交互式决策任务中展现了令人印象深刻的推理能力。这些代理通过预定义的动作空间和交互规则等中间接口与环境进行交互，这些接口介导了感知与行动。然而，代理对其发出动作对环境影响的内部预期与环境实际状态转换之间经常出现不匹配，这一现象被称为	extbf{智能体-环境对齐问题}。

尽管先前的工作在提升代理策略和环境设计方面投入了大量努力，但接口的关键作用仍然未得到充分探索。在本研究中，我们实证表明智能体-环境对齐问题对代理性能构成了重大瓶颈。为解决这一问题，我们提出了	extbf{ALIGN}，一个通过丰富接口来缓解对齐问题的	extbf{自动对齐接口生成框架}。具体而言，ALIGN生成的接口增强了环境的静态信息以及返回给代理的逐步观察结果。作为轻量级包装器实现，该接口无需修改代理逻辑或环境代码即可实现对齐。

在包括具身任务、网络导航和工具使用在内的多个领域进行的实验均显示出一致的性能提升，在ALFWorld中成功率达到45.67\%的显著提升。同时，ALIGN生成的接口可以跨不同代理架构和LLM基础模型进行泛化，无需重新生成接口。代码和实验结果可在https://github.com/THUNLP-MT/ALIGN获取。

> Large language model (LLM) agents have shown impressive reasoning capabilities in interactive decision-making tasks. These agents interact with environment through intermediate interfaces, such as predefined action spaces and interaction rules, which mediate the perception and action. However, mismatches often happen between the internal expectations of the agent regarding the influence of its issued actions and the actual state transitions in the environment, a phenomenon referred to as \textbf{agent-environment misalignment}. While prior work has invested substantially in improving agent strategies and environment design, the critical role of the interface still remains underexplored. In this work, we empirically demonstrate that agent-environment misalignment poses a significant bottleneck to agent performance. To mitigate this issue, we propose \textbf{ALIGN}, an \underline{A}uto-A\underline{l}igned \underline{I}nterface \underline{G}e\underline{n}eration framework that alleviates the misalignment by enriching the interface. Specifically, the ALIGN-generated interface enhances both the static information of the environment and the step-wise observations returned to the agent. Implemented as a lightweight wrapper, this interface achieves the alignment without modifying either the agent logic or the environment code. Experiments across multiple domains including embodied tasks, web navigation and tool-use, show consistent performance improvements, with up to a 45.67\% success rate improvement observed in ALFWorld. Meanwhile, ALIGN-generated interface can generalize across different agent architectures and LLM backbones without interface regeneration. Code and experimental results are available at https://github.com/THUNLP-MT/ALIGN.

[Arxiv](https://arxiv.org/abs/2505.21055)