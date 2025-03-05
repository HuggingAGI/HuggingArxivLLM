# 莎士比亚式的火花：在 LLM 解码层中，幻觉与创造力展开了一场精彩的舞蹈

发布时间：2025年03月04日

`LLM理论` `人工智能` `认知科学`

> Shakespearean Sparks: The Dance of Hallucination and Creativity in LLMs' Decoding Layers

# 摘要

> 大型语言模型（LLMs）的幻觉现象常与创造力相关联，但以往研究多从理论或定性角度探讨这一联系。我们的研究采用定量方法，系统性地考察了LLMs中幻觉与创造力之间的关系。鉴于创造力的复杂性，我们为LLMs提出了一个窄定义，并引入了HCL评估框架，该框架量化了LLMs在解码过程中不同层的幻觉与创造力。实证分析揭示了幻觉与创造力之间的一致性权衡关系，这种关系贯穿层深度、模型类型和模型规模。值得注意的是，在不同模型架构中，每个模型规模下都有一个特定层能够最优地平衡这一权衡。此外，最佳层倾向于出现在较大模型的早期层中，且模型信心在该层显著更高。这些发现提供了定量视角，为理解LLMs创造力与幻觉之间的相互作用提供了新见解。我们的实验代码和数据可在https://github.com/ZicongHe2002/HCL-Spark获取。

> Large language models (LLMs) are known to hallucinate, a phenomenon often linked to creativity. While previous research has primarily explored this connection through theoretical or qualitative lenses, our work takes a quantitative approach to systematically examine the relationship between hallucination and creativity in LLMs. Given the complex nature of creativity, we propose a narrow definition tailored to LLMs and introduce an evaluation framework, HCL, which quantifies Hallucination and Creativity across different Layers of LLMs during decoding. Our empirical analysis reveals a tradeoff between hallucination and creativity that is consistent across layer depth, model type, and model size. Notably, across different model architectures, we identify a specific layer at each model size that optimally balances this tradeoff. Additionally, the optimal layer tends to appear in the early layers of larger models, and the confidence of the model is also significantly higher at this layer. These findings provide a quantitative perspective that offers new insights into the interplay between LLM creativity and hallucination. The code and data for our experiments are available at https://github.com/ZicongHe2002/HCL-Spark.

[Arxiv](https://arxiv.org/abs/2503.02851)