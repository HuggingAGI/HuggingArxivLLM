# Ponder & Press：推动视觉图形用户界面代理迈向通用计算机控制

发布时间：2024年12月02日

`Agent` `计算机` `图形用户界面`

> Ponder & Press: Advancing Visual GUI Agent towards General Computer Control

# 摘要

> 大多数现有的 GUI 代理往往依赖于诸如 HTML 源代码或可访问性树之类的非视觉输入，这限制了它们在不同软件环境和平台中的灵活性。当前擅长利用视觉来定位现实世界对象的多模态大型语言模型（MLLMs）带来了一种可能的替代选择。然而，由于现实世界对象与 GUI 元素之间存在语义差距，它们在精确定位 GUI 元素方面常遭遇难题——而这是实现有效 GUI 自动化的关键需求。在本项工作中，我们推出了 Ponder & Press，这是一个仅依靠视觉输入来实现通用计算机控制的分治框架。我们的方法将通用的 MLLM 作为“解释器”，负责把高级用户指令转化为详细的动作描述，同时将特定于 GUI 的 MLLM 作为“定位器”，精准定位用于执行动作的 GUI 元素。凭借纯视觉输入，我们的代理提供了一种通用且类人的交互模式，适用于众多应用场景。Ponder & Press 定位器在 ScreenSpot GUI 基准测试中比现有模型高出 22.5%。在涵盖网页、桌面软件和移动 UI 等各种 GUI 环境的离线和交互式代理基准测试中，均表明 Ponder & Press 框架达到了最先进的性能，凸显了视觉 GUI 代理的潜力。请访问项目主页 https://invinciblewyq.github.io/ponder-press-page/

> Most existing GUI agents typically depend on non-vision inputs like HTML source code or accessibility trees, limiting their flexibility across diverse software environments and platforms. Current multimodal large language models (MLLMs), which excel at using vision to ground real-world objects, offer a potential alternative. However, they often struggle with accurately localizing GUI elements -- a critical requirement for effective GUI automation -- due to the semantic gap between real-world objects and GUI elements. In this work, we introduce Ponder & Press, a divide-and-conquer framework for general computer control using only visual input. Our approach combines an general-purpose MLLM as an 'interpreter', responsible for translating high-level user instructions into detailed action descriptions, with a GUI-specific MLLM as a 'locator' that precisely locates GUI elements for action placement. By leveraging a purely visual input, our agent offers a versatile, human-like interaction paradigm applicable to a wide range of applications. Ponder & Press locator outperforms existing models by +22.5% on the ScreenSpot GUI grounding benchmark. Both offline and interactive agent benchmarks across various GUI environments -- including web pages, desktop software, and mobile UIs -- demonstrate that Ponder & Press framework achieves state-of-the-art performance, highlighting the potential of visual GUI agents. Refer to the project homepage https://invinciblewyq.github.io/ponder-press-page/

[Arxiv](https://arxiv.org/abs/2412.01268)