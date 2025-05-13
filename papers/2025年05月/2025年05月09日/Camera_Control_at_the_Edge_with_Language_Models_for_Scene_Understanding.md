# # 基于语言模型的边缘摄像头控制，用于场景理解

发布时间：2025年05月09日

`LLM应用` `摄像头技术` `计算机视觉`

> Camera Control at the Edge with Language Models for Scene Understanding

# 摘要

> 本文提出了一种名为优化提示驱动的统一系统（OPUS）的框架，它利用大型语言模型（LLM）来控制云台变焦（PTZ）摄像头，实现对自然环境的深入理解。OPUS通过从高级摄像头控制API生成关键词，并借助监督微调（SFT）将大型闭源语言模型的知识迁移到更小的模型中，显著提升了成本效益。这种创新使得在边缘端实现高效部署的同时，性能仍能与GPT-4等大型模型相媲美。OPUS通过将多摄像头数据转化为语言模型可理解的文本描述，增强了环境感知能力，完全摆脱了对专门传感器标记的依赖。在基准测试中，OPUS的表现远超传统语言模型技术和复杂的提示方法，相比先进方法实现了35%的性能提升，并在任务准确性上比Gemini Pro等闭源模型高出20%。系统实验证明，OPUS通过直观的自然语言界面，大幅简化了PTZ摄像头的操作流程。这种方法无需显式编程，为用户与摄像头系统之间的交互提供了一种全新的对话式方式，标志着PTZ摄像头技术控制与应用方式的重大革新。

> In this paper, we present Optimized Prompt-based Unified System (OPUS), a framework that utilizes a Large Language Model (LLM) to control Pan-Tilt-Zoom (PTZ) cameras, providing contextual understanding of natural environments. To achieve this goal, the OPUS system improves cost-effectiveness by generating keywords from a high-level camera control API and transferring knowledge from larger closed-source language models to smaller ones through Supervised Fine-Tuning (SFT) on synthetic data. This enables efficient edge deployment while maintaining performance comparable to larger models like GPT-4. OPUS enhances environmental awareness by converting data from multiple cameras into textual descriptions for language models, eliminating the need for specialized sensory tokens. In benchmark testing, our approach significantly outperformed both traditional language model techniques and more complex prompting methods, achieving a 35% improvement over advanced techniques and a 20% higher task accuracy compared to closed-source models like Gemini Pro. The system demonstrates OPUS's capability to simplify PTZ camera operations through an intuitive natural language interface. This approach eliminates the need for explicit programming and provides a conversational method for interacting with camera systems, representing a significant advancement in how users can control and utilize PTZ camera technology.

[Arxiv](https://arxiv.org/abs/2505.06402)