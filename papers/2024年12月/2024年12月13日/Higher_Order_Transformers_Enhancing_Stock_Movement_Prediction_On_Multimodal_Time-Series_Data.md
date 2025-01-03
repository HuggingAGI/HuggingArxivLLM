# 高阶Transformer：提升多模态时间序列数据的股票走势预测能力

发布时间：2024年12月13日

`其他

理由：这篇论文主要讨论的是一种新的Transformer架构，用于金融市场股票走势预测。虽然Transformer架构与LLM（大型语言模型）相关，但论文的核心内容集中在金融市场的应用，而不是直接讨论LLM的理论、应用或相关技术（如Agent或RAG）。因此，将其分类为“其他”更为合适。` `股票市场`

> Higher Order Transformers: Enhancing Stock Movement Prediction On Multimodal Time-Series Data

# 摘要

> 本文提出了一种名为高阶Transformer的新架构，旨在解决金融市场股票走势预测的难题。该架构通过扩展自注意力机制和Transformer到更高阶，能够有效捕捉跨时间和变量的复杂市场动态。为了降低计算复杂度，我们采用张量分解进行低秩近似，并引入核注意力机制，使复杂度与数据大小呈线性关系。此外，我们还设计了一种编码器-解码器模型，结合技术和基本面分析，利用历史价格和相关推文的多模态信号。在Stocknet数据集上的实验表明，该方法显著提升了股票走势预测的准确性，展现了其在金融市场的应用潜力。

> In this paper, we tackle the challenge of predicting stock movements in financial markets by introducing Higher Order Transformers, a novel architecture designed for processing multivariate time-series data. We extend the self-attention mechanism and the transformer architecture to a higher order, effectively capturing complex market dynamics across time and variables. To manage computational complexity, we propose a low-rank approximation of the potentially large attention tensor using tensor decomposition and employ kernel attention, reducing complexity to linear with respect to the data size. Additionally, we present an encoder-decoder model that integrates technical and fundamental analysis, utilizing multimodal signals from historical prices and related tweets. Our experiments on the Stocknet dataset demonstrate the effectiveness of our method, highlighting its potential for enhancing stock movement prediction in financial markets.

[Arxiv](https://arxiv.org/abs/2412.10540)