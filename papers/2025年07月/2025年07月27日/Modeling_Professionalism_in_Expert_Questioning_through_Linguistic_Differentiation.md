# # 通过语言差异，建模专家提问中的专业性

发布时间：2025年07月27日

`LLM应用` `语言建模`

> Modeling Professionalism in Expert Questioning through Linguistic Differentiation

# 摘要

> 专业性：专家沟通的关键维度——以金融领域为例
本文探讨如何利用语言特征来建模和评估专家提问的专业性。我们引入了一个新的标注框架，用于量化金融分析师提问中的结构和语用元素，如 discourse regulators、prefaces 和 request types。利用人工撰写和大型语言模型（LLM）生成的问题，我们构建了两个数据集：一个标注了感知专业性，另一个标注了问题来源。我们发现，相同的语言特征与人类判断和作者身份有很强的相关性，表明存在共同的风格基础。此外，仅基于这些可解释特征训练的分类器在区分专家撰写的问题方面优于 gemini-2.0 和 SVM 基准。我们的研究结果表明，专业性是一个可学习的、跨领域的构建，可以通过基于语言的建模来捕捉。

> Professionalism is a crucial yet underexplored dimension of expert communication, particularly in high-stakes domains like finance. This paper investigates how linguistic features can be leveraged to model and evaluate professionalism in expert questioning. We introduce a novel annotation framework to quantify structural and pragmatic elements in financial analyst questions, such as discourse regulators, prefaces, and request types. Using both human-authored and large language model (LLM)-generated questions, we construct two datasets: one annotated for perceived professionalism and one labeled by question origin. We show that the same linguistic features correlate strongly with both human judgments and authorship origin, suggesting a shared stylistic foundation. Furthermore, a classifier trained solely on these interpretable features outperforms gemini-2.0 and SVM baselines in distinguishing expert-authored questions. Our findings demonstrate that professionalism is a learnable, domain-general construct that can be captured through linguistically grounded modeling.

[Arxiv](https://arxiv.org/abs/2507.20249)