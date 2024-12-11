# 利用 Transformer 来扩展顺序推荐模型

发布时间：2024年12月10日

`LLM应用` `推荐系统` `用户偏好建模`

> Scaling Sequential Recommendation Models with Transformers

# 摘要

> 用户偏好建模主要通过审视用户与系统中不同元素的交互历史来实现。基于历史数据为个人定制内容是顺序推荐的核心目标。
    鉴于问题的本质以及在各领域的出色表现，促使了转换器架构的运用，其在模型参数增多时，利用大量训练数据方面已被证实有效。这种规模变化行为备受关注，因其为设计和训练更大的模型提供了宝贵指导。
    受训练大型语言模型中观察到的规模定律启发，我们为顺序推荐探索了相似原则。
    我们使用了完整的亚马逊产品数据数据集，该数据集在其他研究中仅被部分探究，并揭示了与语言模型中类似的规模变化行为。实现计算最优训练是可行的，但需要仔细分析针对应用的计算与性能的权衡。
    我们还表明，通过在较小的特定任务领域对较大的预训练模型进行微调，性能规模变化可转化为下游任务。我们的方法和发现为在实际高维偏好空间中的模型训练和部署提供了战略路线，有助于提升训练和推理效率。
    我们期望本文能弥合转换器的潜力与现实世界推荐系统中高维顺序推荐的内在复杂性之间的鸿沟。
    代码和模型可在 https://github.com/mercadolibre/srt 找到。

> Modeling user preferences has been mainly addressed by looking at users' interaction history with the different elements available in the system. Tailoring content to individual preferences based on historical data is the main goal of sequential recommendation.
  The nature of the problem, as well as the good performance observed across various domains, has motivated the use of the transformer architecture, which has proven effective in leveraging increasingly larger amounts of training data when accompanied by an increase in the number of model parameters. This scaling behavior has brought a great deal of attention, as it provides valuable guidance in the design and training of even larger models.
  Taking inspiration from the scaling laws observed in training large language models, we explore similar principles for sequential recommendation.
  We use the full Amazon Product Data dataset, which has only been partially explored in other studies, and reveal scaling behaviors similar to those found in language models. Compute-optimal training is possible but requires a careful analysis of the compute-performance trade-offs specific to the application.
  We also show that performance scaling translates to downstream tasks by fine-tuning larger pre-trained models on smaller task-specific domains. Our approach and findings provide a strategic roadmap for model training and deployment in real high-dimensional preference spaces, facilitating better training and inference efficiency.
  We hope this paper bridges the gap between the potential of transformers and the intrinsic complexities of high-dimensional sequential recommendation in real-world recommender systems.
  Code and models can be found at https://github.com/mercadolibre/srt

[Arxiv](https://arxiv.org/abs/2412.07585)