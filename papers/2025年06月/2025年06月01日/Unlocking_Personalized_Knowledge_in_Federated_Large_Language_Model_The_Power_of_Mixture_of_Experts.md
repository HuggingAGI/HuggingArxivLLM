# # 解锁联邦大型语言模型中的个性化知识：专家混合模型的力量
在联邦大型语言模型中，个性化知识的解锁离不开专家混合模型的强大力量。

发布时间：2025年06月01日

`LLM理论

理由：这篇论文探讨了混合专家模型（MoE）在大型语言模型扩展中的应用，特别是联邦学习框架FLEx的设计。它涉及模型架构和训练方法的改进，属于LLM的理论层面研究。` `人工智能` `联邦学习`

> Unlocking Personalized Knowledge in Federated Large Language Model: The Power of Mixture of Experts

# 摘要

> 混合专家模型（MoE）架构作为一种突出策略，已被广泛应用于大型语言模型（LLMs）的扩展，其通过有效利用稀疏激活并促进任务特定的个性化，取得了显著成效。然而，现有的联邦学习（FL）方法主要针对密集模型设计，无法直接利用MoE架构中固有的稀疏性。将MoE模型视为密集网络进行联邦学习，会导致过高的通信开销和计算成本，从而削弱个性化知识共享的潜力。为了解决这些挑战，我们提出了FLEx（联邦学习中的个性化专家），这是一种专门针对基于MoE的LLMs设计的新型联邦学习框架。FLEx通过剪枝全局MoE模型，仅保留每个客户端的一个专家，从而实现高效的个性化，并采用自适应门控机制将这些个性化专家重新整合到预训练的MoE层中，同时保持原始主干架构不变。这些个性化专家使用本地数据进行训练，并存储在每个客户端本地，而共享模块则进行全局聚合。在非独立同分布（non-IID）条件下，针对多种基于指令的数据集进行的广泛评估表明，FLEx始终优于现有的联邦学习基线。我们的代码可在https://anonymous.4open.science/r/FLEx-8F12获取。

> The Mixture of Experts (MoE) architecture has emerged as a prominent strategy for scaling large language models (LLMs), effectively leveraging sparse activation and facilitating task-specific personalization. However, current federated learning (FL) approaches are primarily designed for dense models, making them unable to directly exploit the sparsity inherent in MoE architectures. Treating MoE models as dense networks in federated scenarios results in excessive communication overhead and computational costs, undermining the potential for personalized knowledge sharing. To address these challenges, we propose FLEx (Federated LLMs with Personalized Experts), a novel federated learning framework explicitly tailored for MoE-based LLMs. FLEx efficiently personalizes by pruning the global MoE model to keep only one expert per client, and employs an adaptive gating mechanism to reintegrate these personalized experts into the pre-trained MoE layers, ensuring the original backbone architecture remains unchanged. These personalized experts are trained with local data and stored locally on each client, while the shared modules are aggregated globally. Extensive evaluations on diverse instruction-based datasets under non-IID conditions consistently demonstrate that FLEx outperforms existing federated baselines. Our code is available at https://anonymous.4open.science/r/FLEx-8F12.

[Arxiv](https://arxiv.org/abs/2506.00965)