# # 优化化合物检索系统
优化化合物检索系统：提升信息检索效率

发布时间：2025年04月16日

`LLM应用

理由：这篇论文探讨了将大型语言模型（LLMs）整合到检索系统中，作为相关性预测的组件，优化检索系统的效果和效率。它属于将LLM应用于特定任务（检索系统优化）的范畴，因此归类为LLM应用。` `信息检索`

> Optimizing Compound Retrieval Systems

# 摘要

> 现代检索系统不再依赖单一的排名模型，而是普遍采用级联方法，在多个重排名阶段依次应用一系列排名模型。通过限制每个模型重新排名的文档数量，它们在前K位排名的质量与计算成本之间取得平衡。然而，级联方法并不是模型之间相互作用以形成检索系统的唯一途径。
我们提出了复合检索系统这一更广泛类别的概念，它不仅涵盖级联模型，还允许除了前K位重排名之外的其他类型交互。特别地，我们实现了与大型语言模型（LLMs）的交互，这些模型可以提供相关性比较。我们的研究重点在于复合检索系统设计的优化，需要独特地学习在哪里应用组件模型，以及如何将它们的预测整合到最终排名中。这项工作展示了我们的复合方法如何结合经典的BM25检索模型与最先进的（成对）LLM相关性预测，同时优化给定的排名指标和效率目标。我们的实验结果表明，经过优化的复合检索系统在效果与效率之间的权衡优于级联方法，即使在自监督方式下应用也是如此。
通过引入复合检索系统，我们希望激发信息检索领域更多突破常规的思考，探讨预测模型如何相互作用以形成排名结果。

> Modern retrieval systems do not rely on a single ranking model to construct their rankings. Instead, they generally take a cascading approach where a sequence of ranking models are applied in multiple re-ranking stages. Thereby, they balance the quality of the top-K ranking with computational costs by limiting the number of documents each model re-ranks. However, the cascading approach is not the only way models can interact to form a retrieval system.
  We propose the concept of compound retrieval systems as a broader class of retrieval systems that apply multiple prediction models. This encapsulates cascading models but also allows other types of interactions than top-K re-ranking. In particular, we enable interactions with large language models (LLMs) which can provide relative relevance comparisons. We focus on the optimization of compound retrieval system design which uniquely involves learning where to apply the component models and how to aggregate their predictions into a final ranking. This work shows how our compound approach can combine the classic BM25 retrieval model with state-of-the-art (pairwise) LLM relevance predictions, while optimizing a given ranking metric and efficiency target. Our experimental results show optimized compound retrieval systems provide better trade-offs between effectiveness and efficiency than cascading approaches, even when applied in a self-supervised manner.
  With the introduction of compound retrieval systems, we hope to inspire the information retrieval field to more out-of-the-box thinking on how prediction models can interact to form rankings.

[Arxiv](https://arxiv.org/abs/2504.12063)