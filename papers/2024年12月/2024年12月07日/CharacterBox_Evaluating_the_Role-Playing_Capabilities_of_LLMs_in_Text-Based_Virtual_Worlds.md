# CharacterBox：评估 LLMs 在基于文本的虚拟世界里的角色扮演能力

发布时间：2024年12月07日

`LLM应用` `人工智能`

> CharacterBox: Evaluating the Role-Playing Capabilities of LLMs in Text-Based Virtual Worlds

# 摘要

> 角色扮演是大型语言模型（LLMs）的关键能力，能用于诸多实际应用，像智能非玩家角色、数字双胞胎和情感伴侣等。但由于角色扮演存在复杂动态，比如在整个故事线中维持角色的忠诚度，以及在没有明确真相的情况下驾驭开放式叙述，评估 LLMs 的这一能力颇具挑战。当前的评估方法多聚焦于问答或对话快照，难以充分捕捉真实角色扮演所需的细微角色特征和行为。本文提出了 CharacterBox，这是一个用于生成情境细粒度角色行为轨迹的模拟沙盒。这些行为轨迹能更全面深入地评估角色扮演能力。CharacterBox 包含两个主要组件：角色代理和叙述者代理。基于心理和行为科学的角色代理展现出类人的行为，叙述者代理则协调角色代理与环境变化间的相互作用。此外，我们引入了两种基于轨迹的方法，借助 CharacterBox 提升 LLMs 的性能。为降低成本并方便公共社区使用 CharacterBox，我们对两个较小的模型 CharacterNR 和 CharacterRM 进行了微调，以替代 GPT API 调用，并展示了它们相较于先进 GPT API 的竞争性能。

> Role-playing is a crucial capability of Large Language Models (LLMs), enabling a wide range of practical applications, including intelligent non-player characters, digital twins, and emotional companions. Evaluating this capability in LLMs is challenging due to the complex dynamics involved in role-playing, such as maintaining character fidelity throughout a storyline and navigating open-ended narratives without a definitive ground truth. Current evaluation methods, which primarily focus on question-answering or conversational snapshots, fall short of adequately capturing the nuanced character traits and behaviors essential for authentic role-playing. In this paper, we propose CharacterBox, which is a simulation sandbox designed to generate situational fine-grained character behavior trajectories. These behavior trajectories enable a more comprehensive and in-depth evaluation of role-playing capabilities. CharacterBox consists of two main components: the character agent and the narrator agent. The character agent, grounded in psychological and behavioral science, exhibits human-like behaviors, while the narrator agent coordinates interactions between character agents and environmental changes. Additionally, we introduce two trajectory-based methods that leverage CharacterBox to enhance LLM performance. To reduce costs and facilitate the adoption of CharacterBox by public communities, we fine-tune two smaller models, CharacterNR and CharacterRM, as substitutes for GPT API calls, and demonstrate their competitive performance compared to advanced GPT APIs.

[Arxiv](https://arxiv.org/abs/2412.05631)