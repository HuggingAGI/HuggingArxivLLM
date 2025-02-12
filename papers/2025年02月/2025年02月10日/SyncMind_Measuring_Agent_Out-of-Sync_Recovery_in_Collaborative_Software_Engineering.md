# SyncMind：评估协作软件工程中的代理同步恢复能力

发布时间：2025年02月10日

`LLM应用` `软件工程` `协作系统`

> SyncMind: Measuring Agent Out-of-Sync Recovery in Collaborative Software Engineering

# 摘要

> 软件工程 (SE) 正日益强调协作，开发者们共同在共享的复杂代码库上工作。在共享环境中实现有效协作需要参与者（无论是人类还是AI代理）随着环境的演变保持同步。当一个合作者的理解与当前状态出现偏差——我们称之为不同步挑战——其行动可能失败，导致整合问题。在这项研究中，我们提出了SyncMind框架，系统性地定义了协作软件工程 (CSE) 中大型语言模型 (LLM) 代理所面临的不同步问题。基于SyncMind，我们创建了SyncBench基准，其中包含24,332个来自21个流行GitHub仓库的真实CSE场景实例，这些场景涉及代理的不同步情况，并附带可执行的验证测试。通过SyncBench进行的实验揭示了现有LLM代理的能力和局限性。除了代理之间存在显著性能差距（从Llama-3.1代理的<=3.33%到Claude-3.5-Sonnet的>=28.18%）之外，它们始终较低的合作意愿（<=4.86%）表明现有LLM在CSE中存在根本性限制。然而，当协作发生时，它与不同步恢复的成功呈正相关。代理在资源感知的不同步恢复方面表现差异不大，进一步揭示了它们在资源意识和适应性方面的严重不足，为未来资源高效的协作系统提供了重要启示。代码和数据可在我们的项目网站公开获取：https://xhguo7.github.io/SyncMind/。

> Software engineering (SE) is increasingly collaborative, with developers working together on shared complex codebases. Effective collaboration in shared environments requires participants -- whether humans or AI agents -- to stay on the same page as their environment evolves. When a collaborator's understanding diverges from the current state -- what we term the out-of-sync challenge -- the collaborator's actions may fail, leading to integration issues. In this work, we introduce SyncMind, a framework that systematically defines the out-of-sync problem faced by large language model (LLM) agents in collaborative software engineering (CSE). Based on SyncMind, we create SyncBench, a benchmark featuring 24,332 instances of agent out-of-sync scenarios in real-world CSE derived from 21 popular GitHub repositories with executable verification tests. Experiments on SyncBench uncover critical insights into existing LLM agents' capabilities and limitations. Besides substantial performance gaps among agents (from Llama-3.1 agent <= 3.33% to Claude-3.5-Sonnet >= 28.18%), their consistently low collaboration willingness (<= 4.86%) suggests fundamental limitations of existing LLM in CSE. However, when collaboration occurs, it positively correlates with out-of-sync recovery success. Minimal performance differences in agents' resource-aware out-of-sync recoveries further reveal their significant lack of resource awareness and adaptability, shedding light on future resource-efficient collaborative systems. Code and data are openly available on our project website: https://xhguo7.github.io/SyncMind/.

[Arxiv](https://arxiv.org/abs/2502.06994)