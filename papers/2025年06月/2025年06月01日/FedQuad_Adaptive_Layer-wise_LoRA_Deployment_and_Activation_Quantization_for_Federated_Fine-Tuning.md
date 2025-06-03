# # FedQuad：面向联邦微调的自适应分层LoRA部署与激活量化

发布时间：2025年06月01日

`LLM应用

LLM应用` `资源受限设备` `联邦学习`

> FedQuad: Adaptive Layer-wise LoRA Deployment and Activation Quantization for Federated Fine-Tuning

# 摘要

> 联邦微调（FedFT）为隐私敏感场景下的大型语言模型（LLMs）微调提供了一种有效解决方案。然而，终端设备资源有限，导致实际部署面临诸多挑战。现有方法通常借助参数高效的微调（PEFT）技术，如低秩适配（LoRA），大幅降低通信开销。但激活存储的内存占用和全反向传播的计算需求，仍是资源受限设备高效部署的主要障碍。此外，设备间的资源异质性引发严重同步瓶颈，显著降低了整体微调效率。

针对这些问题，我们提出了FedQuad——一个基于LoRA的联邦微调框架。该框架能够根据设备计算能力，自适应调整LoRA深度（从输出开始的连续可调LoRA层数量），并结合激活量化技术，有效降低内存开销，实现资源受限设备的高效部署。具体而言，FedQuad首先基于设备特定资源约束，确定LoRA深度与激活量化层数量的最优组合。随后，通过贪心策略为每个设备选择最佳配置，有效应对系统异质性。

大量实验表明，与现有基线方法相比，FedQuad在达到目标精度时实现了1.4-5.3倍的加速收敛。这充分证明了FedQuad在资源受限和异质终端设备环境中的高效性和可部署性。

> Federated fine-tuning (FedFT) provides an effective paradigm for fine-tuning large language models (LLMs) in privacy-sensitive scenarios. However, practical deployment remains challenging due to the limited resources on end devices. Existing methods typically utilize parameter-efficient fine-tuning (PEFT) techniques, such as Low-Rank Adaptation (LoRA), to substantially reduce communication overhead. Nevertheless, significant memory usage for activation storage and computational demands from full backpropagation remain major barriers to efficient deployment on resource-constrained end devices. Moreover, substantial resource heterogeneity across devices results in severe synchronization bottlenecks, diminishing the overall fine-tuning efficiency. To address these issues, we propose FedQuad, a novel LoRA-based FedFT framework that adaptively adjusts the LoRA depth (the number of consecutive tunable LoRA layers from the output) according to device computational capabilities, while employing activation quantization to reduce memory overhead, thereby enabling efficient deployment on resource-constrained devices. Specifically, FedQuad first identifies the feasible and efficient combinations of LoRA depth and the number of activation quantization layers based on device-specific resource constraints. Subsequently, FedQuad employs a greedy strategy to select the optimal configurations for each device, effectively accommodating system heterogeneity. Extensive experiments demonstrate that FedQuad achieves a 1.4-5.3x convergence acceleration compared to state-of-the-art baselines when reaching target accuracy, highlighting its efficiency and deployability in resource-constrained and heterogeneous end-device environments.

[Arxiv](https://arxiv.org/abs/2506.01001)