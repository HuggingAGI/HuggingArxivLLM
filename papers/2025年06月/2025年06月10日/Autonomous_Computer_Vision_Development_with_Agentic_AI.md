# 基于智能体的自主计算机视觉开发

发布时间：2025年06月10日

`Agent` `计算机视觉`

> Autonomous Computer Vision Development with Agentic AI

# 摘要

> 基于大型语言模型的智能体AI在复杂推理、规划和工具利用方面展现出巨大潜力。我们证明，仅凭自然语言提示，即可通过智能体AI方法自主构建一个专业的计算机视觉系统。这一过程涉及对开源认知AI环境SimpleMind（SM）的扩展，该环境配备可用于医学图像分析的可配置工具。我们通过OpenManus实现了一个基于LLM的智能体，以自动化特定计算机视觉任务的规划（工具配置）。我们提供了一个概念验证演示，证明智能体系统能够解释计算机视觉任务提示，通过分解任务并配置适当的工具来规划相应的SimpleMind工作流。从用户输入提示“提供用于肺、心脏和肋骨分割的SM配置（针对胸透图像）”开始，智能体LLM能够生成规划（YAML格式的工具配置文件），并自主执行SM-Learn（训练）和SM-Think（推理）脚本。计算机视觉智能体在50张胸透图像上自动配置、训练和测试自身，分别实现了肺、心脏和肋骨的平均Dice分数为0.96、0.82和0.83。这项工作展示了自主规划和工具配置的潜力，这些任务传统上由数据科学家在计算机视觉应用开发中完成。

> Agentic Artificial Intelligence (AI) systems leveraging Large Language Models (LLMs) exhibit significant potential for complex reasoning, planning, and tool utilization. We demonstrate that a specialized computer vision system can be built autonomously from a natural language prompt using Agentic AI methods. This involved extending SimpleMind (SM), an open-source Cognitive AI environment with configurable tools for medical image analysis, with an LLM-based agent, implemented using OpenManus, to automate the planning (tool configuration) for a particular computer vision task. We provide a proof-of-concept demonstration that an agentic system can interpret a computer vision task prompt, plan a corresponding SimpleMind workflow by decomposing the task and configuring appropriate tools. From the user input prompt, "provide sm (SimpleMind) config for lungs, heart, and ribs segmentation for cxr (chest x-ray)"), the agent LLM was able to generate the plan (tool configuration file in YAML format), and execute SM-Learn (training) and SM-Think (inference) scripts autonomously. The computer vision agent automatically configured, trained, and tested itself on 50 chest x-ray images, achieving mean dice scores of 0.96, 0.82, 0.83, for lungs, heart, and ribs, respectively. This work shows the potential for autonomous planning and tool configuration that has traditionally been performed by a data scientist in the development of computer vision applications.

[Arxiv](https://arxiv.org/abs/2506.11140)