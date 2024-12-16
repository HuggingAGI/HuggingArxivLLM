# Iris：凭借自适应焦点和自我优化来破除图形用户界面（GUI）的复杂性

发布时间：2024年12月13日

`Agent` `数字环境` `视觉代理`

> Iris: Breaking GUI Complexity with Adaptive Focus and Self-Refining

# 摘要

> 数字代理在诸如网页、软件应用和操作系统等交互式数字环境中，被越来越多地用于自动执行任务。基于大型语言模型（LLMs）的文本代理，因特定平台的 API 常需频繁更新，而借助多模态大型语言模型（MLLMs）的视觉代理，通过与图形用户界面（GUIs）直接交互，适应性更强。不过，这些代理在视觉感知方面遭遇重大挑战，尤其在处理高分辨率、视觉复杂的数字环境时。本文推出了 Iris 这一基础视觉代理，它通过两项关键创新来应对这些挑战：信息敏感裁剪（ISC）和自精炼双重学习（SRDL）。ISC 运用边缘检测算法动态识别并优先处理视觉密集区域，向信息密度更高的区域分配更多计算资源，从而实现高效处理。SRDL 利用双重学习循环提升代理处理复杂任务的能力，其中引用（描述 UI 元素）的改进能强化定位（定位元素），反之亦然，且均无需额外的标注数据。实证评估显示，Iris 仅用 85 万个 GUI 标注，就在多项基准测试中达到了顶尖水平，胜过使用 10 倍以上训练数据的方法。这些改进进一步在网络和操作系统代理的下游任务中带来显著成效。

> Digital agents are increasingly employed to automate tasks in interactive digital environments such as web pages, software applications, and operating systems. While text-based agents built on Large Language Models (LLMs) often require frequent updates due to platform-specific APIs, visual agents leveraging Multimodal Large Language Models (MLLMs) offer enhanced adaptability by interacting directly with Graphical User Interfaces (GUIs). However, these agents face significant challenges in visual perception, particularly when handling high-resolution, visually complex digital environments. This paper introduces Iris, a foundational visual agent that addresses these challenges through two key innovations: Information-Sensitive Cropping (ISC) and Self-Refining Dual Learning (SRDL). ISC dynamically identifies and prioritizes visually dense regions using a edge detection algorithm, enabling efficient processing by allocating more computational resources to areas with higher information density. SRDL enhances the agent's ability to handle complex tasks by leveraging a dual-learning loop, where improvements in referring (describing UI elements) reinforce grounding (locating elements) and vice versa, all without requiring additional annotated data. Empirical evaluations demonstrate that Iris achieves state-of-the-art performance across multiple benchmarks with only 850K GUI annotations, outperforming methods using 10x more training data. These improvements further translate to significant gains in both web and OS agent downstream tasks.

[Arxiv](https://arxiv.org/abs/2412.10342)