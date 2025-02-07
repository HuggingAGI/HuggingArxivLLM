# 维度之痛：LLM嵌入压缩在噪声回归任务中的角色

发布时间：2025年02月04日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLMs）在文本压缩表示方面的表现，特别是在不同信噪比场景下的嵌入压缩效果。论文通过实验对比了不同任务中的嵌入压缩效果，并分析了压缩表示对模型性能的影响。这些研究内容属于对LLM的理论分析和优化，因此归类为“LLM理论”。`

> When Dimensionality Hurts: The Role of LLM Embedding Compression for Noisy Regression Tasks

# 摘要

> 大型语言模型（LLMs）凭借模型规模和文本表示隐藏维度的缩放定律，在语言建模领域取得了显著成就。然而，我们发现文本的压缩表示在LLM回归任务中表现更佳。本文对比了三种不同信噪比场景下的嵌入压缩效果：金融回报预测、写作质量评估和评论评分。结果显示，通过自编码器隐藏层进行最小监督的嵌入压缩，能有效减少过拟合，提升金融回报预测等噪声任务的性能；但在输入与目标数据高度因果依赖的任务中，压缩反而会降低表现。这表明，情感等可解释的压缩表示之所以成功，可能得益于其正则化效果。

> Large language models (LLMs) have shown remarkable success in language modelling due to scaling laws found in model size and the hidden dimension of the model's text representation. Yet, we demonstrate that compressed representations of text can yield better performance in LLM-based regression tasks. In this paper, we compare the relative performance of embedding compression in three different signal-to-noise contexts: financial return prediction, writing quality assessment and review scoring. Our results show that compressing embeddings, in a minimally supervised manner using an autoencoder's hidden representation, can mitigate overfitting and improve performance on noisy tasks, such as financial return prediction; but that compression reduces performance on tasks that have high causal dependencies between the input and target data. Our results suggest that the success of interpretable compressed representations such as sentiment may be due to a regularising effect.

[Arxiv](https://arxiv.org/abs/2502.02199)