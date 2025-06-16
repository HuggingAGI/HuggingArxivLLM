# 自动提取与分析开源软件中的开发者意图

发布时间：2025年04月22日

`LLM应用` `开源软件` `软件工程`

> Automated Extraction and Analysis of Developer's Rationale in Open Source Software

# 摘要

> 开源软件的贡献者必须深刻理解项目的历史，以做出连贯且不与过往推理冲突的决策。然而，检查所有与拟议贡献相关的变更需要大量人工努力，而现有研究尚未提供一种自动化机制来揭示和分析这些冲突。本文提出了一种基于现有高级推理提取与管理架构Kantara的自动化推理分析方法。我们的实现结合了预训练模型和大型语言模型，并采用基于结构的机制，用于检测可能导致项目设计退化的推理冲突和问题。通过Linux内核项目的OOM-Killer模块，我们验证了提取和分析方法的可行性，并进一步研究了其在另外五个活跃开源项目中的适用性。结果表明，我们的自动化方法能够有效支持推理分析，发现有趣的关联，并检测潜在的冲突和推理问题。此外，我们展示了从决策和推理句子中进行自动提取的有效性，并展望了将其推广到其他开源项目的潜力。因此，这种自动化方法可帮助开源软件开发者主动解决隐藏问题，并确保新变更与过往决策保持一致。

> Contributors to open source software must deeply understand a project's history to make coherent decisions which do not conflict with past reasoning. However, inspecting all related changes to a proposed contribution requires intensive manual effort, and previous research has not yet produced an automated mechanism to expose and analyze these conflicts. In this article, we propose such an automated approach for rationale analyses, based on an instantiation of Kantara, an existing high-level rationale extraction and management architecture. Our implementation leverages pre-trained models and Large Language Models, and includes structure-based mechanisms to detect reasoning conflicts and problems which could cause design erosion in a project over time. We show the feasibility of our extraction and analysis approach using the OOM-Killer module of the Linux Kernel project, and investigate the approach's generalization to five other highly active open source projects. The results confirm that our automated approach can support rationale analyses with reasonable performance, by finding interesting relationships and to detect potential conflicts and reasoning problems. We also show the effectiveness of the automated extraction of decision and rationale sentences and the prospects for generalizing this to other open source projects. This automated approach could therefore be used by open source software developers to proactively address hidden issues and to ensure that new changes do not conflict with past decisions.

[Arxiv](https://arxiv.org/abs/2506.11005)