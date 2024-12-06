# Bench-CoE：一个用于基准领域专家协作的框架

发布时间：2024年12月05日

`LLM应用` `智能系统` `多模态任务`

> Bench-CoE: a Framework for Collaboration of Experts from Benchmark

# 摘要

> 大型语言模型（LLMs）是驱动智能系统处理多项任务的关键技术。为满足各类任务的需求，越来越多能力各异、由 LLMs 驱动的专家被开发出来，同时也有相应的基准用于评估其性能。本文提出了 Bench-CoE 框架，它能通过有效利用基准评估实现专家协作（CoE），从而在各类任务中取得最优性能。Bench-CoE 涵盖了一组专家模型、一个为相应专家分配任务的路由器，以及用于训练路由器的基准数据集。此外，我们基于此框架制定了查询级别和主题级别的方法，并分析了这两种方法的优劣。最后，我们在语言和多模态任务上开展了一系列不同数据分布的实验，以证实我们提出的 Bench-CoE 在整体性能上优于任何单个模型。我们期望该方法能成为此领域进一步研究的基准。代码可在 url{https://github.com/ZhangXJ199/Bench-CoE}获取。

> Large Language Models (LLMs) are key technologies driving intelligent systems to handle multiple tasks. To meet the demands of various tasks, an increasing number of LLMs-driven experts with diverse capabilities have been developed, accompanied by corresponding benchmarks to evaluate their performance. This paper proposes the Bench-CoE framework, which enables Collaboration of Experts (CoE) by effectively leveraging benchmark evaluations to achieve optimal performance across various tasks. Bench-CoE includes a set of expert models, a router for assigning tasks to corresponding experts, and a benchmark dataset for training the router. Moreover, we formulate Query-Level and Subject-Level approaches based on our framework, and analyze the merits and drawbacks of these two approaches. Finally, we conduct a series of experiments with vary data distributions on both language and multimodal tasks to validate that our proposed Bench-CoE outperforms any single model in terms of overall performance. We hope this method serves as a baseline for further research in this area. The code is available at url{https://github.com/ZhangXJ199/Bench-CoE}.

[Arxiv](https://arxiv.org/abs/2412.04167)