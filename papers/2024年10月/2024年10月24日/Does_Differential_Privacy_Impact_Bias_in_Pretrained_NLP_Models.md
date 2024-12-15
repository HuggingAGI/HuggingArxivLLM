# 差分隐私会对预训练的 NLP 模型中的偏差产生影响吗？

发布时间：2024年10月24日

`LLM应用` `隐私保护` `语言模型`

> Does Differential Privacy Impact Bias in Pretrained NLP Models?

# 摘要

> 差分隐私（DP）用于预训练大型语言模型（LLMs）的微调，以防止训练示例的泄露。尽管多数DP研究聚焦于优化模型的隐私与效用的平衡，但有人发现DP可能对代表性不足的群体有失公平或存在偏见。在此项工作中，我们通过实证分析揭示了DP对LLMs偏差的影响。差分隐私训练会依据基于AUC的偏差指标，加大模型对受保护群体的偏差。DP让模型更难区分受保护群体与其他群体中的正例和负例。我们的成果还显示，DP对偏差的影响不仅取决于隐私保护级别，还与数据集的底层分布有关。

> Differential privacy (DP) is applied when fine-tuning pre-trained large language models (LLMs) to limit leakage of training examples. While most DP research has focused on improving a model's privacy-utility tradeoff, some find that DP can be unfair to or biased against underrepresented groups. In this work, we show the impact of DP on bias in LLMs through empirical analysis. Differentially private training can increase the model bias against protected groups w.r.t AUC-based bias metrics. DP makes it more difficult for the model to differentiate between the positive and negative examples from the protected groups and other groups in the rest of the population. Our results also show that the impact of DP on bias is not only affected by the privacy protection level but also the underlying distribution of the dataset.

[Arxiv](https://arxiv.org/abs/2410.18749)