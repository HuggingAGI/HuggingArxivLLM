# 利用大型语言模型代理实现自主显微镜实验

发布时间：2024年12月18日

`Agent

理由：这篇论文主要讨论的是基于大型语言模型（LLM）驱动的AI代理框架AILA，旨在自动化原子力显微镜（AFM）操作。论文的核心内容围绕AI代理在科学实验室中的应用，特别是如何评估和提升AI代理在实验设计、结果分析等任务中的表现。因此，这篇论文属于Agent分类，因为它主要关注AI代理的设计、评估和应用。` `材料科学` `实验室自动化`

> Autonomous Microscopy Experiments through Large Language Model Agents

# 摘要

> 大型语言模型（LLMs）的崛起推动了材料研究中自驱动实验室（SDLs）的快速发展。然而，当前的SDL实现依赖于僵化的预定义协议，限制了其在不同实验室中应对动态实验场景的灵活性。一个关键挑战在于如何评估AI代理能否有效模仿专家科学家的自适应决策和实验直觉。为此，我们推出了AILA（人工智慧实验室助手），这是一个基于LLM驱动的代理框架，旨在自动化原子力显微镜（AFM）操作。通过AFM作为实验平台，我们开发了AFMBench——一个全面的评估套件，挑战基于GPT-4o和GPT-3.5等语言模型的AI代理，要求其完成从实验设计到结果分析的全流程任务。我们的系统评估显示，即使是最先进的语言模型在文档检索等基础任务上也表现不佳，导致在多代理协作场景中性能大幅下降。此外，LLMs还表现出不遵守指令甚至偏离原始任务的现象，这引发了SDL中AI代理安全对齐的严重担忧。最后，我们展示了AILA在复杂开放式实验中的应用，包括自动化AFM校准、高分辨率特征检测和机械性能测量。我们的研究强调了在将AI代理广泛应用于科学实验室之前，必须建立严格的基准测试标准。

> The emergence of large language models (LLMs) has accelerated the development of self-driving laboratories (SDLs) for materials research. Despite their transformative potential, current SDL implementations rely on rigid, predefined protocols that limit their adaptability to dynamic experimental scenarios across different labs. A significant challenge persists in measuring how effectively AI agents can replicate the adaptive decision-making and experimental intuition of expert scientists. Here, we introduce AILA (Artificially Intelligent Lab Assistant), a framework that automates atomic force microscopy (AFM) through LLM-driven agents. Using AFM as an experimental testbed, we develop AFMBench-a comprehensive evaluation suite that challenges AI agents based on language models like GPT-4o and GPT-3.5 to perform tasks spanning the scientific workflow: from experimental design to results analysis. Our systematic assessment shows that state-of-the-art language models struggle even with basic tasks such as documentation retrieval, leading to a significant decline in performance in multi-agent coordination scenarios. Further, we observe that LLMs exhibit a tendency to not adhere to instructions or even divagate to additional tasks beyond the original request, raising serious concerns regarding safety alignment aspects of AI agents for SDLs. Finally, we demonstrate the application of AILA on increasingly complex experiments open-ended experiments: automated AFM calibration, high-resolution feature detection, and mechanical property measurement. Our findings emphasize the necessity for stringent benchmarking protocols before deploying AI agents as laboratory assistants across scientific disciplines.

[Arxiv](https://arxiv.org/abs/2501.10385)