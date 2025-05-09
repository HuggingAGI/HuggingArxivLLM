# EcoAgent：高效能边云协同多智能体框架，专为移动自动化而设计

发布时间：2025年05月08日

`Agent` `移动自动化` `边缘计算`

> EcoAgent: An Efficient Edge-Cloud Collaborative Multi-Agent Framework for Mobile Automation

# 摘要

> 基于（多模态）大型语言模型（(M)LLMs）的云端移动智能体虽具备强大的推理能力，但存在高延迟和高成本的局限。尽管经过微调的(M)SLMs能够实现边缘部署，却往往丧失通用能力，难以应对复杂任务。为解决这一难题，我们提出了EcoAgent——一个专为移动自动化设计的边缘-云协作多智能体框架。EcoAgent由云端规划智能体与两个边缘端智能体组成，采用闭环协作机制：执行智能体负责具体动作的执行，观测智能体则用于验证任务结果。观测智能体配备预理解模块，可将屏幕图像压缩为简洁文本，从而减少令牌使用量。若任务执行失败，规划智能体会调取屏幕历史记录并通过反思模块重新规划。在AndroidWorld上的实验表明，EcoAgent不仅保持了高任务成功率，还大幅降低了MLLM令牌的消耗，为实现高效、实用的移动自动化提供了有力支持。

> Cloud-based mobile agents powered by (multimodal) large language models ((M)LLMs) offer strong reasoning abilities but suffer from high latency and cost. While fine-tuned (M)SLMs enable edge deployment, they often lose general capabilities and struggle with complex tasks. To address this, we propose EcoAgent, an Edge-Cloud cOllaborative multi-agent framework for mobile automation. EcoAgent features a closed-loop collaboration among a cloud-based Planning Agent and two edge-based agents: the Execution Agent for action execution and the Observation Agent for verifying outcomes. The Observation Agent uses a Pre-Understanding Module to compress screen images into concise text, reducing token usage. In case of failure, the Planning Agent retrieves screen history and replans via a Reflection Module. Experiments on AndroidWorld show that EcoAgent maintains high task success rates while significantly reducing MLLM token consumption, enabling efficient and practical mobile automation.

[Arxiv](https://arxiv.org/abs/2505.05440)