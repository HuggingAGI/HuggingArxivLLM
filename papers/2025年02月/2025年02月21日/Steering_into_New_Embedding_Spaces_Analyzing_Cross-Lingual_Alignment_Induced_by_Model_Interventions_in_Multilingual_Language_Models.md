# 探索新的嵌入空间：分析多语言模型中模型干预手段对跨语言对齐机制的影响

发布时间：2025年02月21日

`LLM应用` `信息检索`

> Steering into New Embedding Spaces: Analyzing Cross-Lingual Alignment Induced by Model Interventions in Multilingual Language Models

# 摘要

> 跨语言的对齐表示是多语言大语言模型（mLLMs）的理想特性，因为它能够提升跨语言任务的性能表现。通常，实现对齐需要对模型进行微调，这在计算上成本高昂，而且还需要大量语言数据，而这些数据往往难以获取。作为一种数据高效的替代方案，模型干预方法通过操纵模型的激活来引导生成走向预期方向。我们分析了一种流行干预手段（寻找专家）对mLLMs跨语言表示对齐的影响。我们确定了需要操纵的神经元以针对特定语言，并在干预前后对mLLMs的嵌入空间进行了深入探究。我们发现，通过修改mLLM的激活状态，可以改变其嵌入空间，从而增强跨语言的对齐效果。进一步地，我们展示了嵌入空间的这些变化如何转化为检索任务的下游性能提升，跨语言检索任务的top-1准确率最高提升了2倍。


> Aligned representations across languages is a desired property in multilingual large language models (mLLMs), as alignment can improve performance in cross-lingual tasks. Typically alignment requires fine-tuning a model, which is computationally expensive, and sizable language data, which often may not be available. A data-efficient alternative to fine-tuning is model interventions -- a method for manipulating model activations to steer generation into the desired direction. We analyze the effect of a popular intervention (finding experts) on the alignment of cross-lingual representations in mLLMs. We identify the neurons to manipulate for a given language and introspect the embedding space of mLLMs pre- and post-manipulation. We show that modifying the mLLM's activations changes its embedding space such that cross-lingual alignment is enhanced. Further, we show that the changes to the embedding space translate into improved downstream performance on retrieval tasks, with up to 2x improvements in top-1 accuracy on cross-lingual retrieval.

[Arxiv](https://arxiv.org/abs/2502.15639)