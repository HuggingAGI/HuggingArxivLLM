# # 探究模型编辑在基于LLM的方面情感分类中的应用

发布时间：2025年03月19日

`LLM应用` `机器学习`

> Exploring Model Editing for LLM-based Aspect-Based Sentiment Classification

# 摘要

> 模型编辑通过可解释的策略，有选择性地更新神经模型的一小部分参数，以实现预期修改。它能显著降低大型语言模型（LLMs）的适应成本。由于其精准定位LLMs关键组件的能力，模型编辑在高效微调应用中潜力巨大。本研究探索模型编辑作为一种高效方法，用于将LLMs适应以解决基于方面的情感分类问题。通过因果干预，我们追踪并确定了哪些神经元的隐藏状态对模型预测至关重要。通过对LLM的每个组件进行干预和恢复，我们识别出这些组件在基于方面的情感分类中的重要性。我们的研究发现，一组独特的中间层表示对于检测给定方面词的情感极性至关重要。基于这些见解，我们开发了一种专注于LLM关键部分的模型编辑方法，从而形成了一种更高效的LLMs适应方法。我们的领域内和领域外实验表明，与当前最强的方法相比，该方法在可训练参数显著减少的情况下仍能取得具有竞争力的结果，突显出一种更高效、更可解释的微调策略。

> Model editing aims at selectively updating a small subset of a neural model's parameters with an interpretable strategy to achieve desired modifications. It can significantly reduce computational costs to adapt to large language models (LLMs). Given its ability to precisely target critical components within LLMs, model editing shows great potential for efficient fine-tuning applications. In this work, we investigate model editing to serve an efficient method for adapting LLMs to solve aspect-based sentiment classification. Through causal interventions, we trace and determine which neuron hidden states are essential for the prediction of the model. By performing interventions and restorations on each component of an LLM, we identify the importance of these components for aspect-based sentiment classification. Our findings reveal that a distinct set of mid-layer representations is essential for detecting the sentiment polarity of given aspect words. Leveraging these insights, we develop a model editing approach that focuses exclusively on these critical parts of the LLM, leading to a more efficient method for adapting LLMs. Our in-domain and out-of-domain experiments demonstrate that this approach achieves competitive results compared to the currently strongest methods with significantly fewer trainable parameters, highlighting a more efficient and interpretable fine-tuning strategy.

[Arxiv](https://arxiv.org/abs/2503.15117)