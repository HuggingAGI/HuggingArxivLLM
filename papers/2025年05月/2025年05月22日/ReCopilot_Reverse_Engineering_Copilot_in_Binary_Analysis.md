# # ReCopilot：二进制分析中的 Copilot 逆向工程解析

发布时间：2025年05月22日

`LLM应用

摘要中详细描述了ReCopilot作为一款专为二进制分析设计的专家型LLM，展示了其在特定任务中的应用和效果，因此归类为LLM应用。` `二进制分析`

> ReCopilot: Reverse Engineering Copilot in Binary Analysis

# 摘要

> 二进制分析是恶意软件检测和漏洞发现等安全领域的关键环节，但目前仍面临耗时费力且高度依赖专家知识的挑战。通用型大语言模型（LLMs）在源代码分析方面表现出色，而专门针对二进制文件的LLMs研究却相对较少。本文推出了ReCopilot——一款专为二进制分析设计的专家型LLM。ReCopilot通过精心构建的数据集整合二进制代码知识，涵盖持续预训练（CPT）、监督微调（SFT）和直接偏好优化（DPO）等阶段。它利用变量数据流和调用图增强上下文感知能力，并采用测试时缩放提升推理能力。在全面的二进制分析基准测试中，ReCopilot在反编译伪代码上的函数名称恢复和变量类型推断等任务中达到了最先进水平，相较于现有工具和LLMs提升了13%。我们的研究结果凸显了领域特定训练和上下文增强的有效性，同时也揭示了构建超长链式推理过程所面临的挑战。ReCopilot标志着在二进制分析领域迈向自动化的重大进展，为该领域提供了可解释且可扩展的AI辅助工具。


> Binary analysis plays a pivotal role in security domains such as malware detection and vulnerability discovery, yet it remains labor-intensive and heavily reliant on expert knowledge. General-purpose large language models (LLMs) perform well in programming analysis on source code, while binaryspecific LLMs are underexplored. In this work, we present ReCopilot, an expert LLM designed for binary analysis tasks. ReCopilot integrates binary code knowledge through a meticulously constructed dataset, encompassing continue pretraining (CPT), supervised fine-tuning (SFT), and direct preference optimization (DPO) stages. It leverages variable data flow and call graph to enhance context awareness and employs test-time scaling to improve reasoning capabilities. Evaluations on a comprehensive binary analysis benchmark demonstrate that ReCopilot achieves state-of-the-art performance in tasks such as function name recovery and variable type inference on the decompiled pseudo code, outperforming both existing tools and LLMs by 13%. Our findings highlight the effectiveness of domain-specific training and context enhancement, while also revealing challenges in building super long chain-of-thought. ReCopilot represents a significant step toward automating binary analysis with interpretable and scalable AI assistance in this domain.

[Arxiv](https://arxiv.org/abs/2505.16366)