# 探究联邦剪枝方法在大型语言模型中的应用

发布时间：2025年05月18日

`LLM应用` `隐私保护`

> Exploring Federated Pruning for Large Language Models

# 摘要

> LLM剪枝技术为大型语言模型的压缩开辟了新途径，使其能够在资源受限的设备上运行。然而，现有方法通常依赖公开校准样本，这在隐私敏感领域中难以实现。为解决这一问题，我们提出了FedPrLLM——一个全面的联邦剪枝框架，专为保护隐私的LLM压缩设计。在FedPrLLM中，每个客户端仅需基于本地校准数据计算剪枝掩码矩阵，并将其分享给服务器以完成全局模型的剪枝。这种方法不仅实现了全局模型的协同剪枝，还能保障客户端本地数据的隐私安全。此外，我们进行了大量实验，深入探索FedPrLLM框架内的多种可能性，包括不同的对比组、剪枝策略以及权重缩放的决策。通过全面评估，我们发现采用层对比且不进行权重缩放的一次性剪枝，是FedPrLLM框架下的最优选择。我们希望这项研究能够为未来在隐私敏感领域对LLM进行剪枝提供有价值的指导。我们的代码已在GitHub上开放，地址为https://github.com/Pengxin-Guo/FedPrLLM。


> LLM pruning has emerged as a promising technology for compressing LLMs, enabling their deployment on resource-limited devices. However, current methodologies typically require access to public calibration samples, which can be challenging to obtain in privacy-sensitive domains. To address this issue, we introduce FedPrLLM, a comprehensive federated pruning framework designed for the privacy-preserving compression of LLMs. In FedPrLLM, each client only needs to calculate a pruning mask matrix based on its local calibration data and share it with the server to prune the global model. This approach allows for collaborative pruning of the global model with the knowledge of each client while maintaining local data privacy. Additionally, we conduct extensive experiments to explore various possibilities within the FedPrLLM framework, including different comparison groups, pruning strategies, and the decision to scale weights. Our extensive evaluation reveals that one-shot pruning with layer comparison and no weight scaling is the optimal choice within the FedPrLLM framework. We hope our work will help guide future efforts in pruning LLMs in privacy-sensitive fields. Our code is available at https://github.com/Pengxin-Guo/FedPrLLM.

[Arxiv](https://arxiv.org/abs/2505.13547)