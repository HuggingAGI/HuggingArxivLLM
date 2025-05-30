# 针对大型语言模型的隐秘后门样本检测方法：基于类内距离的分析

发布时间：2025年05月28日

`LLM应用` `信息处理`

> Detecting Stealthy Backdoor Samples based on Intra-class Distance for Large Language Models

# 摘要

> 微调大型语言模型（LLMs）时，若使用包含出版方设置的隐藏后门的数据集，将给下游应用带来安全隐患。主流的检测方法要么通过分析中毒分类模型的预测概率来识别中毒样本，要么依赖重写模型来消除隐藏触发器。然而，前者无法应用于生成任务，而后者可能会降低生成性能并引入新的触发器。因此，如何高效地清除LLMs中的隐藏中毒样本仍是一个亟待解决的问题。

我们发现，对样本响应应用TF-IDF聚类后，清洁样本与中毒样本的类内距离存在显著差异。由于恶意输出的特定性，中毒样本往往聚集得更紧密，而清洁样本因响应多样化而分布更为分散。因此，在本文中，我们提出了一种基于参考过滤和TF-IDF聚类机制的隐藏后门样本检测方法（RFTC）。

具体而言，我们首先将样本响应与参考模型的输出进行比较，若存在显著差异则将样本标记为可疑。然后，我们对这些可疑样本进行TF-IDF聚类，并基于类内距离识别出真正的中毒样本。在两个机器翻译数据集和一个问答数据集上的实验表明，RFTC在后门检测和模型性能方面均优于基线方法。对不同参考模型的进一步分析也验证了我们提出的参考过滤方法的有效性。

> Fine-tuning LLMs with datasets containing stealthy backdoors from publishers poses security risks to downstream applications. Mainstream detection methods either identify poisoned samples by analyzing the prediction probability of poisoned classification models or rely on the rewriting model to eliminate the stealthy triggers. However, the former cannot be applied to generation tasks, while the latter may degrade generation performance and introduce new triggers. Therefore, efficiently eliminating stealthy poisoned samples for LLMs remains an urgent problem. We observe that after applying TF-IDF clustering to the sample response, there are notable differences in the intra-class distances between clean and poisoned samples. Poisoned samples tend to cluster closely because of their specific malicious outputs, whereas clean samples are more scattered due to their more varied responses. Thus, in this paper, we propose a stealthy backdoor sample detection method based on Reference-Filtration and Tfidf-Clustering mechanisms (RFTC). Specifically, we first compare the sample response with the reference model's outputs and consider the sample suspicious if there's a significant discrepancy. And then we perform TF-IDF clustering on these suspicious samples to identify the true poisoned samples based on the intra-class distance. Experiments on two machine translation datasets and one QA dataset demonstrate that RFTC outperforms baselines in backdoor detection and model performance. Further analysis of different reference models also confirms the effectiveness of our Reference-Filtration.

[Arxiv](https://arxiv.org/abs/2505.23015)