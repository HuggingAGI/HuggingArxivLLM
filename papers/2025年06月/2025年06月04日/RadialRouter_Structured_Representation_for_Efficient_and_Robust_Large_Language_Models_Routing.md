# RadialRouter：一种高效稳健的大型语言模型路由结构化表示方法

发布时间：2025年06月04日

`LLM应用` `人工智能`

> RadialRouter: Structured Representation for Efficient and Robust Large Language Models Routing

# 摘要

> 大型语言模型（LLMs）的快速发展催生了路由技术，旨在从多样化的候选模型中高效选择最优LLM来处理特定任务，从而在优化性能的同时降低成本。然而，现有LLM路由方法的有效性受限，原因在于未能充分探索用户查询与LLM特性的内在联系。为解决这一问题，本文提出了RadialRouter——一种全新的LLM路由框架。RadialRouter采用一种名为RadialFormer的轻量级Transformer主干结构，用于表达查询与LLMs之间的关系。通过RadialFormer的最终状态，RadialRouter实现了最优LLM的选择。此外，该框架通过结合Kullback-Leibler散度与查询对比损失的客观函数，进一步优化了管道，以增强鲁棒性。实验结果表明，在RouterBench基准测试中，RadialRouter在平衡场景和成本优先场景下，分别比现有路由方法高出9.2%和5.8%。此外，其对不同性能-成本权衡的适应性以及对动态LLM池的支持，展现了其实际应用潜力。

> The rapid advancements in large language models (LLMs) have led to the emergence of routing techniques, which aim to efficiently select the optimal LLM from diverse candidates to tackle specific tasks, optimizing performance while reducing costs. Current LLM routing methods are limited in effectiveness due to insufficient exploration of the intrinsic connection between user queries and the characteristics of LLMs. To address this issue, in this paper, we present RadialRouter, a novel framework for LLM routing which employs a lightweight Transformer-based backbone with a radial structure named RadialFormer to articulate the query-LLMs relationship. The optimal LLM selection is performed based on the final states of RadialFormer. The pipeline is further refined by an objective function that combines Kullback-Leibler divergence with the query-query contrastive loss to enhance robustness. Experimental results on RouterBench show that RadialRouter significantly outperforms existing routing methods by 9.2\% and 5.8\% in the Balance and Cost First scenarios, respectively. Additionally, its adaptability toward different performance-cost trade-offs and the dynamic LLM pool demonstrates practical application potential.

[Arxiv](https://arxiv.org/abs/2506.03880)