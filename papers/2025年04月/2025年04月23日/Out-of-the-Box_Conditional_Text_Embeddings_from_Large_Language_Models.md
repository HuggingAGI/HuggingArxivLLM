# 大型语言模型的开箱即用条件文本嵌入

发布时间：2025年04月23日

`LLM理论` `机器学习`

> Out-of-the-Box Conditional Text Embeddings from Large Language Models

# 摘要

> 条件文本嵌入是一种能够捕捉特定视角下文本变化的表示方法。传统方法依赖大量训练数据进行微调，这在人力和资源成本上面临挑战。我们提出了一种名为PonTE的新颖无监督条件文本嵌入方法，该方法巧妙结合因果大型语言模型和条件提示。通过在条件语义文本相似性和文本聚类上的实验，我们证明PonTE能够生成有用的条件文本嵌入，并在无需微调的情况下达到与监督方法相当的性能。我们还通过分析提示后单词生成和嵌入可视化，展示了文本嵌入的可解释性。

> Conditional text embedding is a proposed representation that captures the shift in perspective on texts when conditioned on a specific aspect. Previous methods have relied on extensive training data for fine-tuning models, leading to challenges in terms of labor and resource costs. We propose PonTE, a novel unsupervised conditional text embedding method that leverages a causal large language model and a conditional prompt. Through experiments on conditional semantic text similarity and text clustering, we demonstrate that PonTE can generate useful conditional text embeddings and achieve performance comparable to supervised methods without fine-tuning. We also show the interpretability of text embeddings with PonTE by analyzing word generation following prompts and embedding visualization.

[Arxiv](https://arxiv.org/abs/2504.16411)