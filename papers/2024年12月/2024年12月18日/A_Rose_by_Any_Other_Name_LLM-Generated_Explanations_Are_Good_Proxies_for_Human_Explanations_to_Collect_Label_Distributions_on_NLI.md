# 无论叫什么名字的玫瑰：LLM 生成的解释可作为收集 NLI 标签分布的人类解释的优质替代品。

发布时间：2024年12月18日

`LLM应用`

> A Rose by Any Other Name: LLM-Generated Explanations Are Good Proxies for Human Explanations to Collect Label Distributions on NLI

# 摘要

> 人类标注存在分歧的情况屡见不鲜，这能在人类判断分布（HJDs）中体现。近期研究表明，解释为理解人类标签变异（HLV）提供了宝贵信息，大型语言模型（LLMs）能从少量人类提供的标签-解释对中近似得出 HJD。不过，为每个标签收集解释仍颇为耗时。本文探讨能否用 LLMs 替代人类生成解释以逼近 HJD。具体而言，我们让 LLMs 充当标注员，为少数给定的人类标签生成模型解释。我们测试了获取和整合这些标签-解释的方式，旨在近似人类判断分布。我们还进一步比较了由此产生的人类和模型生成的解释，并测试了自动和人工解释选择。我们的实验表明，LLM 解释在 NLI 方面颇具潜力：为估计 HJD，在提供人类标签的情况下，生成的解释与人类的结果相当。重要的是，我们的结果从有人类解释的数据集推广到了 i）无人类解释的数据集和 ii）具有挑战性的分布外测试集。

> Disagreement in human labeling is ubiquitous, and can be captured in human judgment distributions (HJDs). Recent research has shown that explanations provide valuable information for understanding human label variation (HLV) and large language models (LLMs) can approximate HJD from a few human-provided label-explanation pairs. However, collecting explanations for every label is still time-consuming. This paper examines whether LLMs can be used to replace humans in generating explanations for approximating HJD. Specifically, we use LLMs as annotators to generate model explanations for a few given human labels. We test ways to obtain and combine these label-explanations with the goal to approximate human judgment distribution. We further compare the resulting human with model-generated explanations, and test automatic and human explanation selection. Our experiments show that LLM explanations are promising for NLI: to estimate HJD, generated explanations yield comparable results to human's when provided with human labels. Importantly, our results generalize from datasets with human explanations to i) datasets where they are not available and ii) challenging out-of-distribution test sets.

[Arxiv](https://arxiv.org/abs/2412.13942)