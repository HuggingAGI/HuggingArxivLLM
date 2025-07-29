# PennyCoder：专为PennyLane量子代码生成设计的高效领域特定大语言模型

发布时间：2025年07月25日

`LLM应用` `量子计算` `人工智能`

> PennyCoder: Efficient Domain-Specific LLMs for PennyLane-Based Quantum Code Generation

# 摘要

> 随着对强大量子编程框架需求的不断增长，我们发现现有基于大型语言模型（LLM）的量子代码助手存在一个关键局限性：它们严重依赖远程API，由此带来了隐私、延迟和高昂使用成本等挑战。针对这一问题，我们提出了PennyCoder——一个专为本地和嵌入式部署设计的新型轻量级量子代码生成框架，旨在实现无需外部API依赖的设备端量子编程辅助。PennyCoder基于LLaMA 3.1-8B模型，通过参数高效的低秩适配（LoRA）技术优化，并结合针对PennyLane量子编程语法和计算逻辑的领域特定指令微调，特别适用于量子机器学习和量子强化学习等任务。与此前专注于云端量子代码生成的研究不同，我们的方法着重于实现设备原生操作，同时保持高水平的模型效能。我们对PennyCoder进行了全面的量子编程数据集评估，结果显示，我们的微调模型达到了44.3%的准确率（相较于基础LLaMA 3.1-8B的33.7%和RAG增强基线的40.1%），充分证明了其功能正确性的显著提升。

> The growing demand for robust quantum programming frameworks has unveiled a critical limitation: current large language model (LLM) based quantum code assistants heavily rely on remote APIs, introducing challenges related to privacy, latency, and excessive usage costs. Addressing this gap, we propose PennyCoder, a novel lightweight framework for quantum code generation, explicitly designed for local and embedded deployment to enable on-device quantum programming assistance without external API dependence. PennyCoder leverages a fine-tuned version of the LLaMA 3.1-8B model, adapted through parameter-efficient Low-Rank Adaptation (LoRA) techniques combined with domain-specific instruction tuning optimized for the specialized syntax and computational logic of quantum programming in PennyLane, including tasks in quantum machine learning and quantum reinforcement learning. Unlike prior work focused on cloud-based quantum code generation, our approach emphasizes device-native operability while maintaining high model efficacy. We rigorously evaluated PennyCoder over a comprehensive quantum programming dataset, achieving 44.3% accuracy with our fine-tuned model (compared to 33.7% for the base LLaMA 3.1-8B and 40.1% for the RAG-augmented baseline), demonstrating a significant improvement in functional correctness.

[Arxiv](https://arxiv.org/abs/2507.19562)