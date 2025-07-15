# Hide-and-Shill：用于去中心化多智能体系统Symphony中的市场操纵检测强化学习框架

发布时间：2025年07月12日

`Agent` `金融科技` `金融监管`

> Hide-and-Shill: A Reinforcement Learning Framework for Market Manipulation Detection in Symphony-a Decentralized Multi-Agent System

# 摘要

> 去中心化金融（DeFi）开启了无需许可的金融创新时代，但也带来了前所未有的市场操纵行为。由于缺乏中心化监管，恶意行为者在多个平台之间协调洗售活动并实施拉高出货计划。我们提出了一种多智能体强化学习（MARL）框架，用于去中心化操纵检测，将操纵者与检测者之间的互动建模为动态对抗博弈。该框架通过延迟的代币价格反应作为财务指标，识别可疑模式。我们的方法在三个创新方面实现了突破：（1）组相对策略优化（GRPO），提升稀疏奖励和部分可观测环境下的学习稳定性；（2）基于理性预期和信息不对称的理论启发奖励函数，区分价格发现与操纵噪音；（3）整合基于LLM的语义特征、社交图信号和链上市场数据的多模态智能体管道，支持有据可依的决策。该框架集成在Symphony系统中，这是一个去中心化的多智能体架构，通过分布式日志实现点对点智能体执行和信任感知学习，支持链上可验证评估。Symphony促进了战略行为者之间的对抗共同进化，在无需中心化预言机的情况下维持强大的操纵检测能力，实现实时全球DeFi生态系统的监控。通过10万次真实世界讨论场景的训练，并在对抗性模拟中验证，Hide-and-Shill在检测准确性和因果归因方面达到顶尖性能。这项研究将多智能体系统与金融监管相结合，推动了去中心化市场情报的新范式。所有资源均可在Hide-and-Shill GitHub仓库中获取，以促进开放研究和可重复性。

> Decentralized finance (DeFi) has introduced a new era of permissionless financial innovation but also led to unprecedented market manipulation. Without centralized oversight, malicious actors coordinate shilling campaigns and pump-and-dump schemes across various platforms. We propose a Multi-Agent Reinforcement Learning (MARL) framework for decentralized manipulation detection, modeling the interaction between manipulators and detectors as a dynamic adversarial game. This framework identifies suspicious patterns using delayed token price reactions as financial indicators.Our method introduces three innovations: (1) Group Relative Policy Optimization (GRPO) to enhance learning stability in sparse-reward and partially observable settings; (2) a theory-based reward function inspired by rational expectations and information asymmetry, differentiating price discovery from manipulation noise; and (3) a multi-modal agent pipeline that integrates LLM-based semantic features, social graph signals, and on-chain market data for informed decision-making.The framework is integrated within the Symphony system, a decentralized multi-agent architecture enabling peer-to-peer agent execution and trust-aware learning through distributed logs, supporting chain-verifiable evaluation. Symphony promotes adversarial co-evolution among strategic actors and maintains robust manipulation detection without centralized oracles, enabling real-time surveillance across global DeFi ecosystems.Trained on 100,000 real-world discourse episodes and validated in adversarial simulations, Hide-and-Shill achieves top performance in detection accuracy and causal attribution. This work bridges multi-agent systems with financial surveillance, advancing a new paradigm for decentralized market intelligence. All resources are available at the Hide-and-Shill GitHub repository to promote open research and reproducibility.

[Arxiv](https://arxiv.org/abs/2507.09179)