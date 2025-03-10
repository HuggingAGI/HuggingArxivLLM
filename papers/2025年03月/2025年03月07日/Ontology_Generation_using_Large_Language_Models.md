# # 基于大型语言模型的本体生成方法

发布时间：2025年03月07日

`LLM应用

摘要中详细描述了如何将大型语言模型应用于生成OWL本体，这属于将LLM应用到特定任务中的实例，因此归类为LLM应用。` `本体工程` `语义网`

> Ontology Generation using Large Language Models

# 摘要

> 本体工程过程复杂且容易出错，即使是经验丰富的本体工程师也难以避免。本研究旨在探索大型语言模型（LLMs）从用户故事和能力问题（CQs）描述的本体需求中直接生成有效的OWL本体草稿的潜力。我们的主要贡献是介绍和评估两种新的自动化本体开发提示技术：Memoryless CQbyCQ和Ontogenia。我们还强调了三个结构评估标准的重要性，结合专家定性评估，突出了多维度评估的必要性，以捕捉生成本体的质量和可用性。我们的实验在包含十个本体、100个不同CQs和29个不同用户故事的基准数据集上进行，比较了三种LLMs在两种提示技术下的性能。结果显示，与当前基于LLM的本体工程最先进方法相比，我们的方法有所改进。具体而言，使用Ontogenia提示技术的OpenAI o1-preview模型生成的本体质量足以满足本体工程师的要求，在建模能力上显著优于新手本体工程师。然而，我们仍然注意到一些常见错误和结果质量的波动，这在使用LLMs进行本体创作支持时需要考虑。我们讨论了这些限制，并提出了未来研究的方向。

> The ontology engineering process is complex, time-consuming, and error-prone, even for experienced ontology engineers. In this work, we investigate the potential of Large Language Models (LLMs) to provide effective OWL ontology drafts directly from ontological requirements described using user stories and competency questions. Our main contribution is the presentation and evaluation of two new prompting techniques for automated ontology development: Memoryless CQbyCQ and Ontogenia. We also emphasize the importance of three structural criteria for ontology assessment, alongside expert qualitative evaluation, highlighting the need for a multi-dimensional evaluation in order to capture the quality and usability of the generated ontologies. Our experiments, conducted on a benchmark dataset of ten ontologies with 100 distinct CQs and 29 different user stories, compare the performance of three LLMs using the two prompting techniques. The results demonstrate improvements over the current state-of-the-art in LLM-supported ontology engineering. More specifically, the model OpenAI o1-preview with Ontogenia produces ontologies of sufficient quality to meet the requirements of ontology engineers, significantly outperforming novice ontology engineers in modelling ability. However, we still note some common mistakes and variability of result quality, which is important to take into account when using LLMs for ontology authoring support. We discuss these limitations and propose directions for future research.

[Arxiv](https://arxiv.org/abs/2503.05388)