# # 标题 Trae 代理：基于 LLM 的软件工程代理，支持测试时扩展

发布时间：2025年07月31日

`Agent` `软件工程` `软件开发`

> Trae Agent: An LLM-based Agent for Software Engineering with Test-time Scaling

# 摘要

> 软件问题解决是软件工程中的重要挑战，近年来受到了广泛关注。随着大型语言模型（LLMs）的快速发展，我们在解决现实世界软件工程任务方面取得了显著进展。最近的研究引入了集成推理技术，以提升基于LLM的问题解决性能。然而，现有基于提示的方法仍面临两大挑战：无法有效探索大规模集成空间，且缺乏仓库级别的理解能力，这严重制约了它们的整体效果。在本文中，我们提出了Trae Agent——首个基于代理的集成推理方法，专为仓库级别问题解决而设计。Trae Agent将问题解决目标转化为最优解搜索问题，并通过生成、剪枝和选择的模块化代理，成功应对了大规模集成空间和仓库级别理解两大难题。我们在广泛采用的SWE-bench基准上，使用三个领先LLMs进行了全面实验，将Trae Agent与四种最新集成推理技术进行了对比。实验结果表明，Trae Agent在Pass@1指标上始终表现出色，比所有基线平均提升了10.22%。它在SWE-bench Verified排行榜上位居榜首，Pass@1分数高达75.20%。我们很高兴将Trae Agent作为开源项目发布，以支持研究社区，所有资源均可在https://github.com/bytedance/trae-agent获取。

> Software issue resolution is a critical challenge in software engineering and has garnered increasing attention in recent years. With the rapid advancement of large language models (LLMs), substantial progress has been made in addressing real-world software engineering tasks. Recent studies have introduced ensemble reasoning techniques to enhance the performance of LLM-based issue resolution. However, existing prompting-based methods still face limitations in effectively exploring large ensemble spaces and lack the capacity for repository-level understanding, both of which constrain their overall effectiveness. In this paper, we propose Trae Agent, the first agent-based ensemble reasoning approach for repository-level issue resolution. Trae Agent formulates our goal as an optimal solution search problem and addresses two key challenges, i.e., large ensemble spaces and repository-level understanding, through modular agents for generation, pruning, and selection. We conduct extensive experiments using three leading LLMs on the widely-adopted SWE-bench benchmark, comparing Trae Agent against four state-of-the-art ensemble reasoning techniques. Experimental results demonstrate that Trae Agent consistently achieves superior performance, with an average improvement of 10.22% over all baselines in terms of Pass@1. Trae Agent has achieved first place on the SWE-bench Verified leaderboard, with a notable Pass@1 score of 75.20%. We are pleased to release Trae Agent as an open-source project to support the research community, with all resources available at https://github.com/bytedance/trae-agent.

[Arxiv](https://arxiv.org/abs/2507.23370)