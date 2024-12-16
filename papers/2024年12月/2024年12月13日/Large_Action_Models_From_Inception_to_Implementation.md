# 大型动作模型：从发端到落地

发布时间：2024年12月13日

`Agent` `人工智能` `代理系统`

> Large Action Models: From Inception to Implementation

# 摘要

> 随着人工智能持续进步，对于超越语言辅助、迈向能够在现实世界执行行动的智能体的系统的需求与日俱增。这种发展需要从擅长生成文本回应的传统大型语言模型（LLMs）过渡到专为在动态环境中生成和执行行动而设计的大型行动模型（LAMs）。在代理系统的助力下，LAMs 有望将人工智能从被动的语言理解转变为主动的任务完成，这标志着迈向通用人工智能的重要里程碑。
    在本文中，我们呈现了一个开发 LAMs 的综合框架，为其创建提供了从起始到部署的系统性方法。我们先对 LAMs 进行了概述，突出了其独特特性，并阐明了它们与 LLMs 的差异。以基于 Windows 操作系统的代理作为案例研究，我们提供了 LAM 开发关键阶段的详细分步指南，涵盖数据收集、模型训练、环境集成、基础构建和评估。这种可通用的工作流程可作为在各类应用领域创建功能性 LAMs 的蓝图。最后，我们指明了 LAMs 的当前局限，并探讨了未来研究和工业部署的方向，强调了在现实世界应用中充分发挥 LAMs 潜力所面临的挑战和机遇。
    本文中使用的数据收集过程的代码可在以下网址公开获取：https://github.com/microsoft/UFO/tree/main/dataflow ，全面的文档可在 https://microsoft.github.io/UFO/dataflow/overview/ 找到。

> As AI continues to advance, there is a growing demand for systems that go beyond language-based assistance and move toward intelligent agents capable of performing real-world actions. This evolution requires the transition from traditional Large Language Models (LLMs), which excel at generating textual responses, to Large Action Models (LAMs), designed for action generation and execution within dynamic environments. Enabled by agent systems, LAMs hold the potential to transform AI from passive language understanding to active task completion, marking a significant milestone in the progression toward artificial general intelligence.
  In this paper, we present a comprehensive framework for developing LAMs, offering a systematic approach to their creation, from inception to deployment. We begin with an overview of LAMs, highlighting their unique characteristics and delineating their differences from LLMs. Using a Windows OS-based agent as a case study, we provide a detailed, step-by-step guide on the key stages of LAM development, including data collection, model training, environment integration, grounding, and evaluation. This generalizable workflow can serve as a blueprint for creating functional LAMs in various application domains. We conclude by identifying the current limitations of LAMs and discussing directions for future research and industrial deployment, emphasizing the challenges and opportunities that lie ahead in realizing the full potential of LAMs in real-world applications.
  The code for the data collection process utilized in this paper is publicly available at: https://github.com/microsoft/UFO/tree/main/dataflow, and comprehensive documentation can be found at https://microsoft.github.io/UFO/dataflow/overview/.

[Arxiv](https://arxiv.org/abs/2412.10047)