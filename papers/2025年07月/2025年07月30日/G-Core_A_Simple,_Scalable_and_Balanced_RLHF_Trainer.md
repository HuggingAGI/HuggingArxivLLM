# G-Core：简洁、可扩展且均衡的RLHF训练框架

发布时间：2025年07月30日

`LLM应用` `社交媒体`

> G-Core: A Simple, Scalable and Balanced RLHF Trainer

# 摘要

> 从人类反馈中强化学习（RLHF）已成为训练大型语言模型（LLMs）和扩散模型的流行范式。然而，现有的RLHF训练系统在扩展到多模态和扩散工作流以及适应动态负载时仍面临挑战，尤其是在复杂RLHF管道中，当前方法可能在控制器扩展性、资源放置和编排效率方面遇到限制，特别是在涉及动态采样或生成奖励建模的场景中。为此，我们提出了	extbf{G-Core}，一个简单、可扩展且平衡的RLHF训练框架。G-Core通过并行控制器编程模型，实现了复杂RLHF工作流的灵活高效编排，避免了单个集中式控制器的瓶颈。此外，我们提出了一种动态资源分配方案，能够自适应地划分资源并调度负载，即使在高度变化的训练条件下，也能显著减少硬件空闲时间并提高利用率。G-Core成功训练了支持微信产品功能的模型，服务于大规模用户群体，证明了其在现实场景中的有效性和鲁棒性。我们的结果显示，G-Core推进了RLHF训练的前沿技术，为未来大规模、与人类对齐的模型的研究和部署奠定了坚实的基础。

> Reinforcement Learning from Human Feedback (RLHF) has become an increasingly popular paradigm for training large language models (LLMs) and diffusion models. While existing RLHF training systems have enabled significant progress, they often face challenges in scaling to multi-modal and diffusion workflows and adapting to dynamic workloads. In particular, current approaches may encounter limitations in controller scalability, flexible resource placement, and efficient orchestration when handling complex RLHF pipelines, especially in scenarios involving dynamic sampling or generative reward modeling. In this paper, we present \textbf{G-Core}, a simple, scalable, and balanced RLHF training framework designed to address these challenges. G-Core introduces a parallel controller programming model, enabling flexible and efficient orchestration of complex RLHF workflows without the bottlenecks of a single centralized controller. Furthermore, we propose a dynamic placement schema that adaptively partitions resources and schedules workloads, significantly reducing hardware idle time and improving utilization, even under highly variable training conditions. G-Core has successfully trained models that support WeChat product features serving a large-scale user base, demonstrating its effectiveness and robustness in real-world scenarios. Our results show that G-Core advances the state of the art in RLHF training, providing a solid foundation for future research and deployment of large-scale, human-aligned models.

[Arxiv](https://arxiv.org/abs/2507.22789)