# PiMoE：令牌级路由整合高精度计算与推理

发布时间：2025年09月17日

`LLM应用` `工业与制造`

> PiMoE: Token-Level Routing for Integrating High-Precision Computation and Reasoning

# 摘要

> 复杂系统通常依赖高精度数值计算来支持决策，但当前大型语言模型（LLMs）仍无法将此类计算作为一种内在且可解释的能力融入现有架构。主流多智能体方法虽能借助外部专家，但不可避免地会引入通信开销，还存在多模态涌现能力低效、可扩展性有限的问题。为此，我们提出PiMoE（物理隔离的专家混合体）——一种整合计算与推理的训练推理架构。PiMoE摒弃工具调用的工作流范式，而是在分别训练专家、文本到计算模块及路由器后，将计算能力内源性地融入神经网络。推理时，路由器在令牌级别引导计算与推理，从而实现单一思维链内的迭代交替。我们在两项推理-计算任务上对PiMoE进行了评估，对比了LLM微调方法与多智能体系统方法。结果显示，PiMoE架构不仅比直接微调LLMs的准确率更高，而且与主流多智能体方法相比，在响应延迟、令牌使用量及GPU能耗方面均有显著改善。PiMoE为下一代科学或工业智能系统提供了高效、可解释且可扩展的范式。

> Complex systems typically rely on high-precision numerical computation to support decisions, but current large language models (LLMs) cannot yet incorporate such computations as an intrinsic and interpretable capability with existing architectures. Mainstream multi-agent approaches can leverage external experts, but inevitably introduce communication overhead and suffer from inefficient multimodal emergent capability and limited scalability. To this end, we propose PiMoE (Physically-isolated Mixture of Experts), a training and inference architecture for integrating computation and reasoning. Instead of the workflow paradigm of tool invocation, PiMoE endogenously integrates computational capabilities into neural networks after separately training experts, a text-to-computation module, and a router. At inference, the router directs computation and reasoning at the token level, thereby enabling iterative alternation within a single chain of thought. We evaluate PiMoE on two reasoning-computation tasks against LLM finetuning and the multi-agent system approaches. Results show that the PiMoE architecture achieves not only higher accuracy than directly finetuning LLMs but also significant improvements in response latency, token usage, and GPU energy consumption compared with mainstream multi-agent approaches. PiMoE offers an efficient, interpretable, and scalable paradigm for next-generation scientific or industrial intelligent systems.

[Arxiv](https://arxiv.org/abs/2509.18169)