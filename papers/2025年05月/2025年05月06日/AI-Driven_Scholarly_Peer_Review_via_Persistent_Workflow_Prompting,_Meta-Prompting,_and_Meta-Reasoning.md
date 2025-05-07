# # AI驱动的学术同行评审：通过持续工作流提示、元提示和元推理实现
AI-Driven Scholarly Peer Review via Persistent Workflow Prompting, Meta-Prompting, and Meta-Reasoning

发布时间：2025年05月06日

`LLM应用` `科学出版` `同行评审`

> AI-Driven Scholarly Peer Review via Persistent Workflow Prompting, Meta-Prompting, and Meta-Reasoning

# 摘要

> 科学手稿的同行评审对大型语言模型（LLMs）来说是一项重大挑战，这主要源于数据限制和专家推理的复杂性。本报告介绍了一种名为Persistent Workflow Prompting（PWP）的新型提示工程方法，旨在通过标准LLM聊天界面（无需编码，无需API调用）克服这一难题。我们开发了一个用于实验化学手稿批判性分析的PWP提示概念验证，该提示采用分层模块化架构（通过Markdown结构化），清晰定义了详细的工作流分析流程。通过迭代应用元提示技术和元推理，我们系统性地将专家评审工作流转化为规范化的操作，包括隐性知识的提取。该PWP提示只需在会话开始时提交一次，即可为LLM装备持续触发的工作流，指导现代推理型LLM完成系统化、多模式的评估。演示表明，PWP引导的LLM在测试案例中能够识别主要方法学缺陷，同时有效缓解LLM输入偏差，并执行多项复杂任务，包括区分主张与证据、整合文本/照片/图表分析以推断参数、执行定量可行性检查、比较估计与主张，以及评估先验合理性。为了确保透明度并促进研究复制，我们提供了完整的提示内容、详细的演示分析以及交互式聊天日志作为补充资源。除了在特定应用中的表现，这项工作还揭示了元开发过程本身的深刻见解，强调了PWP——通过详细工作流形式化指导——利用现成LLM实现复杂科学任务高级分析的潜力。


> Critical peer review of scientific manuscripts presents a significant challenge for Large Language Models (LLMs), partly due to data limitations and the complexity of expert reasoning. This report introduces Persistent Workflow Prompting (PWP), a potentially broadly applicable prompt engineering methodology designed to bridge this gap using standard LLM chat interfaces (zero-code, no APIs). We present a proof-of-concept PWP prompt for the critical analysis of experimental chemistry manuscripts, featuring a hierarchical, modular architecture (structured via Markdown) that defines detailed analysis workflows. We develop this PWP prompt through iterative application of meta-prompting techniques and meta-reasoning aimed at systematically codifying expert review workflows, including tacit knowledge. Submitted once at the start of a session, this PWP prompt equips the LLM with persistent workflows triggered by subsequent queries, guiding modern reasoning LLMs through systematic, multimodal evaluations. Demonstrations show the PWP-guided LLM identifying major methodological flaws in a test case while mitigating LLM input bias and performing complex tasks, including distinguishing claims from evidence, integrating text/photo/figure analysis to infer parameters, executing quantitative feasibility checks, comparing estimates against claims, and assessing a priori plausibility. To ensure transparency and facilitate replication, we provide full prompts, detailed demonstration analyses, and logs of interactive chats as supplementary resources. Beyond the specific application, this work offers insights into the meta-development process itself, highlighting the potential of PWP, informed by detailed workflow formalization, to enable sophisticated analysis using readily available LLMs for complex scientific tasks.

[Arxiv](https://arxiv.org/abs/2505.03332)