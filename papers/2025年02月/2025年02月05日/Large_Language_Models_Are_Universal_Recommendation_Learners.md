# 大型语言模型：通用推荐学习引擎

发布时间：2025年02月05日

`LLM应用

理由：这篇论文讨论了如何利用大型语言模型（LLMs）作为通用推荐学习器来处理多个推荐任务，并提出了多模态融合模块和序列输入-集合输出的方法来提高推荐性能。这表明论文主要关注LLM在实际应用中的使用，特别是在推荐系统中的应用，因此应归类为“LLM应用”。` `推荐系统`

> Large Language Models Are Universal Recommendation Learners

# 摘要

> 在现实世界的推荐系统中，不同任务通常通过在有特定任务的数据集上进行监督学习来解决，并需要精心设计的模型架构。我们展示了大型语言模型（LLMs）可以作为通用推荐学习器，在统一的输入-输出框架内处理多个任务，无需专门模型设计。为提高LLMs的推荐性能，我们引入了多模态融合模块用于项目表示，以及序列输入-集合输出的方法用于高效候选生成。应用于工业规模数据时，我们的LLM在与为不同推荐任务精心设计的专家模型相比，取得了具有竞争力的结果。此外，分析表明推荐结果对文本输入高度敏感，突显了提示工程在优化工业规模推荐系统中的潜力。

> In real-world recommender systems, different tasks are typically addressed using supervised learning on task-specific datasets with carefully designed model architectures. We demonstrate that large language models (LLMs) can function as universal recommendation learners, capable of handling multiple tasks within a unified input-output framework, eliminating the need for specialized model designs. To improve the recommendation performance of LLMs, we introduce a multimodal fusion module for item representation and a sequence-in-set-out approach for efficient candidate generation. When applied to industrial-scale data, our LLM achieves competitive results with expert models elaborately designed for different recommendation tasks. Furthermore, our analysis reveals that recommendation outcomes are highly sensitive to text input, highlighting the potential of prompt engineering in optimizing industrial-scale recommender systems.

[Arxiv](https://arxiv.org/abs/2502.03041)