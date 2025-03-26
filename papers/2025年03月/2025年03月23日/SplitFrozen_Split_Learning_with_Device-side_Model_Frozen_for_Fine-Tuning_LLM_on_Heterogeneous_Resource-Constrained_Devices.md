# SplitFrozen：设备端模型冻结的拆分学习，用于在异构资源受限设备上微调大型语言模型

发布时间：2025年03月23日

`LLM应用` `边缘计算` `模型优化`

> SplitFrozen: Split Learning with Device-side Model Frozen for Fine-Tuning LLM on Heterogeneous Resource-Constrained Devices

# 摘要

> 在私有设备数据上微调大型语言模型（LLMs）能够赋能定制化的个性化AI代理。然而，在资源受限的边缘设备上进行LLMs微调面临重大挑战，包括过高的计算开销、设备异构性以及数据不平衡问题。为此，我们提出了一种名为SplitFrozen的创新框架，通过在设备端冻结部分模型层，同时在服务器端进行高效微调，实现了资源优化的LLMs微调方案。实验结果表明，SplitFrozen在极度数据不平衡的条件下，模型准确率比现有方法FedLoRA和SplitLoRA高出69.4%，同时显著降低了设备端计算量和总训练时间。此外，该框架在内容生成任务中也展现出良好的可扩展性。

> Fine-tuning large language models (LLMs) on private, on-device data can empower tailored personalized AI agents. However, fine-tuning LLMs on resource-constrained edge devices faces significant challenges, including excessive computation overhead, device heterogeneity, and data imbalance. This paper proposes SplitFrozen, a split learning framework that enables efficient LLM fine-tuning by strategically freezing device-side model layers while centralizing parameter-efficient fine-tuning on the server. Our framework partitions LLMs into device-side frozen layers and server-side fine-tuning layers, where heterogeneous resource-constrained devices execute only forward propagation. To minimize server-side training costs, we integrate Low-Rank Adaptation (LoRA) into the server-side layers. A pipeline parallelism strategy further optimizes training efficiency by decoupling device-server computations and leveraging decomposed backward propagation. Experiments on GPT-2 with the MRPC, MNLI-matched, and SST-2 datasets demonstrate that SplitFrozen outperforms FedLoRA and SplitLoRA by 69.4\% model accuracy under extremely imbalanced data, while reducing up to 86.8\% device-side computations and 50.2\% total training time. Experiments also validate the scalability of SplitFrozen on content generation task using Llama-3.2 model on GSM8K dataset.

[Arxiv](https://arxiv.org/abs/2503.18986)