# 释放个性化知识：联合大模型中的专家混合力量

发布时间：2025年06月01日

`LLM应用

摘要中讨论了混合专家（MoE）架构在大型语言模型中的应用，以及在联邦学习环境中的优化。提出了一种新的框架FLEx，专门针对基于MoE的LLMs，通过剪裁全局模型并使用自适应门控机制来实现高效个性化。这属于LLM的应用层面，因此分类为LLM应用。` `联邦学习` `大型语言模型`

> Unlocking Personalized Knowledge in Federated Large Language Model: The Power of Mixture of Experts

# 摘要

> 混合专家（MoE）架构作为一种突出的策略，已被广泛应用于大型语言模型（LLMs）的扩展，巧妙地利用了稀疏激活机制，并支持任务特定的个性化。然而，现有的联邦学习（FL）方法主要针对密集模型设计，无法直接利用MoE架构中固有的稀疏性。在联邦场景中将MoE模型视为密集网络会导致通信开销和计算成本过高，从而削弱个性化知识共享的潜力。为了解决这些问题，我们提出了FLEx（Federated LLMs with Personalized Experts），一个专门针对基于MoE的LLMs的新型联邦学习框架。FLEx通过剪裁全局MoE模型，仅保留每个客户端的一个专家，从而实现高效个性化，并采用自适应门控机制，将这些个性化的专家重新整合到预训练的MoE层中，确保原始骨干架构保持不变。这些个性化的专家使用本地数据进行训练并存储在每个客户端本地，而共享模块则进行全局聚合。在非IID条件下的多样化指令数据集上进行的广泛评估表明，FLEx始终优于现有的联邦学习基线。我们的代码可在https://anonymous.4open.science/r/FLEx-8F12获取。

> The Mixture of Experts (MoE) architecture has emerged as a prominent strategy for scaling large language models (LLMs), effectively leveraging sparse activation and facilitating task-specific personalization. However, current federated learning (FL) approaches are primarily designed for dense models, making them unable to directly exploit the sparsity inherent in MoE architectures. Treating MoE models as dense networks in federated scenarios results in excessive communication overhead and computational costs, undermining the potential for personalized knowledge sharing. To address these challenges, we propose FLEx (Federated LLMs with Personalized Experts), a novel federated learning framework explicitly tailored for MoE-based LLMs. FLEx efficiently personalizes by pruning the global MoE model to keep only one expert per client, and employs an adaptive gating mechanism to reintegrate these personalized experts into the pre-trained MoE layers, ensuring the original backbone architecture remains unchanged. These personalized experts are trained with local data and stored locally on each client, while the shared modules are aggregated globally. Extensive evaluations on diverse instruction-based datasets under non-IID conditions consistently demonstrate that FLEx outperforms existing federated baselines. Our code is available at https://anonymous.4open.science/r/FLEx-8F12.

[Arxiv](https://arxiv.org/abs/2506.00965)