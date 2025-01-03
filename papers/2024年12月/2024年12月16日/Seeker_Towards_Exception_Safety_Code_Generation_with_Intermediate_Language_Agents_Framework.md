# Seeker: 基于中间语言代理框架的异常安全代码生成

发布时间：2024年12月16日

`Agent

理由：这篇论文提出了一个名为Seeker的多代理框架，旨在利用大型语言模型（LLMs）来改进代码中的异常处理。Seeker通过多个代理（如Scanner、Detector、Predator、Ranker和Handler）协同工作，帮助LLMs更有效地检测、捕获和解决异常。这种多代理系统的设计和应用属于Agent领域的研究。` `软件开发` `代码可靠性`

> Seeker: Towards Exception Safety Code Generation with Intermediate Language Agents Framework

# 摘要

> 在软件开发中，异常处理的缺失或不当会严重影响代码的健壮性和可靠性。尽管异常处理机制要求开发者高标准地检测、捕获和管理异常，但许多开发者在这方面表现不佳，导致代码脆弱。这一问题在开源项目中尤为突出，影响了整个软件生态系统的质量。为应对这一挑战，我们探索利用大型语言模型（LLMs）来改进代码中的异常处理。通过深入分析，我们发现了三个关键问题：脆弱代码的检测不敏感、异常块的捕获不准确以及处理方案的扭曲。这些问题在现实代码库中普遍存在，表明健壮的异常处理实践常被忽视或处理不当。为此，我们提出了Seeker，一个受专家开发者策略启发的多代理框架。Seeker通过Scanner、Detector、Predator、Ranker和Handler等代理，帮助LLMs更有效地检测、捕获和解决异常。我们的研究首次系统性地探讨了如何利用LLMs提升实际开发中的异常处理实践，为未来代码可靠性的改进提供了重要见解。

> In real world software development, improper or missing exception handling can severely impact the robustness and reliability of code. Exception handling mechanisms require developers to detect, capture, and manage exceptions according to high standards, but many developers struggle with these tasks, leading to fragile code. This problem is particularly evident in open-source projects and impacts the overall quality of the software ecosystem. To address this challenge, we explore the use of large language models (LLMs) to improve exception handling in code. Through extensive analysis, we identify three key issues: Insensitive Detection of Fragile Code, Inaccurate Capture of Exception Block, and Distorted Handling Solution. These problems are widespread across real world repositories, suggesting that robust exception handling practices are often overlooked or mishandled. In response, we propose Seeker, a multi-agent framework inspired by expert developer strategies for exception handling. Seeker uses agents: Scanner, Detector, Predator, Ranker, and Handler to assist LLMs in detecting, capturing, and resolving exceptions more effectively. Our work is the first systematic study on leveraging LLMs to enhance exception handling practices in real development scenarios, providing valuable insights for future improvements in code reliability.

[Arxiv](https://arxiv.org/abs/2412.11713)