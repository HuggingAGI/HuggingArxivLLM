# Zoomer：自适应图像聚焦优化，专为黑盒MLLM设计

发布时间：2025年04月29日

`LLM应用` `图像处理`

> Zoomer: Adaptive Image Focus Optimization for Black-box MLLM

# 摘要

> 多模态大型语言模型（MLLMs）的最新进展极大地拓展了视觉-语言任务的应用范围，尤其在图像描述和交互式问答等领域表现卓越。然而，这些模型在处理视觉数据时仍面临挑战，特别是在需要精确物体识别和精细视觉细节的任务中。严格的代币限制常导致关键信息遗漏，影响模型性能。

为了解决这些问题，我们推出了\SysName，一种创新的视觉提示机制，旨在在代币限制内提升MLLM性能，同时保留关键视觉细节。

\SysName的三大核心创新包括：动态突出相关图像区域的提示感知策略、保持物体完整性的空间保留编排架构，以及平衡全局上下文与关键视觉细节的预算感知提示方法。

在多个数据集上的全面评估显示，\SysName始终超越基线方法，准确率提升高达$26.9\%$，同时显著减少代币消耗。

> Recent advancements in multimodal large language models (MLLMs) have broadened the scope of vision-language tasks, excelling in applications like image captioning and interactive question-answering. However, these models struggle with accurately processing visual data, particularly in tasks requiring precise object recognition and fine visual details. Stringent token limits often result in the omission of critical information, hampering performance. To address these limitations, we introduce \SysName, a novel visual prompting mechanism designed to enhance MLLM performance while preserving essential visual details within token limits. \SysName features three key innovations: a prompt-aware strategy that dynamically highlights relevant image regions, a spatial-preserving orchestration schema that maintains object integrity, and a budget-aware prompting method that balances global context with crucial visual details. Comprehensive evaluations across multiple datasets demonstrate that \SysName consistently outperforms baseline methods, achieving up to a $26.9\%$ improvement in accuracy while significantly reducing token consumption.

[Arxiv](https://arxiv.org/abs/2505.00742)