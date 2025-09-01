# Re4：科学计算智能体——具备重写、求解、审查与修订功能

发布时间：2025年08月28日

`Agent` `基础理论`

> Re4: Scientific Computing Agent with Rewriting, Resolution, Review and Revision

# 摘要

> 大型语言模型（LLMs）是生成式人工智能中一个活跃且前景广阔的领域，已展现出在数学、科学推理等多个领域处理复杂任务的能力。本研究构建了一个新颖的智能体框架，用于解决科学计算中的代表性问题。该智能体通过三个推理LLM（分别充当顾问、评审员和程序员）构建了“重写-求解-审查-修订”的逻辑链，并以协作交互的方式集成。顾问模块赋予智能体知识迁移能力，能将问题与专业领域见解关联，进而通过文本增强重写问题描述；程序员模块负责生成和执行结构良好的代码以实现问题求解；评审员模块则通过与代码运行输出的交互反馈，使智能体具备自调试和自优化能力。借助端到端审查机制，程序员生成的可执行代码得以迭代修订。我们全面评估了该框架在求解偏微分方程（PDEs）、病态线性系统及数据驱动物理分析问题上的性能：与单一模型相比，该协作框架显著提升了无bug代码生成率，减少了非物理解的出现，为基于自然语言描述的自主代码生成奠定了高可靠框架。审查机制还提高了最新推理模型的平均执行成功率（无bug代码且非NaN解）。总之，我们的智能体框架将自动代码生成与审查确立为一种极具前景的科学计算新范式。

> Large language models (LLMs) serve as an active and promising field of generative artificial intelligence and have demonstrated abilities to perform complex tasks in multiple domains, including mathematical and scientific reasoning. In this work, we construct a novel agent framework for solving representative problems in scientific computing. The proposed agent, incorporating a "rewriting-resolution-review-revision" logical chain via three reasoning LLMs (functioning as the Consultant, Reviewer, and Programmer, respectively), is integrated in a collaborative and interactive manner. The Consultant module endows the agent with knowledge transfer capabilities to link problems to professional domain insights, thereby rewriting problem descriptions through text augmentation. The Programmer module is responsible for generating and executing well-structured code to deliver the problem resolution. The Reviewer module equips the agent with the capacity for self-debugging and self-refinement through interactive feedback with code runtime outputs. By leveraging the end-to-end review mechanism, the executable code provided by the Programmer attains the iterative revision. A comprehensive evaluation is conducted on the performance of the proposed agent framework in solving PDEs, ill-conditioned linear systems, and data-driven physical analysis problems. Compared to single-model, this collaborative framework significantly improves the bug-free code generation rate and reduces the occurrence of non-physical solutions, thereby establishing a highly reliable framework for autonomous code generation based on natural language descriptions. The review mechanism improved the average execution success (bug-free code and non-NaN solutions) rate of the latest reasoning models. In summary, our agent framework establishes automatic code generation and review as a promising scientific computing paradigm.

[Arxiv](https://arxiv.org/abs/2508.20729)