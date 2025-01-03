# VisionCoder：混合LLMs驱动的多智能体图像处理自动编程

发布时间：2024年10月24日

`Agent

理由：这篇论文提出了一种多智能体框架，结合了GPT-4和本地开源模型，协同完成自动编程任务。每个智能体在软件开发周期中扮演独特角色，形成一个虚拟组织，共同生产软件产品。这种多智能体协作的方式明显属于Agent领域的研究和应用。` `软件开发` `图像处理`

> VisionCoder: Empowering Multi-Agent Auto-Programming for Image Processing with Hybrid LLMs

# 摘要

> 在自动化编程领域，大型语言模型（LLMs）在详细任务描述下展现了强大的生成能力。然而，其功能目前主要局限于函数级开发，难以应对复杂项目环境和特定应用场景，如复杂的图像处理任务。本文提出了一种多智能体框架，结合了GPT-4o和本地开源模型，协同完成自动编程任务。每个智能体在软件开发周期中扮演独特角色，形成一个虚拟组织，共同生产软件产品。通过在项目、模块和函数级别建立树状结构的思维分布和开发机制，该框架为代码生成提供了高效且经济的解决方案。我们使用基准数据集进行评估，实验结果表明，VisionCoder在图像处理自动编程任务中显著优于现有方法。

> In the field of automated programming, large language models (LLMs) have demonstrated foundational generative capabilities when given detailed task descriptions. However, their current functionalities are primarily limited to function-level development, restricting their effectiveness in complex project environments and specific application scenarios, such as complicated image-processing tasks. This paper presents a multi-agent framework that utilises a hybrid set of LLMs, including GPT-4o and locally deployed open-source models, which collaboratively complete auto-programming tasks. Each agent plays a distinct role in the software development cycle, collectively forming a virtual organisation that works together to produce software products. By establishing a tree-structured thought distribution and development mechanism across project, module, and function levels, this framework offers a cost-effective and efficient solution for code generation. We evaluated our approach using benchmark datasets, and the experimental results demonstrate that VisionCoder significantly outperforms existing methods in image processing auto-programming tasks.

[Arxiv](https://arxiv.org/abs/2410.19245)