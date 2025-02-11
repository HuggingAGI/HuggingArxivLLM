# 超越词汇重叠：多语言能力的词汇对齐

发布时间：2025年02月10日

`LLM理论

理由：这篇论文探讨了多语言模型中的分词问题，并提出了一种新的指标来评估跨语言知识转移的潜力。它分析了模型的内部机制，并探讨了数据规模的影响，属于对模型理论的深入研究。` `多语言处理`

> Beyond Literal Token Overlap: Token Alignability for Multilinguality

# 摘要

> 先前研究将token重叠和分布相似性作为语言模型跨语言知识转移的预测指标。然而，这些指标对使用不同脚本的语言对赋予了很大距离，而这些语言对可能仍具有良好的跨语言性。这限制了token重叠对不同脚本或正字法语言对知识转移的解释能力。本文提出subword token对齐性作为理解多语言分词影响的新方法。特别地，当脚本差异大且token重叠低时，这一指标对多语言性的预测效果更佳。我们从编码器和解码器模型角度分析了这一指标，探讨了数据规模的干扰作用，并展望了其在多语言分词中的应用前景。我们推荐该指标用于识别跨语言转移的理想语言对，并指导未来构建更优的多语言分词器。我们的代码和可重复性细节已公开。

> Previous work has considered token overlap, or even similarity of token distributions, as predictors for multilinguality and cross-lingual knowledge transfer in language models. However, these very literal metrics assign large distances to language pairs with different scripts, which can nevertheless show good cross-linguality. This limits the explanatory strength of token overlap for knowledge transfer between language pairs that use distinct scripts or follow different orthographic conventions. In this paper, we propose subword token alignability as a new way to understand the impact and quality of multilingual tokenisation. In particular, this metric predicts multilinguality much better when scripts are disparate and the overlap of literal tokens is low. We analyse this metric in the context of both encoder and decoder models, look at data size as a potential distractor, and discuss how this insight may be applied to multilingual tokenisation in future work. We recommend our subword token alignability metric for identifying optimal language pairs for cross-lingual transfer, as well as to guide the construction of better multilingual tokenisers in the future. We publish our code and reproducibility details.

[Arxiv](https://arxiv.org/abs/2502.06468)