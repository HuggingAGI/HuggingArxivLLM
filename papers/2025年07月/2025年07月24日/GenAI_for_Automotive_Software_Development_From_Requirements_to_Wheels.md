# # 生成式AI赋能汽车软件开发：从需求到量产

发布时间：2025年07月24日

`LLM应用

理由：论文讨论了大型语言模型在自动驾驶和ADAS功能开发中的应用，包括需求总结、测试场景生成和代码生成。虽然提到了RAG技术，但其主要焦点在于LLMs的应用。` `自动驾驶`

> GenAI for Automotive Software Development: From Requirements to Wheels

# 摘要

> 本文提出了一种基于生成式AI的汽车软件自动化开发方法，重点聚焦于自动驾驶和高级驾驶辅助系统（ADAS）功能的实现。整个过程始于需求分析，主要输出包括用于仿真环境的测试场景代码，以及针对连接测试台的车辆硬件平台实现期望的ADAS功能。此外，我们还引入了基于模型驱动工程（MDE）的需求一致性检查步骤。在本工作流中，大型语言模型（LLMs）被用于基于模型的需求总结（包括Ecore元模型、XMI模型实例和OCL约束创建）、测试场景生成、仿真代码（Python）以及目标平台代码生成（C++）。另外，我们采用检索增强生成（RAG）技术，从与自动驾驶法规相关的文档中增强测试场景生成。我们的方法旨在实现更短的合规和重构周期，同时缩短与ADAS功能相关的开发和测试时间。

> This paper introduces a GenAI-empowered approach to automated development of automotive software, with emphasis on autonomous and Advanced Driver Assistance Systems (ADAS) capabilities. The process starts with requirements as input, while the main generated outputs are test scenario code for simulation environment, together with implementation of desired ADAS capabilities targeting hardware platform of the vehicle connected to testbench. Moreover, we introduce additional steps for requirements consistency checking leveraging Model-Driven Engineering (MDE). In the proposed workflow, Large Language Models (LLMs) are used for model-based summarization of requirements (Ecore metamodel, XMI model instance and OCL constraint creation), test scenario generation, simulation code (Python) and target platform code generation (C++). Additionally, Retrieval Augmented Generation (RAG) is adopted to enhance test scenario generation from autonomous driving regulations-related documents. Our approach aims shorter compliance and re-engineering cycles, as well as reduced development and testing time when it comes to ADAS-related capabilities.

[Arxiv](https://arxiv.org/abs/2507.18223)