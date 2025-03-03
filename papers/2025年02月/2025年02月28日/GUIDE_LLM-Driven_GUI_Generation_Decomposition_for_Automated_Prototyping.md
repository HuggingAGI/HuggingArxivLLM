# 指南：LLM驱动的GUI生成分解实现自动化原型设计

发布时间：2025年02月28日

`LLM应用` `GUI原型设计` `软件开发`

> GUIDE: LLM-Driven GUI Generation Decomposition for Automated Prototyping

# 摘要

> GUI原型设计是提升需求提取和促进客户需求可视化与细化的宝贵技术。虽然它对软件开发流程有积极影响，但也需要巨大的努力和资源投入。大型语言模型（LLMs）凭借其出色的代码生成能力，为自动化GUI原型设计提供了新思路。然而，尽管LLMs潜力巨大，当前基于LLM的原型设计解决方案与传统基于用户的GUI原型设计方法之间仍存在差距。传统方法提供GUI原型的可视化表示和直接编辑功能，而LLMs及相关生成方法仅生成文本序列或不可编辑的图像输出，缺乏上述两个方面，因此阻碍了对GUI原型设计的支持。此外，用户通常要求进行的小修改在直接使用LLMs时会导致整个GUI原型的低效再生。在本研究中，我们提出了GUIDE，这是一种全新的LLM驱动的GUI生成分解方法，无缝集成到流行的原型设计框架Figma中。我们的方法首先将高级GUI描述分解为细粒度的GUI需求，然后将其翻译为Material Design GUI原型，从而实现更高的可控性和更高效的更改适应。为了高效地进行基于提示的Material Design GUI原型生成，我们提出了一种检索增强生成方法来整合组件库。我们的初步评估表明，GUIDE在弥合LLM生成能力和传统GUI原型设计工作流之间的差距方面是有效的，为LLM驱动的GUI原型设计提供了一种更有效且受控的基于用户的方法。视频链接：https://youtu.be/C9RbhMxqpTU

> GUI prototyping serves as one of the most valuable techniques for enhancing the elicitation of requirements and facilitating the visualization and refinement of customer needs. While GUI prototyping has a positive impact on the software development process, it simultaneously demands significant effort and resources. The emergence of Large Language Models (LLMs) with their impressive code generation capabilities offers a promising approach for automating GUI prototyping. Despite their potential, there is a gap between current LLM-based prototyping solutions and traditional user-based GUI prototyping approaches which provide visual representations of the GUI prototypes and direct editing functionality. In contrast, LLMs and related generative approaches merely produce text sequences or non-editable image output, which lacks both mentioned aspects and therefore impede supporting GUI prototyping. Moreover, minor changes requested by the user typically lead to an inefficient regeneration of the entire GUI prototype when using LLMs directly. In this work, we propose GUIDE, a novel LLM-driven GUI generation decomposition approach seamlessly integrated into the popular prototyping framework Figma. Our approach initially decomposes high-level GUI descriptions into fine-granular GUI requirements, which are subsequently translated into Material Design GUI prototypes, enabling higher controllability and more efficient adaption of changes. To efficiently conduct prompting-based generation of Material Design GUI prototypes, we propose a retrieval-augmented generation approach to integrate the component library. Our preliminary evaluation demonstrates the effectiveness of GUIDE in bridging the gap between LLM generation capabilities and traditional GUI prototyping workflows, offering a more effective and controlled user-based approach to LLM-driven GUI prototyping. Video: https://youtu.be/C9RbhMxqpTU

[Arxiv](https://arxiv.org/abs/2502.21068)