# 利用LLMs解决第三方库推荐中的流行度偏差

发布时间：2025年01月17日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLMs）在解决第三方库（TPLs）推荐系统中流行度偏差问题中的应用。论文通过实验和消融研究，评估了LLMs在提升推荐多样性方面的效果，并分析了其局限性。因此，这篇论文主要关注LLMs在实际应用中的表现和改进，属于“LLM应用”类别。` `软件工程` `推荐系统`

> Addressing Popularity Bias in Third-Party Library Recommendations Using LLMs

# 摘要

> # 摘要
软件工程推荐系统（RSSE）通过根据开发者上下文提供相关建议，在自动化开发任务中发挥着关键作用。然而，它们常受流行度偏差困扰，即倾向于推荐与当前任务无关的热门项目。长尾效应尤其会影响系统的准确性，导致推荐中出现误报。基础模型作为最先进的生成式AI模型，在多个软件工程任务中表现出色。
本文探讨了大型语言模型（LLMs）在解决第三方库（TPLs）推荐系统中流行度偏差方面的潜力。我们通过消融研究，实验了包括微调和流行度惩罚机制在内的前沿技术。结果显示，尽管微调和后处理惩罚机制提升了推荐的多样性，LLMs仍无法有效解决TPL推荐系统中的流行度偏差。此外，我们分析了LLMs的局限性，并提出了改进建议，为未来研究指明了方向。

> Recommender systems for software engineering (RSSE) play a crucial role in automating development tasks by providing relevant suggestions according to the developer's context. However, they suffer from the so-called popularity bias, i.e., the phenomenon of recommending popular items that might be irrelevant to the current task. In particular, the long-tail effect can hamper the system's performance in terms of accuracy, thus leading to false positives in the provided recommendations. Foundation models are the most advanced generative AI-based models that achieve relevant results in several SE tasks.
  This paper aims to investigate the capability of large language models (LLMs) to address the popularity bias in recommender systems of third-party libraries (TPLs). We conduct an ablation study experimenting with state-of-the-art techniques to mitigate the popularity bias, including fine-tuning and popularity penalty mechanisms. Our findings reveal that the considered LLMs cannot address the popularity bias in TPL recommenders, even though fine-tuning and post-processing penalty mechanism contributes to increasing the overall diversity of the provided recommendations. In addition, we discuss the limitations of LLMs in this context and suggest potential improvements to address the popularity bias in TPL recommenders, thus paving the way for additional experiments in this direction.

[Arxiv](https://arxiv.org/abs/2501.10313)