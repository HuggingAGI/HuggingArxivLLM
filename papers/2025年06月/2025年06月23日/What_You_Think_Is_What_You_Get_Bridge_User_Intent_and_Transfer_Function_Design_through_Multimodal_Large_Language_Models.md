# 心想事成：通过多模态大型语言模型连接用户意图与转换函数设计

发布时间：2025年06月23日

`LLM应用` `计算机图形学` `人工智能`

> What You Think Is What You Get: Bridge User Intent and Transfer Function Design through Multimodal Large Language Models

# 摘要

> 直接体积渲染（DVR）是可视化体积数据的核心技术，其中转移函数（TFs）在提取结构信息方面至关重要。然而，由于用户意图与TF参数空间之间的语义鸿沟，设计有效的TF仍然充满挑战。尽管研究人员开发了多种TF优化方法，但现有方案仍面临两大难题：庞大的探索空间和较差的泛化能力。为此，我们提出了“所想即所得”（WYTWYG）框架，该框架巧妙地结合了多模态大语言模型（MLLMs），根据用户意图指导TF优化过程。具体而言，我们创新性地提出了一个包含两大核心组件的TF优化方法：（1）基于进化的探索器，用于高效探索TF空间；（2）基于MLLMs的体积渲染质量评估器，提供通用的视觉指导。在此基础上，我们进一步开发了一个TF交互设计系统。通过三个实际案例，我们验证了该框架的通用适用性，而大量实验结果也充分证明了各组件的有效性。我们的代码已开源，地址为：https://github.com/wyysteelhead/TFevolve。

> Direct volume rendering (DVR) is a fundamental technique for visualizing volumetric data, with transfer functions (TFs) playing a crucial role in extracting meaningful structures. However, designing effective TFs remains unintuitive due to the semantic gap between user intent and TF parameter space. Researchers have developed numerous TF optimization methods to bridge this gap. However, existing methods still face two challenges: large exploration space and weak generalizability. To address these issues, we propose What You Think is What You Get (WYTWYG) framework, which leveraging Multi-model Large Language Models (MLLMs) to guide the TF optimization based on user intent. Specifically, we first introduce a novel TF optimization approach comprising two core components: (1) an evolution-based explorer for effective exploration of the TF space, and (2) a volume rendering quality evaluator based on MLLMs to provide generalizable visual guidance. We further propose a TF interactive design system based on this approach. We demonstrate the general applicability of our framework through three case studies, and validate the effectiveness of each component through extensive experiments. Our code is available at: https://github.com/wyysteelhead/TFevolve.

[Arxiv](https://arxiv.org/abs/2506.18407)