# QUART-Online：为四足机器人学习打造的无延迟大型多模态语言模型

发布时间：2024年12月20日

`LLM应用` `机器人` `人工智能`

> QUART-Online: Latency-Free Large Multimodal Language Model for Quadruped Robot Learning

# 摘要

> 这篇论文探讨了在四足视觉语言动作（QUAR-VLA）任务中部署多模态大型语言模型（MLLM）所面临的固有推理延迟难题。我们的研究发现，传统的参数削减技术在动作指令调优阶段会损害语言基础模型的性能，所以并不适用。我们推出了一款全新的无延迟四足 MLLM 模型，名为 QUART-Online，旨在提升推理效率的同时不降低语言基础模型的性能。借助动作块离散化（ACD），我们压缩了原始动作表示空间，将连续动作值映射到一组规模更小的离散代表向量上，同时保留关键信息。接着，我们对 MLLM 进行微调，将视觉、语言和压缩后的动作整合到一个统一的语义空间里。实验结果显示，QUART-Online 与现有的 MLLM 系统协同运作，能够与底层控制器频率同步实现实时推理，大幅将各类任务的成功率提高 65％。我们的项目页面是 \href{https://quart-online.github.io}https://quart-online.github.io。

> This paper addresses the inherent inference latency challenges associated with deploying multimodal large language models (MLLM) in quadruped vision-language-action (QUAR-VLA) tasks. Our investigation reveals that conventional parameter reduction techniques ultimately impair the performance of the language foundation model during the action instruction tuning phase, making them unsuitable for this purpose. We introduce a novel latency-free quadruped MLLM model, dubbed QUART-Online, designed to enhance inference efficiency without degrading the performance of the language foundation model. By incorporating Action Chunk Discretization (ACD), we compress the original action representation space, mapping continuous action values onto a smaller set of discrete representative vectors while preserving critical information. Subsequently, we fine-tune the MLLM to integrate vision, language, and compressed actions into a unified semantic space. Experimental results demonstrate that QUART-Online operates in tandem with the existing MLLM system, achieving real-time inference in sync with the underlying controller frequency, significantly boosting the success rate across various tasks by 65\%. Our project page is \href{https://quart-online.github.io}https://quart-online.github.io.

[Arxiv](https://arxiv.org/abs/2412.15576)