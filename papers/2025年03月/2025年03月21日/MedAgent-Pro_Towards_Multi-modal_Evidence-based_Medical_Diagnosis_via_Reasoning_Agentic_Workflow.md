# MedAgent-Pro：迈向多模态证据支持的医学诊断，基于推理智能体工作流

发布时间：2025年03月21日

`LLM应用` `诊断系统`

> MedAgent-Pro: Towards Multi-modal Evidence-based Medical Diagnosis via Reasoning Agentic Workflow

# 摘要

> 开发可靠的AI辅助系统以协助医生进行多模态医疗诊断一直是研究热点。近年来，多模态大型语言模型（MLLMs）在多个领域取得了突破性进展。凭借强大的推理能力和多样化的任务执行能力，它们在医学诊断领域展现出巨大潜力。然而，直接应用于医学领域仍面临挑战：MLLMs缺乏对视觉输入的深入理解，限制了其在关键的定量图像分析方面的表现。此外，MLLMs常出现推理不一致和幻觉现象，而医学诊断必须严格遵循临床标准。为解决这些问题，我们开发了MedAgent-Pro——一个基于证据推理的智能诊断系统，致力于实现可靠、可解释且精准的医学诊断。该系统通过分层工作流程实现目标：在任务层面，基于知识的推理根据临床标准生成可靠的诊断计划；在案例层面，多个工具代理协同处理多模态数据，结合定量与定性证据提供最终诊断。实验结果表明，MedAgent-Pro在2D和3D医学诊断任务中表现优异，案例研究进一步证明了其可靠性和可解释性。代码已开源，详情请访问https://github.com/jinlab-imvr/MedAgent-Pro。

> Developing reliable AI systems to assist human clinicians in multi-modal medical diagnosis has long been a key objective for researchers. Recently, Multi-modal Large Language Models (MLLMs) have gained significant attention and achieved success across various domains. With strong reasoning capabilities and the ability to perform diverse tasks based on user instructions, they hold great potential for enhancing medical diagnosis. However, directly applying MLLMs to the medical domain still presents challenges. They lack detailed perception of visual inputs, limiting their ability to perform quantitative image analysis, which is crucial for medical diagnostics. Additionally, MLLMs often exhibit hallucinations and inconsistencies in reasoning, whereas clinical diagnoses must adhere strictly to established criteria. To address these challenges, we propose MedAgent-Pro, an evidence-based reasoning agentic system designed to achieve reliable, explainable, and precise medical diagnoses. This is accomplished through a hierarchical workflow: at the task level, knowledge-based reasoning generate reliable diagnostic plans for specific diseases following retrieved clinical criteria. While at the case level, multiple tool agents process multi-modal inputs, analyze different indicators according to the plan, and provide a final diagnosis based on both quantitative and qualitative evidence. Comprehensive experiments on both 2D and 3D medical diagnosis tasks demonstrate the superiority and effectiveness of MedAgent-Pro, while case studies further highlight its reliability and interpretability. The code is available at https://github.com/jinlab-imvr/MedAgent-Pro.

[Arxiv](https://arxiv.org/abs/2503.18968)