# AppCopilot：迈向通用、精准、长时程且高效的移动智能体

发布时间：2025年09月02日

`Agent` `基础理论`

> AppCopilot: Toward General, Accurate, Long-Horizon, and Efficient Mobile Agent

# 摘要

> 随着大型语言模型和多模态基础模型的飞速发展，移动智能体领域呈现爆发式增长，但核心挑战尚未形成统一解决方案。本文明确了移动智能体要实现实用且可扩展的影响力必须攻克的四大核心难题：(1) 跨任务、模态、应用及设备的泛化能力；(2) 准确性，尤其是精准的屏幕交互与点击定位；(3) 长程任务能力，以支持持续的多步骤目标；(4) 效率，特别是在资源受限设备上的高性能运行时。我们提出AppCopilot——一款多模态、多智能体的通用设备端助手，能够跨应用运行，构建了从数据到部署的全栈闭环系统。AppCopilot通过端到端自主流程（涵盖数据收集、训练、部署、高质量高效推理及移动应用开发）实现了这一愿景。在模型层，它集成了具备强大中英文支持的多模态基础模型；在推理与控制层，融合了思维链推理、分层任务规划分解及多智能体协作机制；在执行层，支持用户个性化与体验适配、语音交互、函数调用、跨应用跨设备编排及全面的移动应用兼容。系统设计采用基于性能分析的优化策略，在异构硬件上实现了延迟、内存与能耗的全方位优化。实验结果显示，AppCopilot在四大维度均实现显著提升：泛化能力更强、屏幕操作精度更高、长程任务完成更可靠，且运行时更快、资源效率更优。

> With the raid evolution of large language models and multimodal foundation models, the mobile-agent landscape has proliferated without converging on the fundamental challenges. This paper identifies four core problems that must be solved for mobile agents to deliver practical, scalable impact: (1) generalization across tasks, modalities, apps, and devices; (2) accuracy, specifically precise on-screen interaction and click targeting; (3) long-horizon capability for sustained, multi-step goals; and (4) efficiency, specifically high-performance runtime on resource-constrained devices. We present AppCopilot, a multimodal, multi-agent, general-purpose on-device assistant that operates across applications and constitutes a full-stack, closed-loop system from data to deployment. AppCopilot operationalizes this position through an end-to-end autonomous pipeline spanning data collection, training, deployment, high-quality and efficient inference, and mobile application development. At the model layer, it integrates multimodal foundation models with robust Chinese-English support. At the reasoning and control layer, it combines chain-of-thought reasoning, hierarchical task planning and decomposition, and multi-agent collaboration. At the execution layer, it enables user personalization and experiential adaptation, voice interaction, function calling, cross-app and cross-device orchestration, and comprehensive mobile app support. The system design incorporates profiling-driven optimization for latency, memory, and energy across heterogeneous hardware. Empirically, AppCopilot achieves significant improvements along all four dimensions: stronger generalization, higher-precision on-screen actions, more reliable long-horizon task completion, and faster, more resource-efficient runtime.

[Arxiv](https://arxiv.org/abs/2509.02444)