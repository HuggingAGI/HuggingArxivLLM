# AURA：智能体技能提升的强化抽象方法

发布时间：2025年06月03日

`LLM应用` `机器人` `自动化`

> AURA: Agentic Upskilling via Reinforced Abstractions

# 摘要

> 我们研究了通过多阶段强化学习将高层次任务提示转换为敏捷机器人可部署控制策略所涉及的组合爆炸问题。我们介绍了AURA（通过强化抽象实现智能体技能提升），这是一个基于模式的课程强化学习框架，利用大型语言模型（LLMs）作为多阶段课程的自主设计师。AURA将用户提示转换为YAML工作流，这些工作流编码完整的奖励函数、领域随机化策略和训练配置。所有文件在消耗任何GPU时间之前都会经过模式的静态验证，确保可靠且高效的执行，无需人工干预。一个检索增强的反馈循环使专门的LLM代理能够根据存储在向量数据库中的先前训练结果设计、执行和优化阶段课程，支持随时间的持续改进。消融研究表明检索对课程质量和收敛稳定性的重要性。定量实验表明，AURA在GPU加速的训练框架上始终优于LLM引导的基线。在定性测试中，AURA成功地从用户提示直接训练端到端策略，并在定制的人形机器人上零样本部署这些策略，跨越多种环境。通过抽象课程设计的复杂性，AURA实现了可扩展且适应性强的策略学习流水线，这种流水线如果手动构建将极其复杂。

> We study the combinatorial explosion involved in translating high-level task prompts into deployable control policies for agile robots through multi-stage reinforcement learning. We introduce AURA (Agentic Upskilling via Reinforced Abstractions), a schema-centric curriculum RL framework that leverages Large Language Models (LLMs) as autonomous designers of multi-stage curricula. AURA transforms user prompts into YAML workflows that encode full reward functions, domain randomization strategies, and training configurations. All files are statically validated against a schema before any GPU time is consumed, ensuring reliable and efficient execution without human intervention. A retrieval-augmented feedback loop allows specialized LLM agents to design, execute, and refine staged curricula based on prior training results stored in a vector database, supporting continual improvement over time. Ablation studies highlight the importance of retrieval for curriculum quality and convergence stability. Quantitative experiments show that AURA consistently outperforms LLM-guided baselines on GPU-accelerated training frameworks. In qualitative tests, AURA successfully trains end-to-end policies directly from user prompts and deploys them zero-shot on a custom humanoid robot across a range of environments. By abstracting away the complexity of curriculum design, AURA enables scalable and adaptive policy learning pipelines that would be prohibitively complex to construct by hand.

[Arxiv](https://arxiv.org/abs/2506.02507)