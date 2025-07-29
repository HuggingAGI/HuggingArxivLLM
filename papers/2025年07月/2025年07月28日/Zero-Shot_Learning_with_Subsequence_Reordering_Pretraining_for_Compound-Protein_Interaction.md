# # 摘要  
零样本学习（Zero-Shot Learning）是一种无需特定任务训练数据的技术，近年来在大型语言模型（LLMs）的推动下，已在自然语言处理领域广泛应用。然而，针对化合物-蛋白质相互作用（Compound-Protein Interaction）这一复杂任务，零样本学习仍面临诸多挑战。为应对这些挑战，研究者提出了一种基于子序列重排预训练的零样本学习方法，通过优化模型对序列信息的处理能力，旨在提升其在化合物-蛋白质相互作用预测中的表现。

发布时间：2025年07月28日

`LLM应用` `药物研发` `化合物-蛋白质相互作用`

> Zero-Shot Learning with Subsequence Reordering Pretraining for Compound-Protein Interaction

# 摘要

> 面对化学空间的广袤与新型未表征蛋白质的不断涌现，零样本化合物-蛋白质相互作用（CPI）预测更能体现真实药物研发中的实际挑战与需求。尽管现有方法在某些CPI任务中表现尚可，但仍存在以下问题：(1) 从局部或完整蛋白质序列中进行表征学习时，往往忽视了子序列之间的复杂相互依赖关系，而这对于预测空间结构和结合特性至关重要。(2) 对大规模或稀缺多模态蛋白质数据集的依赖需要大量训练数据和计算资源，限制了模型的扩展性和效率。为解决这些问题，我们提出了一种通过子序列重排预训练蛋白质表征的新方法，显式地捕捉蛋白质子序列之间的依赖关系。同时，我们采用了长度可变的蛋白质增强策略，以确保在小规模训练数据集上实现优秀的预训练性能。为了评估模型的有效性和零样本学习能力，我们将模型与多种基线方法相结合。实验结果表明，我们的方法能够提升基线模型在CPI任务上的性能，尤其是在具有挑战性的零样本场景中表现更优。与现有预训练模型相比，我们的模型在数据稀缺场景下表现更出色，特别是在训练样本有限的情况下。我们的实现代码已开源，地址为https://github.com/Hoch-Zhang/PSRP-CPI。


> Given the vastness of chemical space and the ongoing emergence of previously uncharacterized proteins, zero-shot compound-protein interaction (CPI) prediction better reflects the practical challenges and requirements of real-world drug development. Although existing methods perform adequately during certain CPI tasks, they still face the following challenges: (1) Representation learning from local or complete protein sequences often overlooks the complex interdependencies between subsequences, which are essential for predicting spatial structures and binding properties. (2) Dependence on large-scale or scarce multimodal protein datasets demands significant training data and computational resources, limiting scalability and efficiency. To address these challenges, we propose a novel approach that pretrains protein representations for CPI prediction tasks using subsequence reordering, explicitly capturing the dependencies between protein subsequences. Furthermore, we apply length-variable protein augmentation to ensure excellent pretraining performance on small training datasets. To evaluate the model's effectiveness and zero-shot learning ability, we combine it with various baseline methods. The results demonstrate that our approach can improve the baseline model's performance on the CPI task, especially in the challenging zero-shot scenario. Compared to existing pre-training models, our model demonstrates superior performance, particularly in data-scarce scenarios where training samples are limited. Our implementation is available at https://github.com/Hoch-Zhang/PSRP-CPI.

[Arxiv](https://arxiv.org/abs/2507.20925)