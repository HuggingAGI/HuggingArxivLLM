# 通过静态代码分析提升大型语言模型的代码质量

发布时间：2025年06月11日

`LLM应用` `软件工程` `软件开发`

> Augmenting Large Language Models with Static Code Analysis for Automated Code Quality Improvements

# 摘要

> 本研究将 OpenAI 的 GPT-3.5 Turbo 和 GPT-4 等大型语言模型（LLMs）融入软件开发流程，重点研究代码问题检测与自动化修复。通过静态代码分析框架，我们能够在大规模软件项目中精准识别漏洞、代码异味等问题。提取并整理问题详情后，利用 LLM 实现自动化修复。迭代式提示工程确保提示结构生成符合项目需求的准确输出。检索增强生成（RAG）技术的引入，提升了修复的精准度，使 LLM 能够实时整合外部知识。为解决 LLM 幻觉问题，我们开发了“代码比较应用”，用于识别并修正错误变更。后续扫描结果显示，代码问题显著减少，证明了结合 LLM、静态分析与 RAG 技术在提升代码质量、优化开发流程以及节省资源方面的显著效果。

> This study examined code issue detection and revision automation by integrating Large Language Models (LLMs) such as OpenAI's GPT-3.5 Turbo and GPT-4o into software development workflows. A static code analysis framework detects issues such as bugs, vulnerabilities, and code smells within a large-scale software project. Detailed information on each issue was extracted and organized to facilitate automated code revision using LLMs. An iterative prompt engineering process is applied to ensure that prompts are structured to produce accurate and organized outputs aligned with the project requirements. Retrieval-augmented generation (RAG) is implemented to enhance the relevance and precision of the revisions, enabling LLM to access and integrate real-time external knowledge. The issue of LLM hallucinations - where the model generates plausible but incorrect outputs - is addressed by a custom-built "Code Comparison App," which identifies and corrects erroneous changes before applying them to the codebase. Subsequent scans using the static code analysis framework revealed a significant reduction in code issues, demonstrating the effectiveness of combining LLMs, static analysis, and RAG to improve code quality, streamline the software development process, and reduce time and resource expenditure.

[Arxiv](https://arxiv.org/abs/2506.10330)