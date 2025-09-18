# CrowdAgent：多智能体管理的多源标注系统

发布时间：2025年09月17日

`Agent` `基础理论`

> CrowdAgent: Multi-Agent Managed Multi-Source Annotation System

# 摘要

> 高质量标注数据是现代自然语言处理（NLP）的核心基石。尽管近年来的方法已开始整合多样化标注来源——包括大型语言模型（LLMs）、小型语言模型（SLMs）与人类专家——但它们往往局限于标注环节本身。目前在动态管理这些来源所需的全流程控制上仍存在关键空白，难以统一解决复杂的调度与质量-成本权衡问题。受现实众包公司运作模式的启发，我们提出了CrowdAgent——一个通过整合任务分配、数据标注及质量/成本管理，实现端到端流程控制的多智能体系统。该系统采用创新方法实现任务的合理分配，让LLMs、SLMs与人类专家在协作标注流程中协同增效。我们通过在六个不同的多模态分类任务上开展广泛实验，验证了CrowdAgent的有效性。相关源代码和视频演示可访问https://github.com/QMMMS/CrowdAgent获取。

> High-quality annotated data is a cornerstone of modern Natural Language Processing (NLP). While recent methods begin to leverage diverse annotation sources-including Large Language Models (LLMs), Small Language Models (SLMs), and human experts-they often focus narrowly on the labeling step itself. A critical gap remains in the holistic process control required to manage these sources dynamically, addressing complex scheduling and quality-cost trade-offs in a unified manner. Inspired by real-world crowdsourcing companies, we introduce CrowdAgent, a multi-agent system that provides end-to-end process control by integrating task assignment, data annotation, and quality/cost management. It implements a novel methodology that rationally assigns tasks, enabling LLMs, SLMs, and human experts to advance synergistically in a collaborative annotation workflow. We demonstrate the effectiveness of CrowdAgent through extensive experiments on six diverse multimodal classification tasks. The source code and video demo are available at https://github.com/QMMMS/CrowdAgent.

[Arxiv](https://arxiv.org/abs/2509.14030)