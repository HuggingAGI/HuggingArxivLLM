# AGFT：自适应GPU频率调谐器，实时LLM推理优化

发布时间：2025年08月03日

`LLM应用

理由：这篇论文讨论了AGFT框架，它使用在线强化学习来优化GPU频率，从而提高LLM推理任务的能源效率。虽然它使用了强化学习，但主要目标是优化LLM的能源使用，属于应用层面的优化。` `云计算` `能源管理`

> AGFT: An Adaptive GPU Frequency Tuner for Real-Time LLM Inference Optimization

# 摘要

> 交互式大型语言模型的迅猛发展给云GPU带来了前所未有的低延迟挑战，迫使GPU进入高功耗模式，能源成本也因此激增。实时推理任务的动态波动特性为节能提供了宝贵机会。然而，传统静态或基于规则的电源管理策略难以在不牺牲性能的情况下充分利用这些机会。为解决这一难题，我们提出AGFT（自适应GPU频率调节器），一个基于在线强化学习的框架，能够自主学习最优频率调节策略。通过实时监控请求负载和延迟等特征，AGFT采用精细频率控制实现精准调节，并通过智能动作空间剪枝确保稳定高效的决策。这为能源管理提供了一个强大而自动化的解决方案。我们在模拟真实波动推理请求的环境中对AGFT进行了全面评估。实验结果表明，AGFT成功将GPU能耗降低了44.3%，同时仅引入了不到10%的性能延迟开销。这一成果实现了高达40.3%的全面能效-延迟乘积（EDP）优化，充分证明了我们的框架能够在不降低服务质量的前提下，显著提升现有LLM推理集群的能效和经济效益。

> The explosive growth of interactive Large Language Models (LLMs) has placed unprecedented demands for low latency on cloud GPUs, forcing them into high-power modes and causing escalating energy costs. Real-time inference workloads exhibit significant dynamic volatility, presenting substantial energy-saving opportunities. However, traditional static or rule-based power management strategies struggle to exploit these opportunities without compromising peak performance. To address this challenge, we propose AGFT (An Adaptive GPU Frequency Tuner), a framework that employs online reinforcement learning to autonomously learn an optimal frequency tuning policy. By monitoring real-time features like request load and latency, AGFT utilizes fine-grained frequency control for precise adjustments and intelligent action space pruning for stable, efficient decision-making. This creates a robust, automated energy management solution. We comprehensively evaluated AGFT in an environment simulating realistic, fluctuating inference requests. The experimental results demonstrate that AGFT successfully saves 44.3% of GPU energy consumption while introducing a minimal performance latency overhead of under 10%. This achievement translates into a comprehensive Energy-Delay Product (EDP) optimization of up to 40.3%, clearly showing that our framework can significantly enhance the energy efficiency and economic benefits of existing LLM inference clusters without compromising service quality.

[Arxiv](https://arxiv.org/abs/2508.01744)