# WebSailor-V2：通过合成数据与可扩展强化学习弥合与专有智能体的鸿沟

发布时间：2025年09月16日

`Agent` `基础理论`

> WebSailor-V2: Bridging the Chasm to Proprietary Agents via Synthetic Data and Scalable Reinforcement Learning

# 摘要

> 突破人类认知局限是大型语言模型（LLM）训练的关键前沿。像DeepResearch这样的专有智能体系统已在BrowseComp等极其复杂的信息检索基准测试中展现出超人能力，这一成就此前难以企及。我们认为，它们的成功源于开源模型所缺乏的一种复杂推理模式——在海量信息空间中导航时，能够系统性地降低极端不确定性。基于这一洞见，我们提出WebSailor——一种旨在赋予模型这一关键能力的完整后训练方法。我们的方法包括通过结构化采样与信息模糊生成新颖高不确定性任务、RFT冷启动，以及高效的智能体强化学习训练算法“复制采样策略优化（DUPO）”。借助这一集成流程，WebSailor在复杂信息检索任务中显著超越所有开源智能体，性能媲美专有智能体，成功缩小了能力差距。

> Transcending human cognitive limitations represents a critical frontier in LLM training. Proprietary agentic systems like DeepResearch have demonstrated superhuman capabilities on extremely complex information-seeking benchmarks such as BrowseComp, a feat previously unattainable. We posit that their success hinges on a sophisticated reasoning pattern absent in open-source models: the ability to systematically reduce extreme uncertainty when navigating vast information landscapes. Based on this insight, we introduce WebSailor, a complete post-training methodology designed to instill this crucial capability. Our approach involves generating novel, high-uncertainty tasks through structured sampling and information obfuscation, RFT cold start, and an efficient agentic RL training algorithm, Duplicating Sampling Policy Optimization (DUPO). With this integrated pipeline, WebSailor significantly outperforms all open-source agents in complex information-seeking tasks, matching proprietary agents' performance and closing the capability gap.

[Arxiv](https://arxiv.org/abs/2509.13305)