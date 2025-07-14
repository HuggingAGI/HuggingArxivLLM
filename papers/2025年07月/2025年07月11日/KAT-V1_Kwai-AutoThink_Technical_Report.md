# KAT-V1：Kwai-AutoThink 技术报告

发布时间：2025年07月11日

`LLM应用` `人工智能` `软件开发`

> KAT-V1: Kwai-AutoThink Technical Report

# 摘要

> 我们推出了Kwaipilot-AutoThink (KAT)，一个开源的400亿参数大型语言模型，专为解决推理密集型任务中的过度思考问题而设计。该模型采用了一种创新的自动推理训练范式，可根据任务复杂性动态切换推理与非推理模式。具体而言，我们首先通过新颖的标签流水线和多智能体合成策略构建了双模式数据集；接着，引入了多令牌预测（MTP）增强的知识蒸馏技术，实现了高效且细致的推理迁移，同时大幅降低了预训练成本。此外，我们还采用了冷启动初始化策略，利用多数投票信号和意图感知提示引入模式选择先验。最后，我们开发了Step-SRPO强化学习算法，将中间监督融入GRPO框架，为推理模式选择和响应准确性提供结构化指导。在多个基准测试中的实验结果表明，KAT在各种推理密集型任务中表现优异，不仅匹敌甚至超越了当前最先进的模型，如DeepSeek-R1-0528和Qwen3-235B-A22B，同时将令牌使用量减少了约30%。KAT不仅在学术领域表现出色，还在Kwaipilot（快手的内部编码助手）中成功部署，通过高精度、高效率和可控的推理行为显著提升了实际开发工作流程。此外，我们正在积极训练一个包含400亿激活参数的2000亿参数专家混合模型（MoE），早期结果已显示出性能和效率的显著提升，进一步验证了AutoThink范式的可扩展性。

> We present Kwaipilot-AutoThink (KAT), an open-source 40B large language model developed to address the overthinking problem in reasoning-intensive tasks, where an automatic thinking training paradigm is proposed to dynamically switch between reasoning and non-reasoning modes based on task complexity. Specifically, first, we construct the dual-regime dataset based on a novel tagging pipeline and a multi-agent synthesis strategy, and then we apply Multi-Token Prediction (MTP)-enhanced knowledge distillation, enabling efficient and fine-grained reasoning transfer with minimal pretraining cost. Besides, we implement a cold-start initialization strategy that introduces mode-selection priors using majority-vote signals and intent-aware prompting. Finally, we propose Step-SRPO, a reinforcement learning algorithm that incorporates intermediate supervision into the GRPO framework, offering structured guidance over both reasoning-mode selection and response accuracy. Extensive experiments across multiple benchmarks demonstrate that KAT consistently matches or even outperforms current state-of-the-art models, including DeepSeek-R1-0528 and Qwen3-235B-A22B, across a wide range of reasoning-intensive tasks while reducing token usage by up to approximately 30\%. Beyond academic evaluation, KAT has been successfully deployed in Kwaipilot (i.e., Kuaishou's internal coding assistant), and improves real-world development workflows with high accuracy, efficiency, and controllable reasoning behaviors. Moreover, we are actively training a 200B Mixture-of-Experts (MoE) with 40B activation parameters, where the early-stage results already demonstrate promising improvements in performance and efficiency, further showing the scalability of the AutoThink paradigm.

[Arxiv](https://arxiv.org/abs/2507.08297)