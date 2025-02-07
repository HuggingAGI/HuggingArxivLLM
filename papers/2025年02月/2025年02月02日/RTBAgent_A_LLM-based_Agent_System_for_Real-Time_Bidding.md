# RTBAgent: 基于LLM的实时竞价代理系统

发布时间：2025年02月02日

`Agent

这篇论文提出了一个基于大型语言模型（LLMs）的实时竞价代理系统（RTBAgent），并详细描述了其设计和实现。该系统通过LLMs获得推理能力，并结合其他辅助模块（如点击率估计模型、专家策略知识等）来优化竞价决策。论文的核心是构建一个智能代理系统，用于实时竞价环境中的决策优化，因此应归类为Agent。` `实时竞价`

> RTBAgent: A LLM-based Agent System for Real-Time Bidding

# 摘要

> # 实时竞价（RTB）让广告商能在瞬间对展示机会进行竞争性出价，力求在激烈的竞争环境中实现成本效益。尽管RTB已广泛受益于深度学习和强化学习等技术，但由于在线与离线环境的差异以及在线竞价的快速波动，相关方法的可靠性常常面临挑战。为此，我们提出了RTBAgent，这是首个基于大型语言模型（LLMs）的RTB代理系统，它同步了真实的广告竞价环境，并通过集成的决策过程获取竞价价格。具体来说，RTBAgent通过LLMs获得推理能力，并借助点击率估计模型、专家策略知识和每日反思等辅助模块，进一步定制为更适合RTB的专业系统。此外，我们设计了两步决策过程和多记忆检索机制，使RTBAgent能够回顾历史决策和交易记录，实时做出更适应市场变化的竞价决策。实证测试表明，RTBAgent显著提升了盈利能力。RTBAgent代码将公开访问：https://github.com/CaiLeng/RTBAgent。

> Real-Time Bidding (RTB) enables advertisers to place competitive bids on impression opportunities instantaneously, striving for cost-effectiveness in a highly competitive landscape. Although RTB has widely benefited from the utilization of technologies such as deep learning and reinforcement learning, the reliability of related methods often encounters challenges due to the discrepancies between online and offline environments and the rapid fluctuations of online bidding. To handle these challenges, RTBAgent is proposed as the first RTB agent system based on large language models (LLMs), which synchronizes real competitive advertising bidding environments and obtains bidding prices through an integrated decision-making process. Specifically, obtaining reasoning ability through LLMs, RTBAgent is further tailored to be more professional for RTB via involved auxiliary modules, i.e., click-through rate estimation model, expert strategy knowledge, and daily reflection. In addition, we propose a two-step decision-making process and multi-memory retrieval mechanism, which enables RTBAgent to review historical decisions and transaction records and subsequently make decisions more adaptive to market changes in real-time bidding. Empirical testing with real advertising datasets demonstrates that RTBAgent significantly enhances profitability. The RTBAgent code will be publicly accessible at: https://github.com/CaiLeng/RTBAgent.

[Arxiv](https://arxiv.org/abs/2502.00792)