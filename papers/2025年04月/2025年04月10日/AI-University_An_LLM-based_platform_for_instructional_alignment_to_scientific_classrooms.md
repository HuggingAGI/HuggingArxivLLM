# AI大学：基于大型语言模型的科学课堂教学对齐平台

发布时间：2025年04月10日

`LLM应用

理由：这篇论文主要探讨了大型语言模型（LLM）在教育领域的应用，特别是通过RAG技术微调LLM以适应特定教学风格，构建课程内容交付框架。虽然RAG技术是实现手段，但核心目标是教育应用，因此归类为LLM应用。` `高等教育`

> AI-University: An LLM-based platform for instructional alignment to scientific classrooms

# 摘要

> 我们推出了AI大学（AI-U），一个灵活的AI驱动课程内容交付框架，能够适应不同教师的教学风格。其核心是通过检索增强生成（RAG）技术，微调大型语言模型（LLM），使其能够根据讲座视频、笔记和教科书生成与教师风格一致的响应。以研究生级别的有限元方法（FEM）课程为例，我们构建了一个可扩展的管道，系统性地完成训练数据构建、开源LLM的微调（采用低秩适应LoRA技术）以及基于RAG的响应优化。通过结合余弦相似度、LLM评估和专家评审的综合评估，结果表明生成内容与课程材料高度一致。此外，我们开发了一个原型网络应用（访问地址：https://my-ai-university.com），通过将AI生成的响应与相关课程材料的具体部分和开源视频讲座的时间戳实例链接，显著提升了内容的可追溯性。实验数据显示，我们的专家模型在86%的测试用例中表现出更高的余弦相似度。一位LLM评委也指出，相比基础Llama 3.2模型，我们的专家模型在五次评估中有四次表现更优。AI-U为AI辅助教育提供了一个可扩展的解决方案，为在高等教育中的广泛应用奠定了基础。目前，我们的框架是在有限元方法（FEM）课程的背景下提出的——这一主题是工程科学领域博士和硕士学生培训的核心。然而，这种设置只是一个更广泛背景的具体实例：微调LLM以适应科学领域的研究内容。

> We introduce AI University (AI-U), a flexible framework for AI-driven course content delivery that adapts to instructors' teaching styles. At its core, AI-U fine-tunes a large language model (LLM) with retrieval-augmented generation (RAG) to generate instructor-aligned responses from lecture videos, notes, and textbooks. Using a graduate-level finite-element-method (FEM) course as a case study, we present a scalable pipeline to systematically construct training data, fine-tune an open-source LLM with Low-Rank Adaptation (LoRA), and optimize its responses through RAG-based synthesis. Our evaluation - combining cosine similarity, LLM-based assessment, and expert review - demonstrates strong alignment with course materials. We also have developed a prototype web application, available at https://my-ai-university.com, that enhances traceability by linking AI-generated responses to specific sections of the relevant course material and time-stamped instances of the open-access video lectures. Our expert model is found to have greater cosine similarity with a reference on 86% of test cases. An LLM judge also found our expert model to outperform the base Llama 3.2 model approximately four times out of five. AI-U offers a scalable approach to AI-assisted education, paving the way for broader adoption in higher education. Here, our framework has been presented in the setting of a class on FEM - a subject that is central to training PhD and Master students in engineering science. However, this setting is a particular instance of a broader context: fine-tuning LLMs to research content in science.

[Arxiv](https://arxiv.org/abs/2504.08846)