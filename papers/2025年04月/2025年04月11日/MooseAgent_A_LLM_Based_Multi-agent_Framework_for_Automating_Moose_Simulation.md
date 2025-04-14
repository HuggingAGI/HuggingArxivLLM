# MooseAgent：基于LLM的多智能体框架，实现Moose仿真的自动化

发布时间：2025年04月11日

`LLM应用` `科学计算`

> MooseAgent: A LLM Based Multi-agent Framework for Automating Moose Simulation

# 摘要

> 有限元方法（FEM）在工程和科学计算中广泛应用，但其预处理、求解器配置和后处理阶段往往耗时且需要专业知识。针对MOOSE多物理场仿真框架，我们提出了一种结合大规模预训练语言模型（LLMs）和多智能体系统的自动化解决方案框架——MooseAgent。该框架通过LLMs理解用户自然语言描述的仿真需求，并采用任务分解和多轮迭代验证策略，自动生成MOOSE输入文件。为提升精度并减少模型幻觉，系统构建并利用了包含标注MOOSE输入卡片和功能文档的向量数据库。我们在传热、力学、相场和多物理场耦合等多个典型案例中进行了实验评估，结果显示MooseAgent能够一定程度上实现MOOSE仿真流程的自动化，尤其在处理相对简单的单物理场问题时表现出色。本研究的主要贡献是提出了MOOSE的多智能体自动化框架，验证了其在简化有限元仿真流程和降低用户门槛方面的潜力，为智能有限元仿真软件的发展提供了新思路。MooseAgent框架代码已开源，可在GitHub仓库https://github.com/taozhan18/MooseAgent获取。

> The Finite Element Method (FEM) is widely used in engineering and scientific computing, but its pre-processing, solver configuration, and post-processing stages are often time-consuming and require specialized knowledge. This paper proposes an automated solution framework, MooseAgent, for the multi-physics simulation framework MOOSE, which combines large-scale pre-trained language models (LLMs) with a multi-agent system. The framework uses LLMs to understand user-described simulation requirements in natural language and employs task decomposition and multi-round iterative verification strategies to automatically generate MOOSE input files. To improve accuracy and reduce model hallucinations, the system builds and utilizes a vector database containing annotated MOOSE input cards and function documentation. We conducted experimental evaluations on several typical cases, including heat transfer, mechanics, phase field, and multi-physics coupling. The results show that MooseAgent can automate the MOOSE simulation process to a certain extent, especially demonstrating a high success rate when dealing with relatively simple single-physics problems. The main contribution of this research is the proposal of a multi-agent automated framework for MOOSE, which validates its potential in simplifying finite element simulation processes and lowering the user barrier, providing new ideas for the development of intelligent finite element simulation software. The code for the MooseAgent framework proposed in this paper has been open-sourced and is available at https://github.com/taozhan18/MooseAgent

[Arxiv](https://arxiv.org/abs/2504.08621)