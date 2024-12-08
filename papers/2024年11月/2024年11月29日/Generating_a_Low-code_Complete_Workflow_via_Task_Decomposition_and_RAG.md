# 借助任务分解和 RAG 来生成低代码的完整工作流

发布时间：2024年11月29日

`RAG` `软件工程` `人工智能`

> Generating a Low-code Complete Workflow via Task Decomposition and RAG

# 摘要

> AI 技术正迅速从研究迈向生产。随着能生成文本、图像和视频的基础模型（FMs）日益流行，基于 AI 的系统愈发复杂。相较于传统的基于 AI 的软件，运用 FMs 或基于生成式人工智能（GenAI）的系统因其规模和通用性，设计难度更大。这就需要记录最佳实践，即软件工程中的设计模式，以供整个 GenAI 应用使用。我们的首要贡献是将任务分解和检索增强生成（RAG）这两项技术形式化为基于 GenAI 系统的设计模式。我们从软件质量属性的角度探讨它们的权衡，并对替代方法加以评论。我们建议 AI 从业者不仅要从科学视角，还要从灵活性、可维护性、安全性和保密性等期望的工程特性的立场来考虑这些技术。作为第二项贡献，我们讲述了在行业中运用任务分解和 RAG 为企业用户构建复杂的现实世界 GenAI 应用——工作流生成的经验。生成工作流的任务需要依据系统环境的数据生成特定计划，以用户需求作为输入。由于这两种模式影响着整个 AI 开发周期，我们说明了它们如何对数据集创建、模型训练、模型评估和部署阶段产生影响。

> AI technologies are moving rapidly from research to production. With the popularity of Foundation Models (FMs) that generate text, images, and video, AI-based systems are increasing their complexity. Compared to traditional AI-based software, systems employing FMs, or GenAI-based systems, are more difficult to design due to their scale and versatility. This makes it necessary to document best practices, known as design patterns in software engineering, that can be used across GenAI applications. Our first contribution is to formalize two techniques, Task Decomposition and Retrieval-Augmented Generation (RAG), as design patterns for GenAI-based systems. We discuss their trade-offs in terms of software quality attributes and comment on alternative approaches. We recommend to AI practitioners to consider these techniques not only from a scientific perspective but also from the standpoint of desired engineering properties such as flexibility, maintainability, safety, and security. As a second contribution, we describe our industry experience applying Task Decomposition and RAG to build a complex real-world GenAI application for enterprise users: Workflow Generation. The task of generating workflows entails generating a specific plan using data from the system environment, taking as input a user requirement. As these two patterns affect the entire AI development cycle, we explain how they impacted the dataset creation, model training, model evaluation, and deployment phases.

[Arxiv](https://arxiv.org/abs/2412.00239)