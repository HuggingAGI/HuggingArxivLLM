# 推进移动 GUI 代理：以验证器驱动的方法实现实用部署

发布时间：2025年03月20日

`Agent` `移动应用` `任务自动化`

> Advancing Mobile GUI Agents: A Verifier-Driven Approach to Practical Deployment

# 摘要

> 我们提出了一种名为V-Droid的移动GUI任务自动化代理。与以往使用大型语言模型（LLMs）作为生成器直接生成动作的移动代理不同，V-Droid采用了一种全新的方法：它利用LLMs作为验证器，在做出最终决策之前对候选动作进行评估。为了实现这一创新性的方法，我们构建了一个基于验证器的移动代理框架。该框架包含三个关键组成部分：离散化的动作空间构建结合仅限预填充的工作流，以加速验证过程；配对式进度偏好训练，以显著提升验证器的决策能力；以及可扩展的人机联合标注方案，以高效地收集大规模所需的训练数据。V-Droid在多个公开的移动任务自动化基准测试中树立了新的成功率标杆：在AndroidWorld基准测试中达到59.5%，在AndroidLab中达到38.3%，在MobileAgentBench中达到49%。这些成绩分别比现有代理高出9.5%、2.1%和9%。此外，V-Droid实现了令人印象深刻的低延迟，每步仅需0.7秒，使其成为首个能够实现近实时、有效决策能力的移动代理。

> We propose V-Droid, a mobile GUI task automation agent. Unlike previous mobile agents that utilize Large Language Models (LLMs) as generators to directly generate actions at each step, V-Droid employs LLMs as verifiers to evaluate candidate actions before making final decisions. To realize this novel paradigm, we introduce a comprehensive framework for constructing verifier-driven mobile agents: the discretized action space construction coupled with the prefilling-only workflow to accelerate the verification process, the pair-wise progress preference training to significantly enhance the verifier's decision-making capabilities, and the scalable human-agent joint annotation scheme to efficiently collect the necessary data at scale. V-Droid sets a new state-of-the-art task success rate across several public mobile task automation benchmarks: 59.5% on AndroidWorld, 38.3% on AndroidLab, and 49% on MobileAgentBench, surpassing existing agents by 9.5%, 2.1%, and 9%, respectively. Furthermore, V-Droid achieves an impressively low latency of 0.7 seconds per step, making it the first mobile agent capable of delivering near-real-time, effective decision-making capabilities.

[Arxiv](https://arxiv.org/abs/2503.15937)