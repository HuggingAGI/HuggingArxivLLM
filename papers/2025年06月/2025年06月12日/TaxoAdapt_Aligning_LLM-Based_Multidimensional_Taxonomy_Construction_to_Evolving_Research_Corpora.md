# # TaxoAdapt：基于 LLM 的多维分类体系构建与动态研究语料库的匹配

发布时间：2025年06月12日

`LLM应用` `学术出版` `文献分类`

> TaxoAdapt: Aligning LLM-Based Multidimensional Taxonomy Construction to Evolving Research Corpora

# 摘要

> 科学领域的快速发展带来了文献整理与检索的挑战。传统上，专家编纂的分类体系曾有效应对这一需求，但该过程耗时且昂贵。此外，近期的自动分类体系构建方法要么（1）过度依赖特定语料库，牺牲了通用性，要么（2）严重依赖大型语言模型（LLMs）预训练数据中的常识，却忽视了科学领域不断演变的动态特性。同时，这些方法未能顾及科学文献的多维度特性，一篇研究论文可能涉及多个方面（如方法论、新任务、评估指标、基准测试）。为填补这些空白，我们提出了TaxoAdapt框架，它能够跨多维度动态调整基于LLM生成的分类体系以适应特定语料库。TaxoAdapt通过迭代分层分类，根据语料库的主题分布扩展分类体系的广度与深度。我们在多年来的计算机科学会议上展示了其最先进性能，证明了它在结构化呈现和捕捉科学领域演变方面的强大能力。作为一种多维度方法，TaxoAdapt生成的分类体系在粒度保留方面比最竞争的基线高出26.51%，在连贯性方面高出50.41%，且这一评估是由LLMs完成的。

> The rapid evolution of scientific fields introduces challenges in organizing and retrieving scientific literature. While expert-curated taxonomies have traditionally addressed this need, the process is time-consuming and expensive. Furthermore, recent automatic taxonomy construction methods either (1) over-rely on a specific corpus, sacrificing generalizability, or (2) depend heavily on the general knowledge of large language models (LLMs) contained within their pre-training datasets, often overlooking the dynamic nature of evolving scientific domains. Additionally, these approaches fail to account for the multi-faceted nature of scientific literature, where a single research paper may contribute to multiple dimensions (e.g., methodology, new tasks, evaluation metrics, benchmarks). To address these gaps, we propose TaxoAdapt, a framework that dynamically adapts an LLM-generated taxonomy to a given corpus across multiple dimensions. TaxoAdapt performs iterative hierarchical classification, expanding both the taxonomy width and depth based on corpus' topical distribution. We demonstrate its state-of-the-art performance across a diverse set of computer science conferences over the years to showcase its ability to structure and capture the evolution of scientific fields. As a multidimensional method, TaxoAdapt generates taxonomies that are 26.51% more granularity-preserving and 50.41% more coherent than the most competitive baselines judged by LLMs.

[Arxiv](https://arxiv.org/abs/2506.10737)