# FLEKE：联邦定位-编辑知识编辑方法

发布时间：2025年02月21日

`其他` `联邦学习` `模型优化`

> FLEKE: Federated Locate-then-Edit Knowledge Editing

# 摘要

> 定位-编辑知识编辑（LEKE）是更新大型语言模型（LLMs）的重要技术，无需进行完整的重新训练。然而，现有方法仅适用于单用户场景，在实际的多客户端场景中效率低下。具体而言，去中心化组织（如医院、金融机构）在独立更新重叠知识时，会出现冗余的中介知识向量（MKV）计算和隐私泄露问题。针对这些挑战，我们提出了联邦定位-编辑知识编辑（FLEKE），这是一种新型任务，允许多个客户端在保护隐私的同时协作完成LEKE任务并减少计算开销。为此，我们设计了FedEdit，一个两阶段的优化框架，专注于MKV的选择与复用。在第一阶段，客户端本地执行LEKE并上传计算得到的MKVs。在第二阶段，FLEKE突破了传统服务器端MKV共享的限制，允许客户端根据余弦相似度检索相关MKVs，从而实现知识的重新编辑并最大限度地减少冗余计算。实验结果表明，在两个基准数据集上，FedEdit不仅保留了非联邦LEKE超过96%的性能，而且在与基于FedAvg的基线模型对比中，性能提升约两倍。此外，通过实证研究，我们发现MEMIT在结合我们的FedEdit框架的FLEKE任务中表现比PMET更加稳定。我们的代码已开源，可在https://github.com/zongkaiz/FLEKE获取。

> Locate-then-Edit Knowledge Editing (LEKE) is a key technique for updating large language models (LLMs) without full retraining. However, existing methods assume a single-user setting and become inefficient in real-world multi-client scenarios, where decentralized organizations (e.g., hospitals, financial institutions) independently update overlapping knowledge, leading to redundant mediator knowledge vector (MKV) computations and privacy concerns. To address these challenges, we introduce Federated Locate-then-Edit Knowledge Editing (FLEKE), a novel task that enables multiple clients to collaboratively perform LEKE while preserving privacy and reducing computational overhead. To achieve this, we propose FedEdit, a two-stage framework that optimizes MKV selection and reuse. In the first stage, clients locally apply LEKE and upload the computed MKVs. In the second stage, rather than relying solely on server-based MKV sharing, FLEKE allows clients retrieve relevant MKVs based on cosine similarity, enabling knowledge re-edit and minimizing redundant computations. Experimental results on two benchmark datasets demonstrate that FedEdit retains over 96% of the performance of non-federated LEKE while significantly outperforming a FedAvg-based baseline by approximately twofold. Besides, we find that MEMIT performs more consistently than PMET in the FLEKE task with our FedEdit framework. Our code is available at https://github.com/zongkaiz/FLEKE.

[Arxiv](https://arxiv.org/abs/2502.15677)