# 多智能体 LLM Actor-Critic 框架助力社交导航

发布时间：2025年03月12日

`LLM应用` `机器人学`

> Multi-Agent LLM Actor-Critic Framework for Social Robot Navigation

# 摘要

> 机器人学与大型语言模型（LLMs）的最新进展激发了人们对人机协作及具身智能的浓厚兴趣。要在人类环境中实现更广泛的机器人部署，社会感知机器人导航（SAN）已成为关键研究领域。尽管结合人机交互（HRI）与路径规划的深度强化学习方法在基准测试中表现优异，但它们往往难以适应新场景和新环境。LLMs为通过常识推理实现零样本导航提供了有前景的途径。然而，现有LLM框架多依赖集中式决策，缺乏 robust 验证机制，且在将宏观动作转化为精确低级控制信号时存在不一致。为解决这些问题，我们提出了SAMALM——一个用于多机器人社交导航的去中心化多智能体LLM演员-评论家框架。在此框架中，一组反映不同机器人个性或配置的并行LLM演员直接生成控制信号。这些动作通过全局评论家（评估组级行为）和个体评论家（评估每个机器人的上下文）进行两级验证。基于熵的评分融合机制进一步增强了自我验证与重新查询，显著提升了鲁棒性与协调性。实验结果表明，SAMALM在多机器人场景中实现了局部自主性与全局监督的完美平衡，不仅行为符合社会规范，更展现了强大的适应能力。更多关于这项工作的细节与视频，请访问：https://sites.google.com/view/SAMALM。

> Recent advances in robotics and large language models (LLMs) have sparked growing interest in human-robot collaboration and embodied intelligence. To enable the broader deployment of robots in human-populated environments, socially-aware robot navigation (SAN) has become a key research area. While deep reinforcement learning approaches that integrate human-robot interaction (HRI) with path planning have demonstrated strong benchmark performance, they often struggle to adapt to new scenarios and environments. LLMs offer a promising avenue for zero-shot navigation through commonsense inference. However, most existing LLM-based frameworks rely on centralized decision-making, lack robust verification mechanisms, and face inconsistencies in translating macro-actions into precise low-level control signals. To address these challenges, we propose SAMALM, a decentralized multi-agent LLM actor-critic framework for multi-robot social navigation. In this framework, a set of parallel LLM actors, each reflecting distinct robot personalities or configurations, directly generate control signals. These actions undergo a two-tier verification process via a global critic that evaluates group-level behaviors and individual critics that assess each robot's context. An entropy-based score fusion mechanism further enhances self-verification and re-query, improving both robustness and coordination. Experimental results confirm that SAMALM effectively balances local autonomy with global oversight, yielding socially compliant behaviors and strong adaptability across diverse multi-robot scenarios. More details and videos about this work are available at: https://sites.google.com/view/SAMALM.

[Arxiv](https://arxiv.org/abs/2503.09758)