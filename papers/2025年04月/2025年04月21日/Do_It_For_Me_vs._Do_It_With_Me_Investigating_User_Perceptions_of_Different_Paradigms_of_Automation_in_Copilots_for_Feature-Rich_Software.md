# 替我做 vs. 与我一起做：探究用户对功能丰富的软件Copilot中不同自动化范式的感知
对比分析用户对功能丰富的软件Copilot中不同自动化模式的感知：Do It For Me vs. Do It With Me

发布时间：2025年04月21日

`LLM应用` `软件工程` `用户体验`

> Do It For Me vs. Do It With Me: Investigating User Perceptions of Different Paradigms of Automation in Copilots for Feature-Rich Software

# 摘要

> 基于大型语言模型（LLM）的应用内助手（副驾驶）虽然能实现软件任务的自动化，但用户更倾向于通过实践学习，这引发了关于实现有效用户体验的最佳自动化水平的疑问。我们通过设计并实现全自动副驾驶（AutoCopilot）和半自动副驾驶（GuidedCopilot）来研究两种自动化范式。GuidedCopilot能够自动完成琐碎步骤，同时提供逐步的视觉指导。在涵盖数据分析和视觉设计任务的用户研究（N=20）中，GuidedCopilot在用户控制、软件实用性和可学习性方面优于AutoCopilot，尤其在探索性和创造性任务中表现突出，而AutoCopilot在更简单的视觉任务中节省了时间。随后的设计探索（N=10）通过引入任务和状态感知功能增强了GuidedCopilot，包括上下文预览片段和自适应指令。我们的研究结果表明，在设计下一代副驾驶时，用户控制和个性化指导是关键因素，这些副驾驶能够提升生产力，支持不同技能水平，并促进更深层次的软件互动。

> Large Language Model (LLM)-based in-application assistants, or copilots, can automate software tasks, but users often prefer learning by doing, raising questions about the optimal level of automation for an effective user experience. We investigated two automation paradigms by designing and implementing a fully automated copilot (AutoCopilot) and a semi-automated copilot (GuidedCopilot) that automates trivial steps while offering step-by-step visual guidance. In a user study (N=20) across data analysis and visual design tasks, GuidedCopilot outperformed AutoCopilot in user control, software utility, and learnability, especially for exploratory and creative tasks, while AutoCopilot saved time for simpler visual tasks. A follow-up design exploration (N=10) enhanced GuidedCopilot with task-and state-aware features, including in-context preview clips and adaptive instructions. Our findings highlight the critical role of user control and tailored guidance in designing the next generation of copilots that enhance productivity, support diverse skill levels, and foster deeper software engagement.

[Arxiv](https://arxiv.org/abs/2504.15549)