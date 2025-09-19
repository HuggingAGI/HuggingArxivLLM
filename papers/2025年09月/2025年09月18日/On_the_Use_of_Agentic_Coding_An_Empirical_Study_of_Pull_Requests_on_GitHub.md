# # 智能体编码的应用：GitHub拉取请求实证研究

发布时间：2025年09月18日

`Agent` `基础理论`

> On the Use of Agentic Coding: An Empirical Study of Pull Requests on GitHub

# 摘要

> 大型语言模型（LLMs）正日益融入软件开发流程。借助自主AI智能体，以最小人工干预生成代码并提交拉取请求的能力，正逐步成为标准实践。然而，这些拉取请求的实际效用以及其贡献在真实项目中的接受程度，目前尚不清楚。本文对157个不同开源项目中，由智能体编码工具Claude Code生成的567个GitHub拉取请求（PRs）展开实证研究。分析发现，开发人员常借助智能体处理重构、文档编写和测试等任务。结果显示，83.8%的智能体辅助PR最终被项目维护者接受并合并，其中54.9%的合并PR无需额外修改便直接集成。其余45.1%则需要额外修改，而人工修订对此类PR帮助显著，尤其是在错误修复、文档编写及遵循项目特定标准方面。这些发现表明，尽管智能体辅助PR总体上可被接受，但仍需人工监督与优化。

> Large language models (LLMs) are increasingly being integrated into software development processes. The ability to generate code and submit pull requests with minimal human intervention, through the use of autonomous AI agents, is poised to become a standard practice. However, little is known about the practical usefulness of these pull requests and the extent to which their contributions are accepted in real-world projects. In this paper, we empirically study 567 GitHub pull requests (PRs) generated using Claude Code, an agentic coding tool, across 157 diverse open-source projects. Our analysis reveals that developers tend to rely on agents for tasks such as refactoring, documentation, and testing. The results indicate that 83.8% of these agent-assisted PRs are eventually accepted and merged by project maintainers, with 54.9% of the merged PRs are integrated without further modification. The remaining 45.1% require additional changes benefit from human revisions, especially for bug fixes, documentation, and adherence to project-specific standards. These findings suggest that while agent-assisted PRs are largely acceptable, they still benefit from human oversight and refinement.

[Arxiv](https://arxiv.org/abs/2509.14745)