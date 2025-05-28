# SHE-LoRA：用于异构LoRA联邦调优的选择性同态加密

发布时间：2025年05月27日

`LLM应用` `人工智能` `联邦学习`

> SHE-LoRA: Selective Homomorphic Encryption for Federated Tuning with Heterogeneous LoRA

# 摘要

> 提升大型语言模型（LLMs）在特定领域任务中的性能，联邦微调至关重要。然而，先前研究表明，攻击者可通过梯度反演技术恢复客户端的私有数据。现有针对此类攻击的隐私保护技术通常导致性能下降和高昂成本，难以满足数据分布和设备能力异质的客户端需求。本文提出SHE-LoRA，结合选择性同态加密（HE）和低秩适应（LoRA），实现跨设备环境下高效且隐私保护的LLM联邦微调。异质客户端根据参数敏感性评估自适应选择部分模型参数进行同态加密，并通过协商确定加密子集。为确保模型聚合准确性，我们设计了列感知 secure aggregation 方法和定制重新参数化技术，使聚合结果与客户端设备能力相匹配。大量实验表明，SHE-LoRA 性能与非私有基线相当，对最新攻击具有强鲁棒性，通信开销减少94.901%，加密计算开销减少99.829%。代码获取地址：https://anonymous.4open.science/r/SHE-LoRA-8D84。

> Federated fine-tuning of large language models (LLMs) is critical for improving their performance in handling domain-specific tasks. However, prior work has shown that clients' private data can actually be recovered via gradient inversion attacks. Existing privacy preservation techniques against such attacks typically entail performance degradation and high costs, making them ill-suited for clients with heterogeneous data distributions and device capabilities. In this paper, we propose SHE-LoRA, which integrates selective homomorphic encryption (HE) and low-rank adaptation (LoRA) to enable efficient and privacy-preserving federated tuning of LLMs in cross-device environment. Heterogeneous clients adaptively select partial model parameters for homomorphic encryption based on parameter sensitivity assessment, with the encryption subset obtained via negotiation. To ensure accurate model aggregation, we design a column-aware secure aggregation method and customized reparameterization techniques to align the aggregation results with the heterogeneous device capabilities of clients. Extensive experiments demonstrate that SHE-LoRA maintains performance comparable to non-private baselines, achieves strong resistance to the state-of-the-art attacks, and significantly reduces communication overhead by 94.901\% and encryption computation overhead by 99.829\%, compared to baseline. Our code is accessible at https://anonymous.4open.science/r/SHE-LoRA-8D84.

[Arxiv](https://arxiv.org/abs/2505.21051)