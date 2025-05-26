# 大型语言模型中知识存储的参数专业化趋势

发布时间：2025年05月22日

`LLM理论` `人工智能` `机器学习`

> The Rise of Parameter Specialization for Knowledge Storage in Large Language Models

# 摘要

> 随着时间推移，越来越多的大型语言模型进入社区。研究者们致力于在有限参数规模下提升模型性能。然而，从微观层面来看，关于如何优化知识在模型参数中存储的研究较少，尤其是在多层感知器（MLP）中。本研究分析了二十个开源大型语言模型，探究其强劲性能与其知识存储方式的关系。研究发现，随着模型能力增强，其参数呈现更高专业化程度，MLP参数更专注于编码相似知识。实验表明，这种专业化分布提升了知识利用效率。因果实验进一步证实，这种知识分布对模型高效利用存储知识至关重要。

> Over time, a growing wave of large language models from various series has been introduced to the community. Researchers are striving to maximize the performance of language models with constrained parameter sizes. However, from a microscopic perspective, there has been limited research on how to better store knowledge in model parameters, particularly within MLPs, to enable more effective utilization of this knowledge by the model. In this work, we analyze twenty publicly available open-source large language models to investigate the relationship between their strong performance and the way knowledge is stored in their corresponding MLP parameters. Our findings reveal that as language models become more advanced and demonstrate stronger knowledge capabilities, their parameters exhibit increased specialization. Specifically, parameters in the MLPs tend to be more focused on encoding similar types of knowledge. We experimentally validate that this specialized distribution of knowledge contributes to improving the efficiency of knowledge utilization in these models. Furthermore, by conducting causal training experiments, we confirm that this specialized knowledge distribution plays a critical role in improving the model's efficiency in leveraging stored knowledge.

[Arxiv](https://arxiv.org/abs/2505.17260)