# # 如何应用缩放定律于知识图谱工程任务？模型规模对大型语言模型性能的影响

发布时间：2025年05月22日

`LLM应用` `知识图谱` `知识图谱工程`

> How do Scaling Laws Apply to Knowledge Graph Engineering Tasks? The Impact of Model Size on Large Language Model Performance

# 摘要

> 在使用大型语言模型 (LLMs) 支持知识图谱工程 (KGE) 时，模型规模是选择模型的重要考量。根据缩放定律，模型越大通常能力越强。然而，资源成本同样重要，因此需权衡性能与成本。LLM-KG-Bench 框架用于在 KGE 任务中比较 LLMs，并评估其理解和生成知识图谱及查询的能力。基于涵盖 26 个开源最先进 LLMs 的数据集，我们探索了 KGE 任务中的模型大小缩放定律。分析显示，除少数例外，缩放定律普遍适用。然而，在某些情况下，性能增长趋缓或停滞，此时较小模型更具成本效益。此外，同一模型家族中，有时较大模型表现不如较小模型，但这种情况仅在局部出现。因此，建议对同一家族的相邻大小模型进行额外测试。

> When using Large Language Models (LLMs) to support Knowledge Graph Engineering (KGE), one of the first indications when searching for an appropriate model is its size. According to the scaling laws, larger models typically show higher capabilities. However, in practice, resource costs are also an important factor and thus it makes sense to consider the ratio between model performance and costs. The LLM-KG-Bench framework enables the comparison of LLMs in the context of KGE tasks and assesses their capabilities of understanding and producing KGs and KG queries. Based on a dataset created in an LLM-KG-Bench run covering 26 open state-of-the-art LLMs, we explore the model size scaling laws specific to KGE tasks. In our analyses, we assess how benchmark scores evolve between different model size categories. Additionally, we inspect how the general score development of single models and families of models correlates to their size. Our analyses revealed that, with a few exceptions, the model size scaling laws generally also apply to the selected KGE tasks. However, in some cases, plateau or ceiling effects occurred, i.e., the task performance did not change much between a model and the next larger model. In these cases, smaller models could be considered to achieve high cost-effectiveness. Regarding models of the same family, sometimes larger models performed worse than smaller models of the same family. These effects occurred only locally. Hence it is advisable to additionally test the next smallest and largest model of the same family.

[Arxiv](https://arxiv.org/abs/2505.16276)