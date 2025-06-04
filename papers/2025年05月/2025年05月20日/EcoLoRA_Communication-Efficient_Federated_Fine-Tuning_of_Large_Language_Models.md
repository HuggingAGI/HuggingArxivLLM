# EcoLoRA：高效通信的大型语言模型联邦微调方案

发布时间：2025年05月20日

`LLM应用` `人工智能` `联邦学习`

> EcoLoRA: Communication-Efficient Federated Fine-Tuning of Large Language Models

# 摘要

> 为解决数据本地化与隐私限制问题，联邦学习（FL）被用于微调大型语言模型（LLMs），无需聚合数据即可提升下游任务性能。然而，FL中模型更新的反复交换导致通信成本过高，阻碍了分布式学习。为应对这一挑战，我们提出EcoLoRA，一个针对LLMs的高效通信联邦微调新框架。基于模块化结构，我们设计了一种轮流分段共享方案，每个客户端每轮仅上传互补的LoRA段以减少带宽占用。同时结合自适应稀疏化方法和无损编码技术，专为LoRA的训练动态优化。我们在多个数据集和模型上进行了全面评估，涵盖问答和价值对齐任务。结果显示，EcoLoRA显著降低了通信开销，性能不受影响。例如，通信时间减少高达79%，总训练时间减少高达65%。

> To address data locality and privacy restrictions, Federated Learning (FL) has recently been adopted to fine-tune large language models (LLMs), enabling improved performance on various downstream tasks without requiring aggregated data. However, the repeated exchange of model updates in FL can result in prohibitively high communication costs, hindering the distributed learning process. To address this challenge, we propose EcoLoRA, a novel communication-efficient federated fine-tuning framework for LLMs. Leveraging the modular structure, we propose a round-robin segment sharing scheme, where each client uploads only a complementary LoRA segment per round to reduce network bandwidth. It is further combined with adaptive sparsification methods tailored to LoRA's training dynamics and lossless encoding techniques. We conduct extensive evaluations on both question-answering and value-alignment tasks across multiple datasets and models. The results show that EcoLoRA significantly reduces communication overhead without compromising performance. For instance, it reduces communication time by up to 79% and total training time by up to 65%.

[Arxiv](https://arxiv.org/abs/2506.02001)