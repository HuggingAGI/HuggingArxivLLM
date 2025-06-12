# # UTBoost: 在 SWE-Bench 基准上对代码生成智能体进行严谨评估

发布时间：2025年06月10日

`LLM应用` `软件开发` `软件工程`

> UTBoost: Rigorous Evaluation of Coding Agents on SWE-Bench

# 摘要

> 大型语言模型的出现推动了编码代理的发展，这些代理能够生成现实世界的代码。作为评估这些代理能力的基准，SWE-Bench基于GitHub问题和拉取请求构建，但其中的手动测试用例往往不够充分，导致生成的补丁通过测试却未能真正解决问题。为了解决这一难题，我们开发了UTGenerator，一个基于LLM的测试用例生成器，能够自动分析代码库和依赖项，为Python项目生成测试用例。在此基础上，我们提出了UTBoost，一个全面的测试用例增强框架。在我们的评估中，我们识别出36个测试用例不足的任务实例，并在SWE Bench中发现了345个错误的补丁。这些修正影响了SWE-Bench Lite的40.9%和SWE-Bench Verified排行榜的24.4%，分别导致了18和11个排名的变化。

> The advent of Large Language Models (LLMs) has spurred the development of coding agents for real-world code generation. As a widely used benchmark for evaluating the code generation capabilities of these agents, SWE-Bench uses real-world problems based on GitHub issues and their corresponding pull requests. However, the manually written test cases included in these pull requests are often insufficient, allowing generated patches to pass the tests without resolving the underlying issue. To address this challenge, we introduce UTGenerator, an LLM-driven test case generator that automatically analyzes codebases and dependencies to generate test cases for real-world Python projects. Building on UTGenerator, we propose UTBoost, a comprehensive framework for test case augmentation. In our evaluation, we identified 36 task instances with insufficient test cases and uncovered 345 erroneous patches incorrectly labeled as passed in the original SWE Bench. These corrections, impacting 40.9% of SWE-Bench Lite and 24.4% of SWE-Bench Verified leaderboard entries, yield 18 and 11 ranking changes, respectively.

[Arxiv](https://arxiv.org/abs/2506.09289)