# # 车载大型语言模型助力自动驾驶系统升级

发布时间：2025年04月15日

`LLM应用` `自动驾驶` `智能驾驶`

> Enhancing Autonomous Driving Systems with On-Board Deployed Large Language Models

# 摘要

> 监督学习训练的神经网络（NNs）在处理真实驾驶中的边缘案例时面临挑战，因为全面覆盖所有边缘场景的数据集难以构建。因此，类似于人类直观识别异常驾驶行为的知识驱动方法，可以作为数据驱动方法的有力补充。本研究提出了一种结合底层模型预测控制器（MPC）与本地部署的大型语言模型（LLMs）的混合架构，以提升决策能力和人机交互（HMI）。决策xLLM模块通过对比机器人状态信息与自然语言指令，确保符合预期驾驶行为。随后，MPCxLLM模块根据LLM生成的见解调整MPC参数，在保持传统MPC系统安全性和约束保证的同时，实现控制适应性。此外，为了实现高效的车载部署并消除对云连接的依赖，我们将处理转移到车载计算平台：我们提出了一种结合检索增强生成（RAG）、低秩适配（LoRA）微调和量化的方法。实验结果表明，这些改进显著提升了推理准确性（最高提升10.45%）、控制适应性（最高提升52.2%），以及计算效率（每秒处理的标记数提升高达10.5倍）。这验证了所提出的框架在实时部署中的实用性，即使是在性能较低的机器人平台上。本研究将高层决策与底层控制适应性相结合，为知识驱动和自适应的自主驾驶系统（ADS）提供了一个协同框架。

> Neural Networks (NNs) trained through supervised learning struggle with managing edge-case scenarios common in real-world driving due to the intractability of exhaustive datasets covering all edge-cases, making knowledge-driven approaches, akin to how humans intuitively detect unexpected driving behavior, a suitable complement to data-driven methods. This work proposes a hybrid architecture combining low-level Model Predictive Controller (MPC) with locally deployed Large Language Models (LLMs) to enhance decision-making and Human Machine Interaction (HMI). The DecisionxLLM module evaluates robotic state information against natural language instructions to ensure adherence to desired driving behavior. The MPCxLLM module then adjusts MPC parameters based on LLM-generated insights, achieving control adaptability while preserving the safety and constraint guarantees of traditional MPC systems. Further, to enable efficient on-board deployment and to eliminate dependency on cloud connectivity, we shift processing to the on-board computing platform: We propose an approach that exploits Retrieval Augmented Generation (RAG), Low Rank Adaptation (LoRA) fine-tuning, and quantization. Experimental results demonstrate that these enhancements yield significant improvements in reasoning accuracy by up to 10.45%, control adaptability by as much as 52.2%, and up to 10.5x increase in computational efficiency (tokens/s), validating the proposed framework's practicality for real-time deployment even on down-scaled robotic platforms. This work bridges high-level decision-making with low-level control adaptability, offering a synergistic framework for knowledge-driven and adaptive Autonomous Driving Systems (ADS).

[Arxiv](https://arxiv.org/abs/2504.11514)