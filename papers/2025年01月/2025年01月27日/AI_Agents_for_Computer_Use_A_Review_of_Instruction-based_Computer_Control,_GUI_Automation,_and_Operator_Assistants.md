# AI 代理在计算机应用中的综述：指令控制、GUI 自动化与操作员助手

发布时间：2025年01月27日

`Agent

理由：这篇论文主要讨论了基于指令的计算机控制代理（CCAs），这些代理能够在个人电脑或移动设备上执行复杂的操作序列，通过自然语言指令完成任务。论文详细探讨了这些代理的分类、开发、资源以及从手动设计的专用代理向基于基础模型（如大型语言模型和视觉语言模型）的转变。此外，论文还形式化了该问题，并建立了领域分类法，从环境、交互和代理三个角度进行分析。这些内容都与Agent（代理）领域密切相关，因此将其分类为Agent是合适的。` `计算机控制` `人机交互`

> AI Agents for Computer Use: A Review of Instruction-based Computer Control, GUI Automation, and Operator Assistants

# 摘要

> # 摘要
基于指令的计算机控制代理（CCAs）能够在个人电脑或移动设备上执行复杂的操作序列，通过自然语言指令完成任务，使用与人类相同的图形用户界面。本文全面综述了这一新兴领域，探讨了现有代理的分类、开发及其资源，并强调了从手动设计的专用代理向基于基础模型（如大型语言模型（LLMs）和视觉语言模型（VLMs））的转变。我们形式化了该问题，并建立了领域分类法，从三个角度分析代理：（a）环境角度，分析计算机环境；（b）交互角度，描述观察空间（如屏幕截图、HTML）和动作空间（如鼠标、键盘操作、可执行代码）；（c）代理角度，关注代理如何行动和学习行动的核心原则。我们的框架涵盖了专用代理和基础代理，促进了两者的比较分析，并展示了专用代理中的先前解决方案（如环境学习步骤）如何指导更有能力的基础代理的开发。此外，我们回顾了当前的CCA数据集和评估方法，并概述了在生产环境中部署此类代理的挑战。本文共回顾并分类了86个CCAs和33个相关数据集。通过揭示趋势、局限性和未来研究方向，本文为全面理解该领域并推动其未来发展提供了坚实的基础。

> Instruction-based computer control agents (CCAs) execute complex action sequences on personal computers or mobile devices to fulfill tasks using the same graphical user interfaces as a human user would, provided instructions in natural language. This review offers a comprehensive overview of the emerging field of instruction-based computer control, examining available agents -- their taxonomy, development, and respective resources -- and emphasizing the shift from manually designed, specialized agents to leveraging foundation models such as large language models (LLMs) and vision-language models (VLMs). We formalize the problem and establish a taxonomy of the field to analyze agents from three perspectives: (a) the environment perspective, analyzing computer environments; (b) the interaction perspective, describing observations spaces (e.g., screenshots, HTML) and action spaces (e.g., mouse and keyboard actions, executable code); and (c) the agent perspective, focusing on the core principle of how an agent acts and learns to act. Our framework encompasses both specialized and foundation agents, facilitating their comparative analysis and revealing how prior solutions in specialized agents, such as an environment learning step, can guide the development of more capable foundation agents. Additionally, we review current CCA datasets and CCA evaluation methods and outline the challenges to deploying such agents in a productive setting. In total, we review and classify 86 CCAs and 33 related datasets. By highlighting trends, limitations, and future research directions, this work presents a comprehensive foundation to obtain a broad understanding of the field and push its future development.

[Arxiv](https://arxiv.org/abs/2501.16150)