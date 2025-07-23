# Screen2AX：基于视觉驱动的macOS辅助功能自动生成实现

发布时间：2025年07月22日

`Agent` `无障碍技术` `计算机视觉`

> Screen2AX: Vision-Based Approach for Automatic macOS Accessibility Generation

# 摘要

> 桌面可访问性元数据让AI代理能够理解屏幕内容，为依赖屏幕阅读器等辅助工具的用户提供支持。然而，由于开发人员提供的元数据不完整或缺失，许多应用程序仍难以访问——我们的调查显示，macOS平台上仅有33%的应用程序提供了完整的可访问性支持。尽管近期在结构化屏幕表示方面的研究主要针对特定挑战，如UI元素检测或标注，但尚未有研究尝试通过复制其完整的层级结构来捕捉桌面界面的全部复杂性。为填补这一空白，我们推出了Screen2AX——首个能够从单张屏幕截图中自动生成实时树状可访问性元数据的框架。我们的方法利用视觉语言和目标检测模型，以层级方式检测、描述并组织UI元素，完美还原macOS的系统级可访问性结构。为应对macOS桌面应用程序数据有限的挑战，我们整理并公开发布了三个数据集，涵盖112款macOS应用程序，每款应用均标注了UI元素检测、分组及层级可访问性元数据，并附有对应屏幕截图。Screen2AX能够准确推断层级树，在重建完整可访问性树方面达到了77%的F1分数。这些层级树显著提升了自主代理解读和交互复杂桌面界面的能力。我们还推出了Screen2AX-Task，这是一个专门用于评估macOS桌面环境中自主代理任务执行的基准测试。通过此基准测试，我们证明Screen2AX的性能较原生可访问性表示提升了2.2倍，并在ScreenSpot基准上超越了最先进的OmniParser V2系统。


> Desktop accessibility metadata enables AI agents to interpret screens and supports users who depend on tools like screen readers. Yet, many applications remain largely inaccessible due to incomplete or missing metadata provided by developers - our investigation shows that only 33% of applications on macOS offer full accessibility support. While recent work on structured screen representation has primarily addressed specific challenges, such as UI element detection or captioning, none has attempted to capture the full complexity of desktop interfaces by replicating their entire hierarchical structure. To bridge this gap, we introduce Screen2AX, the first framework to automatically create real-time, tree-structured accessibility metadata from a single screenshot. Our method uses vision-language and object detection models to detect, describe, and organize UI elements hierarchically, mirroring macOS's system-level accessibility structure. To tackle the limited availability of data for macOS desktop applications, we compiled and publicly released three datasets encompassing 112 macOS applications, each annotated for UI element detection, grouping, and hierarchical accessibility metadata alongside corresponding screenshots. Screen2AX accurately infers hierarchy trees, achieving a 77% F1 score in reconstructing a complete accessibility tree. Crucially, these hierarchy trees improve the ability of autonomous agents to interpret and interact with complex desktop interfaces. We introduce Screen2AX-Task, a benchmark specifically designed for evaluating autonomous agent task execution in macOS desktop environments. Using this benchmark, we demonstrate that Screen2AX delivers a 2.2x performance improvement over native accessibility representations and surpasses the state-of-the-art OmniParser V2 system on the ScreenSpot benchmark.

[Arxiv](https://arxiv.org/abs/2507.16704)