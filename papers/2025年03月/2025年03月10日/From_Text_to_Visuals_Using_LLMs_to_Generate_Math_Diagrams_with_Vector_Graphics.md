# 从文本到视觉：生成数学图表的矢量图形方法，利用 LLMs

发布时间：2025年03月10日

`LLM应用` `数学教育`

> From Text to Visuals: Using LLMs to Generate Math Diagrams with Vector Graphics

# 摘要

> 大型语言模型（LLMs）的进步为数学教育带来了新的可能性，通过自动化为教师和学生提供支持。虽然先前研究主要集中在生成数学问题和高质量干扰项上，但可视化在数学学习中的作用尚未得到充分探索。图表对数学思维和问题解决至关重要，但手动创建耗时且需要专业知识，限制了其可扩展性。利用LLMs生成可缩放矢量图形（SVG）的最新研究为自动化图表创建提供了新途径。与基于像素的图像不同，SVG使用XML表示几何图形，支持无缝缩放和适应。教育平台如Khan Academy和IXL已采用SVG展示数学问题和提示。本文探讨了通过中间SVG表示，利用LLMs自动生成与文本提示相关数学图表的可能性。我们聚焦于三个研究问题：（1）如何自动生成问题解决提示中的数学图表并评估其质量，（2）SVG是否是数学图表的有效中间表示，（3）LLMs生成准确SVG图表所需提示策略和格式是什么。我们的贡献包括定义了为数学提示自动生成SVG图表的任务，开发了一个基于LLM提示的管道，并确定了改进图表生成的关键策略。此外，我们引入了一个基于视觉问答的评估设置，并进行了消融研究以评估不同管道变体。通过自动化数学图表的创建，我们旨在为学生和教师提供准确且概念相关的视觉辅助工具，从而提升解决问题和学习体验。

> Advances in large language models (LLMs) offer new possibilities for enhancing math education by automating support for both teachers and students. While prior work has focused on generating math problems and high-quality distractors, the role of visualization in math learning remains under-explored. Diagrams are essential for mathematical thinking and problem-solving, yet manually creating them is time-consuming and requires domain-specific expertise, limiting scalability. Recent research on using LLMs to generate Scalable Vector Graphics (SVG) presents a promising approach to automating diagram creation. Unlike pixel-based images, SVGs represent geometric figures using XML, allowing seamless scaling and adaptability. Educational platforms such as Khan Academy and IXL already use SVGs to display math problems and hints. In this paper, we explore the use of LLMs to generate math-related diagrams that accompany textual hints via intermediate SVG representations. We address three research questions: (1) how to automatically generate math diagrams in problem-solving hints and evaluate their quality, (2) whether SVG is an effective intermediate representation for math diagrams, and (3) what prompting strategies and formats are required for LLMs to generate accurate SVG-based diagrams. Our contributions include defining the task of automatically generating SVG-based diagrams for math hints, developing an LLM prompting-based pipeline, and identifying key strategies for improving diagram generation. Additionally, we introduce a Visual Question Answering-based evaluation setup and conduct ablation studies to assess different pipeline variations. By automating the math diagram creation, we aim to provide students and teachers with accurate, conceptually relevant visual aids that enhance problem-solving and learning experiences.

[Arxiv](https://arxiv.org/abs/2503.07429)