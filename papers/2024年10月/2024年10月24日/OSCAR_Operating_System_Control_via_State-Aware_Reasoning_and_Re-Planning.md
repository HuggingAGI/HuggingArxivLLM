# OSCAR：借助状态感知推理与重新规划实现操作系统控制

发布时间：2024年10月24日

`Agent` `操作系统` `自动化任务`

> OSCAR: Operating System Control via State-Aware Reasoning and Re-Planning

# 摘要

> 大型语言模型（LLMs）和大型多模态模型（LMMs）在自动化像网页浏览和游戏这类复杂任务时展现出极大的潜力。但它们在不同应用中的泛化能力有限，限制了其更广泛的用途。为解决此难题，我们推出了 OSCAR：借助状态感知推理和重新规划来实现操作系统控制。OSCAR 是一个全能代理，能够通过诸如鼠标和键盘输入等标准控制，自主导航并与各类桌面和移动应用交互，同时处理屏幕图像以完成用户指令。OSCAR 能将人类指令转化为可执行的 Python 代码，实现对图形用户界面（GUIs）的精准控制。为增强稳定性和适应性，OSCAR 以状态机的形式运行，配备有错误处理机制和动态任务重新规划，从而能高效地根据实时反馈和异常情况进行调整。我们在桌面和移动平台的多种基准测试中进行了大量实验，证明了 OSCAR 的有效性，它把复杂的工作流程转变为简单的自然语言指令，大幅提升了用户的生产力。我们的代码在发布时将开源。

> Large language models (LLMs) and large multimodal models (LMMs) have shown great potential in automating complex tasks like web browsing and gaming. However, their ability to generalize across diverse applications remains limited, hindering broader utility. To address this challenge, we present OSCAR: Operating System Control via state-Aware reasoning and Re-planning. OSCAR is a generalist agent designed to autonomously navigate and interact with various desktop and mobile applications through standardized controls, such as mouse and keyboard inputs, while processing screen images to fulfill user commands. OSCAR translates human instructions into executable Python code, enabling precise control over graphical user interfaces (GUIs). To enhance stability and adaptability, OSCAR operates as a state machine, equipped with error-handling mechanisms and dynamic task re-planning, allowing it to efficiently adjust to real-time feedback and exceptions. We demonstrate OSCAR's effectiveness through extensive experiments on diverse benchmarks across desktop and mobile platforms, where it transforms complex workflows into simple natural language commands, significantly boosting user productivity. Our code will be open-source upon publication.

[Arxiv](https://arxiv.org/abs/2410.18963)