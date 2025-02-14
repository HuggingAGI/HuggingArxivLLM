# # 从 PowerPoint UI 草图到 Web 应用  
## 基于模式驱动代码生成的 GIS 仪表盘开发：知识增强的大型语言模型、上下文感知的视觉提示与 React 框架的应用

发布时间：2025年02月12日

`LLM应用` `GIS`

> From PowerPoint UI Sketches to Web-Based Applications: Pattern-Driven Code Generation for GIS Dashboard Development Using Knowledge-Augmented LLMs, Context-Aware Visual Prompting, and the React Framework

# 摘要

> 开发基于网络的GIS应用（即CyberGIS仪表盘），用于环境研究中的GIS数据查询与可视化，通常需要投入重复且资源密集的努力。尽管生成式AI在代码生成方面具有自动化潜力，但其在处理复杂科学应用时仍面临挑战，主要体现在领域知识、软件工程原则和UI设计最佳实践的整合难度上。本文提出了一种知识增强的代码生成框架，该框架从专用知识库中检索软件工程最佳实践、领域专业知识和先进技术栈，以提升生成式预训练转换器（GPT）的前端开发能力。该框架能够根据用户在PowerPoint或Adobe Illustrator等工具中绘制的UI草图，自动创建基于GIS的Web应用（如仪表盘、界面）。一种新颖的情境感知视觉提示方法（用Python实现），可从这些草图中提取布局和界面特征，以指导代码生成。我们的方法借助大型语言模型（LLMs），通过整合结构化推理、软件工程原则和领域知识（灵感源自Chain-of-Thought（CoT）提示和检索增强生成（RAG）），生成前端代码。一个案例研究展示了该框架如何从用户绘制的草图生成一个模块化、可维护的Web平台，用于托管多个仪表盘，可视化环境和能源数据（如时间序列、形状文件、栅格）。通过采用知识驱动的方法，该框架利用设计模式（如Model-View-ViewModel（MVVM））和框架（如React）生成可扩展、符合行业标准的前端代码，从而大幅减少设计和编码的手动工作量，开创了一种自动化的高效方法，用于开发智慧城市软件。


> Developing web-based GIS applications, commonly known as CyberGIS dashboards, for querying and visualizing GIS data in environmental research often demands repetitive and resource-intensive efforts. While Generative AI offers automation potential for code generation, it struggles with complex scientific applications due to challenges in integrating domain knowledge, software engineering principles, and UI design best practices. This paper introduces a knowledge-augmented code generation framework that retrieves software engineering best practices, domain expertise, and advanced technology stacks from a specialized knowledge base to enhance Generative Pre-trained Transformers (GPT) for front-end development. The framework automates the creation of GIS-based web applications (e.g., dashboards, interfaces) from user-defined UI wireframes sketched in tools like PowerPoint or Adobe Illustrator. A novel Context-Aware Visual Prompting method, implemented in Python, extracts layouts and interface features from these wireframes to guide code generation. Our approach leverages Large Language Models (LLMs) to generate front-end code by integrating structured reasoning, software engineering principles, and domain knowledge, drawing inspiration from Chain-of-Thought (CoT) prompting and Retrieval-Augmented Generation (RAG). A case study demonstrates the framework's capability to generate a modular, maintainable web platform hosting multiple dashboards for visualizing environmental and energy data (e.g., time-series, shapefiles, rasters) from user-sketched wireframes. By employing a knowledge-driven approach, the framework produces scalable, industry-standard front-end code using design patterns such as Model-View-ViewModel (MVVM) and frameworks like React. This significantly reduces manual effort in design and coding, pioneering an automated and efficient method for developing smart city software.

[Arxiv](https://arxiv.org/abs/2502.08756)