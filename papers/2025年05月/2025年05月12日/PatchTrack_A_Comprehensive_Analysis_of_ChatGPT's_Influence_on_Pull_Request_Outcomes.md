# PatchTrack：ChatGPT对拉取请求结果的全面影响分析

发布时间：2025年05月12日

`LLM应用` `软件开发` `协作工具`

> PatchTrack: A Comprehensive Analysis of ChatGPT's Influence on Pull Request Outcomes

# 摘要

> 大型语言模型（LLMs）如ChatGPT在软件开发中的广泛应用为开发者与AI的交互开辟了新途径，特别是在Pull Request工作流程中。尽管先前的研究已经探讨了AI生成代码的质量，但对于ChatGPT在实际Pull Request决策中的应用及其建议对补丁集成和拒绝的影响仍知之甚少。为了探究这些方面，我们分析了自我报告的ChatGPT使用情况（SACU），即开发者在Pull Request讨论中明确披露其对ChatGPT的依赖。我们的研究涵盖了255个GitHub仓库中的338个Pull Request（285个已合并，53个已关闭），其中包含645个ChatGPT生成的代码片段和3,486个补丁。我们引入了PatchTrack，一个分类工具，用于判断ChatGPT生成的补丁是否被应用（PA，115例）、未被应用（PN，64例）或未被建议（NE，106例）。我们的研究发现，完全采用ChatGPT生成代码的情况很少，开发者通常会修改或有选择地整合AI生成的补丁以符合项目约束，补丁的平均集成率为25%。通过定性分析，我们识别出影响补丁集成和Pull Request拒绝的关键因素，包括范围不符、可维护性担忧、冗余解决方案以及程序性障碍（如不完整的文档或行政政策）。本研究通过揭示ChatGPT在Pull Request工作流程中的实际作用，为开发者、维护者和教育工作者提供了实证见解，帮助他们了解生成式AI在协作软件开发中的演变应用。同时，这项研究也为未来优化AI辅助开发、提升AI采用的透明度以及改进补丁集成工作流程的研究奠定了基础。

> The rapid adoption of large language models (LLMs) like ChatGPT in software development has introduced new ways for developers to interact with AI, particularly in pull request workflows. While prior research has examined AI-generated code quality, there is limited understanding of how ChatGPT is utilized in real-world pull request decision-making and how its suggestions influence patch integration and rejection. To explore these aspects, we analyze self-admitted ChatGPT usage (SACU), where developers explicitly disclose their reliance on ChatGPT within pull request discussions. Our study examines 338 pull requests (285 merged, 53 closed) across 255 GitHub repositories, containing 645 ChatGPT-generated code snippets and 3,486 patches. We introduce PatchTrack, a classification tool that determines whether ChatGPT-generated patches were applied (PA, 115 cases), not applied (PN, 64 cases), or not suggested (NE, 106 cases). Our findings reveal that full adoption of ChatGPT-generated code is rare, developers frequently modify or selectively integrate AI-generated patches to align with project constraints, with a median integration rate of 25%. Through qualitative analysis, we identify key factors influencing patch integration and pull request rejection, including scope misalignment, maintainability concerns, redundant solutions, and procedural barriers such as incomplete documentation or administrative policies. By providing empirical insights into ChatGPT's role in pull request workflows, this study informs developers, maintainers, and educators on the evolving use of generative AI in collaborative software development. It also lays the groundwork for future research on optimizing AI-assisted development, improving transparency in AI adoption, and enhancing patch integration workflows.

[Arxiv](https://arxiv.org/abs/2505.07700)