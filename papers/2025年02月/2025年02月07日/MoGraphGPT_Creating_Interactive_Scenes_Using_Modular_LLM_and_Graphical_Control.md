# MoGraphGPT：利用模块化大语言模型与图形界面控制，轻松创建交互式场景

发布时间：2025年02月07日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLMs）在生成和优化互动场景代码中的应用，特别是通过模块化方法和图形界面来提高生成代码的质量和效率。它属于LLM在特定任务中的应用，因此归类为LLM应用。` `计算机图形学` `人机交互`

> MoGraphGPT: Creating Interactive Scenes Using Modular LLM and Graphical Control

# 摘要

> 互动场景的创建通常涉及复杂的编程工作。尽管像ChatGPT这样的大型语言模型（LLMs）能够从自然语言生成代码，但其输出往往容易出错，尤其在处理多个元素之间的交互时。线性对话结构限制了对单个元素的编辑能力，而缺乏图形化和精准控制则使视觉整合变得复杂。为了解决这些问题，我们引入了一种元素级模块化技术，通过独立的LLM模块处理单个元素的文本描述，并由中央模块管理元素间的交互。这种模块化方法使每个元素的独立优化成为可能。我们设计了一个名为MoGraphGPT的图形用户界面，它结合了模块化LLMs与增强的图形控制功能，用于生成2D互动场景代码。MoGraphGPT能够直接整合图形信息，并通过自动生成的滑块提供快速、精准的控制。我们的对比评估以AI编码工具Cursor Composer为基准系统，并通过可用性研究发现，MoGraphGPT在无需编写代码的情况下，显著提升了创建包含多个视觉元素的复杂2D互动场景的简易性、可控性和精致度。

> Creating interactive scenes often involves complex programming tasks. Although large language models (LLMs) like ChatGPT can generate code from natural language, their output is often error-prone, particularly when scripting interactions among multiple elements. The linear conversational structure limits the editing of individual elements, and lacking graphical and precise control complicates visual integration. To address these issues, we integrate an element-level modularization technique that processes textual descriptions for individual elements through separate LLM modules, with a central module managing interactions among elements. This modular approach allows for refining each element independently. We design a graphical user interface, MoGraphGPT , which combines modular LLMs with enhanced graphical control to generate codes for 2D interactive scenes. It enables direct integration of graphical information and offers quick, precise control through automatically generated sliders. Our comparative evaluation against an AI coding tool, Cursor Composer, as the baseline system and a usability study show MoGraphGPT significantly improves easiness, controllability, and refinement in creating complex 2D interactive scenes with multiple visual elements in a coding-free manner.

[Arxiv](https://arxiv.org/abs/2502.04983)