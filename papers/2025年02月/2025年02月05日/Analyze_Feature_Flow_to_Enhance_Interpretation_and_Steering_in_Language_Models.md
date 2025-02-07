# 通过分析特征流，提升语言模型的解释性与可控性

发布时间：2025年02月05日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLM）内部特征的追踪和演化，特别是通过跨层特征图来理解和操纵模型行为。这涉及到对LLM内部机制的理论性研究，旨在提高模型的可解释性和控制能力。因此，这篇论文更适合归类为“LLM理论”。` `机器学习`

> Analyze Feature Flow to Enhance Interpretation and Steering in Language Models

# 摘要

> 我们提出了一种新方法，系统地追踪稀疏自编码器在大型语言模型连续层中发现的特征，扩展了早期对层间特征链接的研究。通过无数据余弦相似度技术，我们追踪特征在每一层的持续、转变或首次出现，生成细粒度的特征演化流图，为模型计算提供精细的可解释性和机制性洞察。更重要的是，我们展示了如何通过跨层特征图放大或抑制特定特征，直接引导模型行为，实现文本生成中的主题控制。这些发现突显了因果跨层可解释性框架的价值，它不仅揭示了特征在前向传递中的演变，还为透明操纵大型语言模型提供了新工具。

> We introduce a new approach to systematically map features discovered by sparse autoencoder across consecutive layers of large language models, extending earlier work that examined inter-layer feature links. By using a data-free cosine similarity technique, we trace how specific features persist, transform, or first appear at each stage. This method yields granular flow graphs of feature evolution, enabling fine-grained interpretability and mechanistic insights into model computations. Crucially, we demonstrate how these cross-layer feature maps facilitate direct steering of model behavior by amplifying or suppressing chosen features, achieving targeted thematic control in text generation. Together, our findings highlight the utility of a causal, cross-layer interpretability framework that not only clarifies how features develop through forward passes but also provides new means for transparent manipulation of large language models.

[Arxiv](https://arxiv.org/abs/2502.03032)