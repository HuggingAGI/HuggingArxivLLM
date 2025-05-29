# RepoMaster：解决复杂任务的GitHub仓库自主探索与理解

发布时间：2025年05月27日

`LLM应用` `软件开发` `开源软件`

> RepoMaster: Autonomous Exploration and Understanding of GitHub Repositories for Complex Task Solving

# 摘要

> 代码代理的核心目标在于提升自主解决复杂任务的能力。尽管大型语言模型（LLMs）在代码生成领域取得了长足进步，但实际应用中往往需要完整的代码仓库支持，而非简单的脚本片段。从零开始构建这样的代码仓库仍面临巨大挑战。幸运的是，GitHub上拥有海量且不断更新的开源仓库资源，开发者常将其作为模块化组件用于复杂任务开发。然而，现有框架如OpenHands和SWE-Agent在有效利用这些资源方面仍显不足。仅依赖README文件提供的信息远远不够，深入分析发现，现有方法面临两大核心挑战：海量信息和复杂依赖关系，这些都受限于当前LLMs有限的上下文窗口。为解决这些问题，我们提出RepoMaster——一个专注于探索和复用GitHub仓库的自主代理框架，旨在更高效地解决复杂任务。RepoMaster通过构建函数调用图、模块依赖图和层级代码树，精准识别关键组件，并仅向LLMs提供核心模块，而非整个仓库。在自主执行过程中，RepoMaster借助我们的探索工具逐步查找相关组件，并通过信息修剪优化上下文使用效率。在调整后的MLE-bench基准测试中，RepoMaster的提交有效率比最强基线OpenHands提升了110%。在我们新发布的GitTaskBench基准测试中，RepoMaster将任务通过率从24.1%大幅提升至62.9%，同时将令牌使用量减少了95%。我们的代码和演示材料已公开发布在https://github.com/wanghuacan/RepoMaster。

> The ultimate goal of code agents is to solve complex tasks autonomously. Although large language models (LLMs) have made substantial progress in code generation, real-world tasks typically demand full-fledged code repositories rather than simple scripts. Building such repositories from scratch remains a major challenge. Fortunately, GitHub hosts a vast, evolving collection of open-source repositories, which developers frequently reuse as modular components for complex tasks. Yet, existing frameworks like OpenHands and SWE-Agent still struggle to effectively leverage these valuable resources. Relying solely on README files provides insufficient guidance, and deeper exploration reveals two core obstacles: overwhelming information and tangled dependencies of repositories, both constrained by the limited context windows of current LLMs. To tackle these issues, we propose RepoMaster, an autonomous agent framework designed to explore and reuse GitHub repositories for solving complex tasks. For efficient understanding, RepoMaster constructs function-call graphs, module-dependency graphs, and hierarchical code trees to identify essential components, providing only identified core elements to the LLMs rather than the entire repository. During autonomous execution, it progressively explores related components using our exploration tools and prunes information to optimize context usage. Evaluated on the adjusted MLE-bench, RepoMaster achieves a 110% relative boost in valid submissions over the strongest baseline OpenHands. On our newly released GitTaskBench, RepoMaster lifts the task-pass rate from 24.1% to 62.9% while reducing token usage by 95%. Our code and demonstration materials are publicly available at https://github.com/wanghuacan/RepoMaster.

[Arxiv](https://arxiv.org/abs/2505.21577)