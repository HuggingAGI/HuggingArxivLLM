# PreGenie：一个专注于高质量视觉演示生成的智能框架

发布时间：2025年05月27日

`LLM应用` `演示文稿生成` `视觉内容生成`

> PreGenie: An Agentic Framework for High-quality Visual Presentation Generation

# 摘要

> 视觉呈现是有效沟通的关键。早期尝试利用深度学习自动制作视觉内容时，常面临布局杂乱、文本摘要不准以及图像理解不足等问题，导致图文不匹配。这些局限性限制了其在商业和科研等正式场景中的应用。为解决这些问题，我们提出了PreGenie——一个基于多模态大型语言模型（MLLMs）的智能模块化框架，专为生成高质量视觉呈现而设计。

PreGenie基于Slidev演示框架构建，通过Markdown代码生成幻灯片。其工作流程分为两个阶段：(1) 分析与初始生成，对多模态输入进行总结并生成初始代码；(2) 审查与重新生成，通过迭代审查中间代码和渲染后的幻灯片，最终生成高质量的演示文稿。每个阶段都集成了多个MLLMs进行协作和信息共享。实验结果表明，PreGenie在多模态理解方面表现卓越，无论是在美学设计还是内容一致性上都优于现有模型，同时更符合人类的设计偏好。


> Visual presentations are vital for effective communication. Early attempts to automate their creation using deep learning often faced issues such as poorly organized layouts, inaccurate text summarization, and a lack of image understanding, leading to mismatched visuals and text. These limitations restrict their application in formal contexts like business and scientific research. To address these challenges, we propose PreGenie, an agentic and modular framework powered by multimodal large language models (MLLMs) for generating high-quality visual presentations.
  PreGenie is built on the Slidev presentation framework, where slides are rendered from Markdown code. It operates in two stages: (1) Analysis and Initial Generation, which summarizes multimodal input and generates initial code, and (2) Review and Re-generation, which iteratively reviews intermediate code and rendered slides to produce final, high-quality presentations. Each stage leverages multiple MLLMs that collaborate and share information. Comprehensive experiments demonstrate that PreGenie excels in multimodal understanding, outperforming existing models in both aesthetics and content consistency, while aligning more closely with human design preferences.

[Arxiv](https://arxiv.org/abs/2505.21660)