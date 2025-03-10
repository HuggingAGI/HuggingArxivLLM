# # WinClick：利用多模态大型语言模型实现GUI交互定位

发布时间：2025年01月27日

`LLM应用` `软件测试` `用户界面`

> WinClick: GUI Grounding with Multimodal Large Language Models

# 摘要

> 图形用户界面（GUI）任务在软件测试和用户界面导航等自动化工作中扮演着关键角色。对于用户而言，GUI 是与计算机交互最直观的平台。然而，开发视觉 GUI 代理面临一个重大挑战：根据指令准确定位屏幕元素的能力，即 GUI 锚定。现有 GUI 代理通常依赖于结构化的数据格式（如 DOM 或 HTML 文件）进行训练或推理，但这些格式无法在所有应用中通用，尤其在 Windows 操作系统等通用桌面环境中。为解决这一难题，我们推出了 WinClick——一个在 Windows 平台上开发的新型视觉 GUI 代理。WinClick 通过屏幕截图检测可操作区域。我们对 WinClick 进行了 GUI 锚定预训练，并提出了一种基于大语言模型（LLM）的方法来优化 GUI 锚定数据的对齐。此外，我们还发布了 WinSpot——首个针对 Windows 环境下 GUI 锚定的综合性基准测试。实验结果表明，结合 GUI 锚定预训练的 WinClick 显著超越了现有基线方法，为桌面环境中的 GUI 自动化提供了可扩展的解决方案。WinSpot 的开源地址为 https://github.com/zackhuiiiii/WinSpot。

> Graphical User Interface (GUI) tasks are vital for automating workflows such as software testing, user interface navigation. For users, the GUI is the most intuitive platform for interacting with a computer. Previous work identified a key challenge in developing visual GUI agents: GUI grounding - the ability to accurately locate screen elements based on instructions. However, most existing GUI agents rely on structured data formats like DOM or HTML files in training or inferencing, which are inaccessible across all applications, particular in a general desktop environments such as Windows OS. To address this, we introduce WinClick, a novel visual GUI agent developed in Windows platform. WinClick leverages screenshots to detect actionable regions. To overcome the challenge of GUI grounding, we enhance WinClick with GUI grounding pre-training and propose an LLM-based method for aligning GUI grounding data. Additionally, we introduce WinSpot, the first comprehensive benchmark for GUI grounding on Windows. Our experiments demonstrate that WinClick, combined with GUI grounding pre-training, significantly outperforms existing baselines, offering a scalable solution for GUI automation in desktop environments. WinSpot is publicly available at https://github.com/zackhuiiiii/WinSpot.

[Arxiv](https://arxiv.org/abs/2503.04730)