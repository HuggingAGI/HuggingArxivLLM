# Recon-Act：基于网络侦察、工具生成与任务执行的自进化多智能体浏览器应用系统

发布时间：2025年09月25日

`Agent` `基础理论`

> Recon-Act: A Self-Evolving Multi-Agent Browser-Use System via Web Reconnaissance, Tool Generation, and Task Execution

# 摘要

> 近年来，多模态模型的显著进步为智能浏览器代理的发展奠定了基础。但在真实网页上以多轮、长周期轨迹执行任务时，当前代理仍面临动作序列混乱和试错过多的执行难题。本文提出Recon-Act——一个基于“侦察-行动”行为范式的自进化多智能体框架。该系统包含侦察团队与行动团队：前者负责比较分析与工具生成，后者则处理意图分解、工具编排及执行。侦察团队通过对比错误与成功轨迹推断补救措施，并将其抽象为统一的“广义工具”概念（可表现为提示或基于规则的代码），实时注册至工具库。行动团队借助这些针对性工具重新推演流程，构建起“数据-工具-行动-反馈”的闭环训练流程。依据本文提出的6级实施路线图，目前已进展至第3级（仅需有限人在环干预）。凭借侦察获得的广义工具，Recon-Act大幅提升了对未知网站的适应性和长周期任务的可解决性，并在极具挑战性的VisualWebArena数据集上刷新了当前最佳性能。

> Recent years, multimodal models have made remarkable strides and pave the way for intelligent browser use agents. However, when solving tasks on real world webpages in multi-turn, long-horizon trajectories, current agents still suffer from disordered action sequencing and excessive trial and error during execution. This paper introduces Recon-Act, a self-evolving multi-agent framework grounded in Reconnaissance-Action behavioral paradigm. The system comprises a Reconnaissance Team and an Action Team: the former conducts comparative analysis and tool generation, while the latter handles intent decomposition, tool orchestration, and execution. By contrasting the erroneous trajectories with successful ones, the Reconnaissance Team infers remedies, and abstracts them into a unified notion of generalized tools, either expressed as hints or as rule-based codes, and register to the tool archive in real time. The Action Team reinference the process empowered with these targeting tools, thus establishing a closed-loop training pipeline of data-tools-action-feedback. Following the 6 level implementation roadmap proposed in this work, we have currently reached Level 3 (with limited human-in-the-loop intervention). Leveraging generalized tools obtained through reconnaissance, Recon-Act substantially improves adaptability to unseen websites and solvability on long-horizon tasks, and achieves state-of-the-art performance on the challenging VisualWebArena dataset.

[Arxiv](https://arxiv.org/abs/2509.21072)