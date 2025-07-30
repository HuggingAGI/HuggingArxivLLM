# MoHoBench：借助不可回答的视觉问题评估多模态大语言模型的诚实性

发布时间：2025年07月29日

`LLM应用` `人工智能`

> MoHoBench: Assessing Honesty of Multimodal Large Language Models via Unanswerable Visual Questions

# 摘要

> 多模态大型语言模型（MLLMs）在视觉语言任务中取得了显著进展，但它们生成的内容仍可能存在风险或不可信赖。尽管已有大量研究探讨了语言模型的可信度，但 MMLMs 在面对视觉上无法回答的问题时能否诚实行事，这一方面仍鲜有研究。本文首次对不同 MMLMs 的诚实行为进行了系统性评估。我们基于模型对无法回答的视觉问题的回应行为定义诚实，提出了四种具有代表性的视觉问题类型，并构建了大规模多模态模型诚实基准测试集 MoHoBench，包含 12,000 多个视觉问题样本，其质量通过多阶段筛选和人工验证得到保证。利用 MoHoBench，我们对 28 个流行的 MMLMs 进行了诚实度基准测试，并进行了全面分析。研究发现：（1）大多数模型在必要时无法恰当拒绝回答；（2）MMLMs 的诚实性不仅是一个语言建模问题，还深受视觉信息影响，因此需要开发专门的多模态诚实对齐方法。为此，我们通过监督学习和偏好学习实现了初步的对齐方法，以改进诚实行为，为未来开发可信的 MMLMs 提供了基础。我们的数据和代码可在 https://github.com/DSTTSD/MoHoBench 获取。

> Recently Multimodal Large Language Models (MLLMs) have achieved considerable advancements in vision-language tasks, yet produce potentially harmful or untrustworthy content. Despite substantial work investigating the trustworthiness of language models, MMLMs' capability to act honestly, especially when faced with visually unanswerable questions, remains largely underexplored. This work presents the first systematic assessment of honesty behaviors across various MLLMs. We ground honesty in models' response behaviors to unanswerable visual questions, define four representative types of such questions, and construct MoHoBench, a large-scale MMLM honest benchmark, consisting of 12k+ visual question samples, whose quality is guaranteed by multi-stage filtering and human verification. Using MoHoBench, we benchmarked the honesty of 28 popular MMLMs and conducted a comprehensive analysis. Our findings show that: (1) most models fail to appropriately refuse to answer when necessary, and (2) MMLMs' honesty is not solely a language modeling issue, but is deeply influenced by visual information, necessitating the development of dedicated methods for multimodal honesty alignment. Therefore, we implemented initial alignment methods using supervised and preference learning to improve honesty behavior, providing a foundation for future work on trustworthy MLLMs. Our data and code can be found at https://github.com/DSTTSD/MoHoBench.

[Arxiv](https://arxiv.org/abs/2507.21503)