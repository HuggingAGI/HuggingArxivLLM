# 图在“说话”，可谁在听？——重新思考图-语言模型的评估方法

发布时间：2025年08月28日

`LLM理论` `基础理论`

> A Graph Talks, But Who's Listening? Rethinking Evaluations for Graph-Language Models

# 摘要

> 图语言模型（GLMs）的研发旨在融合图神经网络（GNNs）的结构推理能力与大型语言模型（LLMs）的语义理解能力。然而，我们研究发现，当前GLMs的评估基准多为节点级分类数据集的复用，难以有效评估多模态推理能力。分析显示，仅凭单模态信息就能在这些基准测试中表现优异，说明它们无需进行图-语言融合。为解决这一评估缺陷，我们提出了CLEGR（组合语言-图推理）基准，专门用于评估不同复杂度的多模态推理能力。该基准通过合成图生成流程构建，并设计了需要结合结构与文本语义进行联合推理的问题。我们对主流GLM架构展开深入评估，结果发现软提示大型语言模型基线的性能与集成完整GNN骨干的GLM不相上下。这一结果引发了对“将图结构融入LLMs是否具有架构必要性”的质疑。我们还发现，在需要结构推理的任务中，GLMs的性能显著下降。这些发现揭示了当前GLMs在图推理能力上的局限，同时为推动研究界向涉及图结构与语言的显式多模态推理方向发展奠定了基础。

> Developments in Graph-Language Models (GLMs) aim to integrate the structural reasoning capabilities of Graph Neural Networks (GNNs) with the semantic understanding of Large Language Models (LLMs). However, we demonstrate that current evaluation benchmarks for GLMs, which are primarily repurposed node-level classification datasets, are insufficient to assess multimodal reasoning. Our analysis reveals that strong performance on these benchmarks is achievable using unimodal information alone, suggesting that they do not necessitate graph-language integration. To address this evaluation gap, we introduce the CLEGR(Compositional Language-Graph Reasoning) benchmark, designed to evaluate multimodal reasoning at various complexity levels. Our benchmark employs a synthetic graph generation pipeline paired with questions that require joint reasoning over structure and textual semantics. We perform a thorough evaluation of representative GLM architectures and find that soft-prompted LLM baselines perform on par with GLMs that incorporate a full GNN backbone. This result calls into question the architectural necessity of incorporating graph structure into LLMs. We further show that GLMs exhibit significant performance degradation in tasks that require structural reasoning. These findings highlight limitations in the graph reasoning capabilities of current GLMs and provide a foundation for advancing the community toward explicit multimodal reasoning involving graph structure and language.

[Arxiv](https://arxiv.org/abs/2508.20583)