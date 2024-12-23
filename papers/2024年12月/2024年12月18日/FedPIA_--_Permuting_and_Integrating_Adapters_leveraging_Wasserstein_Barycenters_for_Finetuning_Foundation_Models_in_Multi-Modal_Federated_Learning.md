# FedPIA——借助Wasserstein重心来对适配器进行排列与整合，以在多模态联邦学习中对基础模型进行微调

发布时间：2024年12月18日

`LLM应用` `联邦学习`

> FedPIA -- Permuting and Integrating Adapters leveraging Wasserstein Barycenters for Finetuning Foundation Models in Multi-Modal Federated Learning

# 摘要

> 大型视觉语言模型通常需要大量的文本和图像数据集来实现有效的微调。然而，由于严格的隐私规定，从各个站点收集数据，尤其是在医疗保健领域，困难重重。一个替代方案是在终端用户设备（比如医疗诊所）上对这些模型进行微调，且不把数据传至服务器。这些本地客户端通常计算能力有限，数据集规模小，自身难以对大型 VLM 进行全面微调。针对这种情况，一个直接的解决办法是借助参数高效微调（PEFT）策略，并运用联邦学习（FL）算法来整合学习到的适配器权重，以此尊重资源限制和数据隐私。但这种方式未能充分利用在不同数据分布和不同任务上训练的多个适配器的知识。适配器受客户端之间的数据异质性和任务异质性的不良影响，导致收敛效果不佳。为此，我们提出了一个名为 FedPIA 的新框架，通过在服务器中对本地适配器进行排列和整合，以及在客户端中引入全局适配器，并利用 Wasserstein 重心来优化客户端特定和客户端无关知识的融合。这种分层排列有助于在整合前弥合本地和全局适配器的参数空间差距。我们利用涵盖五个不同医疗视觉语言 FL 任务设置的 48 个医疗图像数据集开展了超过 2000 次客户端级别的实验，包含视觉问答以及基于图像和报告的多标签疾病检测。我们涉及不同客户端设置、十种不同模态和两个 VLM 骨干的实验表明，FedPIA 始终优于最先进的 PEFT-FL 基线。

> Large Vision-Language Models typically require large text and image datasets for effective fine-tuning. However, collecting data from various sites, especially in healthcare, is challenging due to strict privacy regulations. An alternative is to fine-tune these models on end-user devices, such as in medical clinics, without sending data to a server. These local clients typically have limited computing power and small datasets, which are not enough for fully fine-tuning large VLMs on their own. A naive solution to these scenarios is to leverage parameter-efficient fine-tuning (PEFT) strategies and apply federated learning (FL) algorithms to combine the learned adapter weights, thereby respecting the resource limitations and data privacy. However, this approach does not fully leverage the knowledge from multiple adapters trained on diverse data distributions and for diverse tasks. The adapters are adversely impacted by data heterogeneity and task heterogeneity across clients resulting in suboptimal convergence. To this end, we propose a novel framework called FedPIA that improves upon the naive combinations of FL and PEFT by introducing Permutation and Integration of the local Adapters in the server and global Adapters in the clients exploiting Wasserstein barycenters for improved blending of client-specific and client-agnostic knowledge. This layerwise permutation helps to bridge the gap in the parameter space of local and global adapters before integration. We conduct over 2000 client-level experiments utilizing 48 medical image datasets across five different medical vision-language FL task settings encompassing visual question answering as well as image and report-based multi-label disease detection. Our experiments involving diverse client settings, ten different modalities, and two VLM backbones demonstrate that FedPIA consistently outperforms the state-of-the-art PEFT-FL baselines.

[Arxiv](https://arxiv.org/abs/2412.14424)