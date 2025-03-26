# # 摘要  
Bugdar 采用先进的 AI 模型，结合代码上下文和安全知识库，自动检测代码中的漏洞和潜在安全问题，并提供修复建议。它通过在 GitHub 拉取请求中自动化安全审查流程，帮助开发团队在代码提交前识别并修复问题，从而显著提升代码质量和安全性。

发布时间：2025年03月21日

`LLM应用` `软件开发`

> Bugdar: AI-Augmented Secure Code Review for GitHub Pull Requests

# 摘要

> 在软件系统日益复杂的背景下，开发过程中的安全性保障面临严峻挑战。传统的手动代码审计不仅成本高昂、耗时费力，而且难以适应快速迭代的工作流程，而自动化工具常常因误报率过高而可靠性不足。针对这些问题，我们推出了Bugdar——一款与GitHub拉取请求无缝集成的AI增强型代码审查系统，提供近乎实时、语境感知的漏洞分析。Bugdar借助可微调的大型语言模型（LLMs）和检索增强生成（RAGs），为每个代码库量身定制切实可行的反馈，确保与项目独特需求及开发者习惯保持一致。支持Solidity、Move、Rust和Python等多种编程语言，Bugdar展现了卓越的效率，平均每处理一个拉取请求仅需56.4秒，或每秒处理30行代码。这相较于可能需要数小时手动审查的效率有了显著提升。通过促进主动安全编码方法，Bugdar减少了对人工审查的依赖，加速了开发周期，同时在不降低生产力的前提下，提升了软件系统的整体安全性。

> As software systems grow increasingly complex, ensuring security during development poses significant challenges. Traditional manual code audits are often expensive, time-intensive, and ill-suited for fast-paced workflows, while automated tools frequently suffer from high false-positive rates, limiting their reliability. To address these issues, we introduce Bugdar, an AI-augmented code review system that integrates seamlessly into GitHub pull requests, providing near real-time, context-aware vulnerability analysis. Bugdar leverages fine-tunable Large Language Models (LLMs) and Retrieval Augmented Generation (RAGs) to deliver project-specific, actionable feedback that aligns with each codebase's unique requirements and developer practices. Supporting multiple programming languages, including Solidity, Move, Rust, and Python, Bugdar demonstrates exceptional efficiency, processing an average of 56.4 seconds per pull request or 30 lines of code per second. This is significantly faster than manual reviews, which could take hours per pull request. By facilitating a proactive approach to secure coding, Bugdar reduces the reliance on manual reviews, accelerates development cycles, and enhances the security posture of software systems without compromising productivity.

[Arxiv](https://arxiv.org/abs/2503.17302)