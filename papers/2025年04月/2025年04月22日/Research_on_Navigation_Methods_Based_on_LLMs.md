# 基于大型语言模型的导航方法研究

发布时间：2025年04月22日

`LLM应用` `室内导航` `机器人`

> Research on Navigation Methods Based on LLMs

# 摘要

> 近年来，室内导航领域借助大型语言模型（LLMs）实现了革命性突破。传统依赖预建地图或强化学习的导航方法存在泛化能力不足和动态环境适应性差等问题。相比之下，LLMs凭借其卓越的语义理解、推理能力和零样本泛化特性，为复杂室内导航任务提供了全新解决方案。我们提出了一种基于LLMs的导航框架，将LLMs定位为中央控制器，并充分利用其功能调用能力。我们的方法通过模块化分解传统导航功能，将其转化为可复用且配置灵活的LLM工具。同时，我们设计了系统化的可迁移提示模板和交互工作流，便于在不同实现中快速适配。在PyBullet仿真环境中进行的跨场景实验验证了我们方法的巨大潜力和有效性，尤其在通过动态工具组合实现语境感知导航方面表现突出。

> In recent years, the field of indoor navigation has witnessed groundbreaking advancements through the integration of Large Language Models (LLMs). Traditional navigation approaches relying on pre-built maps or reinforcement learning exhibit limitations such as poor generalization and limited adaptability to dynamic environments. In contrast, LLMs offer a novel paradigm for complex indoor navigation tasks by leveraging their exceptional semantic comprehension, reasoning capabilities, and zero-shot generalization properties. We propose an LLM-based navigation framework that leverages function calling capabilities, positioning the LLM as the central controller. Our methodology involves modular decomposition of conventional navigation functions into reusable LLM tools with expandable configurations. This is complemented by a systematically designed, transferable system prompt template and interaction workflow that can be easily adapted across different implementations. Experimental validation in PyBullet simulation environments across diverse scenarios demonstrates the substantial potential and effectiveness of our approach, particularly in achieving context-aware navigation through dynamic tool composition.

[Arxiv](https://arxiv.org/abs/2504.15600)