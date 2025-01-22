# Trustformer: 可信联邦Transformer

发布时间：2025年01月20日

`LLM应用

理由：这篇论文主要讨论了在Transformer模型的训练过程中，如何通过联邦学习（FL）技术来保护数据隐私并减少通信开销。虽然涉及了Transformer模型（如BERT和GPT-3），但重点在于如何在实际应用中优化这些模型的训练过程，特别是在隐私保护和通信效率方面。因此，这篇论文更适合归类为“LLM应用”，因为它关注的是如何在实际场景中应用和改进大型语言模型（LLM）的训练方法。` `隐私保护`

> Trustformer: A Trusted Federated Transformer

# 摘要

> # 摘要
Transformer 作为序列数据深度学习的基石，在 NLP 等任务中表现卓越。BERT 和 GPT-3 等模型的成功推动了 LLM 的崛起。然而，数据隐私保护仍是关键挑战。尽管联邦学习（FL）等隐私保护技术提供了解决方案，但其在 Transformer 训练中的实际应用仍受限于两大问题：（I）FedAvg 或 FedSGD 等聚合方法可能导致敏感信息泄露，（II）Transformer 模型的大尺寸带来高通信开销。
本文提出了一种新颖的 FL 方法，通过本地模拟全局模型，避免共享完整权重，从而减少通信开销。我们对每个 Transformer 层进行 k-means 聚类，本地计算质心并仅传输质心至服务器。为增强安全性，我们采用 Intel SGX 确保质心传输的安全。在翻译任务中，该方法在显著降低通信成本的同时，保持了与最先进基线相当的性能，为 Transformer 模型提供了一种高效且隐私保护的 FL 解决方案。

> Transformers, a cornerstone of deep-learning architectures for sequential data, have achieved state-of-the-art results in tasks like Natural Language Processing (NLP). Models such as BERT and GPT-3 exemplify their success and have driven the rise of large language models (LLMs). However, a critical challenge persists: safeguarding the privacy of data used in LLM training. Privacy-preserving techniques like Federated Learning (FL) offer potential solutions, but practical limitations hinder their effectiveness for Transformer training. Two primary issues are (I) the risk of sensitive information leakage due to aggregation methods like FedAvg or FedSGD, and (II) the high communication overhead caused by the large size of Transformer models.
  This paper introduces a novel FL method that reduces communication overhead while maintaining competitive utility. Our approach avoids sharing full model weights by simulating a global model locally. We apply k-means clustering to each Transformer layer, compute centroids locally, and transmit only these centroids to the server instead of full weights or gradients. To enhance security, we leverage Intel SGX for secure transmission of centroids. Evaluated on a translation task, our method achieves utility comparable to state-of-the-art baselines while significantly reducing communication costs. This provides a more efficient and privacy-preserving FL solution for Transformer models.

[Arxiv](https://arxiv.org/abs/2501.11706)