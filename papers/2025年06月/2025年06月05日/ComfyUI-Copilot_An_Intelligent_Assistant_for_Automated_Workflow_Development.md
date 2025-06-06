# ComfyUI-Copilot：自动化工作流程开发的智能助手

发布时间：2025年06月05日

`LLM应用

理由：这篇论文主要讨论了如何将大型语言模型（LLM）应用于提升开源AI艺术创作平台ComfyUI的用户体验。通过智能节点推荐、模型推荐和自动化工作流构建等功能，ComfyUI-Copilot展示了LLM在实际应用中的具体用途，属于LLM应用领域的研究。` `AI艺术` `艺术创作`

> ComfyUI-Copilot: An Intelligent Assistant for Automated Workflow Development

# 摘要

> 我们很高兴推出ComfyUI-Copilot——一款专为开源AI艺术创作平台ComfyUI打造的大型语言模型驱动插件，旨在提升其易用性和效率。尽管ComfyUI以其友好的界面和高度的灵活性著称，但对新手用户而言，使用过程中仍可能遇到诸多挑战，包括文档资料有限、模型配置容易出错以及工作流设计复杂等问题。ComfyUI-Copilot通过提供智能节点推荐、智能模型推荐以及一键式自动化工作流构建功能，有效解决了这些问题。系统采用了一种创新的分层多智能体架构，包含一个负责任务分配的中央助理代理和多个专注于不同使用场景的专用工作代理，同时借助我们精心整理的ComfyUI知识库，进一步优化了调试和部署流程。我们通过离线定量评估和在线用户反馈双重验证，证实了ComfyUI-Copilot的有效性。实验结果表明，该插件不仅能够精准推荐所需节点，还能显著加速工作流开发进程。此外，实际使用案例也充分证明，ComfyUI-Copilot不仅降低了新手用户的入门门槛，还为资深用户提升了工作效率。如需获取ComfyUI-Copilot的安装包和演示视频，欢迎访问我们的GitHub仓库：https://github.com/AIDC-AI/ComfyUI-Copilot。

> We introduce ComfyUI-Copilot, a large language model-powered plugin designed to enhance the usability and efficiency of ComfyUI, an open-source platform for AI-driven art creation. Despite its flexibility and user-friendly interface, ComfyUI can present challenges to newcomers, including limited documentation, model misconfigurations, and the complexity of workflow design. ComfyUI-Copilot addresses these challenges by offering intelligent node and model recommendations, along with automated one-click workflow construction. At its core, the system employs a hierarchical multi-agent framework comprising a central assistant agent for task delegation and specialized worker agents for different usages, supported by our curated ComfyUI knowledge bases to streamline debugging and deployment. We validate the effectiveness of ComfyUI-Copilot through both offline quantitative evaluations and online user feedback, showing that it accurately recommends nodes and accelerates workflow development. Additionally, use cases illustrate that ComfyUI-Copilot lowers entry barriers for beginners and enhances workflow efficiency for experienced users. The ComfyUI-Copilot installation package and a demo video are available at https://github.com/AIDC-AI/ComfyUI-Copilot.

[Arxiv](https://arxiv.org/abs/2506.05010)