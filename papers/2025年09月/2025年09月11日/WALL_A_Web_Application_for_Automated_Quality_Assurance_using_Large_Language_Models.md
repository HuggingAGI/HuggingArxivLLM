# WALL：基于大型语言模型的自动化质量保证Web应用

发布时间：2025年09月11日

`LLM应用` `工业与制造`

> WALL: A Web Application for Automated Quality Assurance using Large Language Models

# 摘要

> 随着软件项目复杂度不断提升，代码文件中的问题数量和类型也显著增多。要应对这一挑战，亟需高效的问题检测、解决与评估工具。本文介绍了WALL——一款集成SonarQube与大型语言模型（如GPT-3.5 Turbo、GPT-4o）的Web应用，旨在实现这些任务的自动化。WALL包含三个核心模块：问题提取工具、代码问题修正器及代码比较工具。这些模块协同工作，形成了一条无缝流水线，可完成软件问题检测、自动化代码修订生成及修订准确性评估。我们在563个文件（含7599余个问题）上开展的实验显示，WALL能够在减少人工投入的同时确保修订质量。结果表明，将经济高效型与先进型LLMs相结合的混合策略能显著降低成本并提升修订效率。未来研究计划集成开源LLMs并消除人工干预，以进一步增强WALL的功能，为实现全自动化代码质量管理奠定基础。

> As software projects become increasingly complex, the volume and variety of issues in code files have grown substantially. Addressing this challenge requires efficient issue detection, resolution, and evaluation tools. This paper presents WALL, a web application that integrates SonarQube and large language models (LLMs) such as GPT-3.5 Turbo and GPT-4o to automate these tasks. WALL comprises three modules: an issue extraction tool, code issues reviser, and code comparison tool. Together, they enable a seamless pipeline for detecting software issues, generating automated code revisions, and evaluating the accuracy of revisions. Our experiments, conducted on 563 files with over 7,599 issues, demonstrate WALL's effectiveness in reducing human effort while maintaining high-quality revisions. Results show that employing a hybrid approach of cost-effective and advanced LLMs can significantly lower costs and improve revision rates. Future work aims to enhance WALL's capabilities by integrating open-source LLMs and eliminating human intervention, paving the way for fully automated code quality management.

[Arxiv](https://arxiv.org/abs/2509.09918)