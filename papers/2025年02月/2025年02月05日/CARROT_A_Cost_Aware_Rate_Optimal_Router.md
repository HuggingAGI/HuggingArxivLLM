# CARROT: 成本感知的速率最优路由器

发布时间：2025年02月05日

`LLM应用

理由：这篇论文主要讨论了如何通过成本感知的路由器（CARROT）来优化大型语言模型（LLMs）的使用，特别是在性能和成本之间进行权衡。这涉及到LLM在实际应用中的部署和优化，属于LLM应用的范畴。` `云计算`

> CARROT: A Cost Aware Rate Optimal Router

# 摘要

> 随着大型语言模型（LLMs）数量的激增，LLM路由——即将查询导向能提供合适响应的最经济LLM——引起了广泛关注。为此，我们推出了CARROT，一款成本感知速率最优路由器，它能根据性能与成本的任意权衡来挑选模型。面对查询，CARROT依据模型成本与性能的预估做出选择，其简洁设计确保了高效计算，理论分析更证实了其路由性能达到最小最大速率最优。此外，我们还推出了智能价格感知路由（SPROUT）数据集，旨在支持广泛查询场景下最新顶尖LLM的路由应用。借助SPROUT及Routerbench、open-LLM-leaderboard-v2等基准测试，我们实证了CARROT相较于多种替代路由器的卓越表现。

> With the rapid growth in the number of Large Language Models (LLMs), there has been a recent interest in LLM routing, or directing queries to the cheapest LLM that can deliver a suitable response. Following this line of work, we introduce CARROT, a Cost AwaRe Rate Optimal rouTer that can select models based on any desired trade-off between performance and cost. Given a query, CARROT selects a model based on estimates of models' cost and performance. Its simplicity lends CARROT computational efficiency, while our theoretical analysis demonstrates minimax rate-optimality in its routing performance. Alongside CARROT, we also introduce the Smart Price-aware Routing (SPROUT) dataset to facilitate routing on a wide spectrum of queries with the latest state-of-the-art LLMs. Using SPROUT and prior benchmarks such as Routerbench and open-LLM-leaderboard-v2 we empirically validate CARROT's performance against several alternative routers.

[Arxiv](https://arxiv.org/abs/2502.03261)