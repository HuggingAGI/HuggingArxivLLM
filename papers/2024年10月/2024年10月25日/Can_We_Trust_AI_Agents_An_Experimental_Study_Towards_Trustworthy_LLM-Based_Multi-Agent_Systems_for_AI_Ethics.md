# 我们能否信任人工智能代理？ 这是一项针对基于可信 LLM 的多代理系统在人工智能伦理方面的实验研究

发布时间：2024年10月25日

`LLM应用` `AI 伦理` `软件开发`

> Can We Trust AI Agents? An Experimental Study Towards Trustworthy LLM-Based Multi-Agent Systems for AI Ethics

# 摘要

> AI 相关的系统，比如大型语言模型（LLMs），在支持各类任务的过程中影响了数百万人，但也面临着错误信息、偏见和滥用等问题。随着新技术和新问题不断涌现，合乎伦理的 AI 开发变得至关重要，然而客观且实用的伦理指导仍存在争议。本研究对开发合乎伦理的 AI 系统中的 LLMs 进行了考察，评估了增强可信度的技术对合乎伦理的 AI 输出生成的影响。运用设计科学研究（DSR）方法，我们明确了 LLM 可信度的相关技术：多智能体、不同角色、结构化通信以及多轮辩论。我们设计了多智能体原型 LLM-BMAS，其中的智能体针对来自 AI 事件数据库的现实世界中的伦理 AI 问题展开结构化讨论。通过主题分析、层次聚类、消融研究和源代码执行来评估该原型的性能。我们的系统每次运行能生成约 2000 行，而在消融研究中仅生成 80 行。讨论中出现了诸如偏差检测、透明度、问责制、用户同意、GDPR 合规、公平评估和欧盟 AI 法案合规等术语，这表明 LLM-BMAS 能够生成详尽的源代码和文档，解决那些常被忽视的伦理 AI 问题。不过，源代码集成和依赖管理方面的实际难题可能会限制从业者顺利采用该系统。本研究旨在阐明如何提升 LLMs 的可信度，以助力从业者开发基于伦理的 AI 系统。

> AI-based systems, including Large Language Models (LLMs), impact millions by supporting diverse tasks but face issues like misinformation, bias, and misuse. Ethical AI development is crucial as new technologies and concerns emerge, but objective, practical ethical guidance remains debated. This study examines LLMs in developing ethical AI systems, assessing how trustworthiness-enhancing techniques affect ethical AI output generation. Using the Design Science Research (DSR) method, we identify techniques for LLM trustworthiness: multi-agents, distinct roles, structured communication, and multiple rounds of debate. We design the multi-agent prototype LLM-BMAS, where agents engage in structured discussions on real-world ethical AI issues from the AI Incident Database. The prototype's performance is evaluated through thematic analysis, hierarchical clustering, ablation studies, and source code execution. Our system generates around 2,000 lines per run, compared to only 80 lines in the ablation study. Discussions reveal terms like bias detection, transparency, accountability, user consent, GDPR compliance, fairness evaluation, and EU AI Act compliance, showing LLM-BMAS's ability to generate thorough source code and documentation addressing often-overlooked ethical AI issues. However, practical challenges in source code integration and dependency management may limit smooth system adoption by practitioners. This study aims to shed light on enhancing trustworthiness in LLMs to support practitioners in developing ethical AI-based systems.

[Arxiv](https://arxiv.org/abs/2411.08881)