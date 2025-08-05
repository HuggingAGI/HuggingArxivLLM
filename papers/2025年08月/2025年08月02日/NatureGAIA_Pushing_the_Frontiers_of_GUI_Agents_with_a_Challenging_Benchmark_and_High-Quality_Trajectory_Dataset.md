# NatureGAIA: 挑战性基准测试与高质量轨迹数据集助力 GUI 代理技术突破

发布时间：2025年08月02日

`LLM应用` `人工智能` `图形用户界面（GUI）`

> NatureGAIA: Pushing the Frontiers of GUI Agents with a Challenging Benchmark and High-Quality Trajectory Dataset

# 摘要

> 大型语言模型（LLM）驱动的GUI代理发展迅猛，但现有评估基准的局限性严重阻碍了其潜力。为突破这一瓶颈，我们推出了\Benchmark——一个基于因果路径原则打造的全新评测体系。它将复杂任务拆解为可程序化验证的最小单元，确保评估过程严格、自动且可复现。同时，为弥补现有代理的能力短板，我们开发了\Agent——一种专为长周期任务优化的分层架构。通过该架构，我们创建了一个高质量、人工验证的交互数据集，首次完整记录了LLM多样且自我修正的交互模式。基于此数据集，我们对Qwen2.5-VL-7B模型进行了强化微调（RFT）。实验结果令人瞩目：\Benchmark对当前最先进模型构成巨大挑战，Claude-sonnet-4的加权路径成功率（WPSR）仅为34.6%。尽管RFT使小规模模型的GUI执行能力大幅提升（WPSR从3.3%跃升至10.8%），但在复杂场景下表现骤降。这揭示了小规模模型在处理感知、决策与执行一体化任务时的天然限制。本研究为社区提供了严格评测标准和优质数据集，旨在为未来GUI代理发展指明方向。

> The rapid advancement of Large Language Model (LLM)-driven Graphical User Interface (GUI) agents is significantly hampered by the profound limitations of existing evaluation benchmarks in terms of accuracy, reproducibility, and scalability. To address this critical gap, we introduce \Benchmark, a novel benchmark engineered on the principle of Causal Pathways. This design paradigm structures complex tasks into a series of programmatically verifiable atomic steps, ensuring a rigorous, fully automated, and reproducible standard for assessment. Concurrently, to mitigate the inherent capability deficits of agents, we developed \Agent, a hierarchical agent architecture specifically optimized for long-horizon tasks. We leveraged this agent to generate a high-quality, human-verified trajectory dataset that uniquely captures diverse and even self-correcting interaction patterns of LLMs. We then utilized this dataset to perform Reinforcement Fine-Tuning (RFT) on the Qwen2.5-VL-7B model. Our experiments reveal that \Benchmark~presents a formidable challenge to current state-of-the-art LLMs; even the top-performing Claude-sonnet-4 achieved a Weighted Pathway Success Rate (WPSR) of only 34.6\%. Moreover, while RFT substantially improved the smaller model's GUI execution capabilities (WPSR increased from 3.3\% to 10.8\%), its performance degraded sharply when handling complex scenarios. This outcome highlights the inherent capability ceiling of smaller models when faced with comprehensive tasks that integrate perception, decision-making, and execution. This research contributes a rigorous evaluation standard and a high-quality dataset to the community, aiming to guide the future development of GUI agents.

[Arxiv](https://arxiv.org/abs/2508.01330)