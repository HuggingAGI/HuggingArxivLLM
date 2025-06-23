# 剖析SWE-Bench排行榜：分析基于LLM和智能体的修复系统提交者及其架构

发布时间：2025年06月20日

`LLM应用` `软件工程` `人工智能`

> Dissecting the SWE-Bench Leaderboards: Profiling Submitters and Architectures of LLM- and Agent-Based Repair Systems

# 摘要

> 自动化程序修复（APR）的快速发展主要得益于 AI 技术的突破性进展，尤其是大型语言模型（LLMs）和基于智能体的系统。SWE-Bench 是一个近期推出的基准测试，旨在通过从 12 个流行的开源 Python 仓库中提取的真实问题和拉取请求，评估基于 LLM 的修复系统。其公开的排行榜 SWE-Bench Lite 和 SWE-Bench Verified 已经成为跟踪进展和比较解决方案的核心平台。然而，由于提交流程不要求详细文档，许多解决方案的架构设计和来源仍然不明。本文中，我们首次对 SWE-Bench Lite（68 项提交）和 Verified（79 项提交）排行榜的所有提交进行了全面研究，分析了 67 种独特的修复方法，涵盖了提交者类型、产品可用性、LLM 使用情况和系统架构等多个维度。我们的研究发现，专有 LLM（尤其是 Claude 3.5/3.7）占据主导地位，同时存在智能体和非智能体两种设计模式，贡献者群体则涵盖了从个人开发者到大型科技公司。

> The rapid progress in Automated Program Repair (APR) has been driven by advances in AI, particularly large language models (LLMs) and agent-based systems. SWE-Bench is a recent benchmark designed to evaluate LLM-based repair systems using real issues and pull requests mined from 12 popular open-source Python repositories. Its public leaderboards, SWE-Bench Lite and SWE-Bench Verified, have become central platforms for tracking progress and comparing solutions. However, because the submission process does not require detailed documentation, the architectural design and origin of many solutions remain unclear. In this paper, we present the first comprehensive study of all submissions to the SWE-Bench Lite (68 entries) and Verified (79 entries) leaderboards, analyzing 67 unique approaches across dimensions such as submitter type, product availability, LLM usage, and system architecture. Our findings reveal the dominance of proprietary LLMs (especially Claude 3.5/3.7), the presence of both agentic and non-agentic designs, and a contributor base spanning from individual developers to large tech companies.

[Arxiv](https://arxiv.org/abs/2506.17208)