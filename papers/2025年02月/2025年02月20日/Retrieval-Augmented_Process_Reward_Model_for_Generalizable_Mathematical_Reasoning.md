# 检索增强型流程奖励模型实现数学推理的泛化能力

发布时间：2025年02月20日

`LLM应用`

> Retrieval-Augmented Process Reward Model for Generalizable Mathematical Reasoning

# 摘要

> 虽然大型语言模型 (LLMs) 在数学推理领域取得了显著进展，但现有的过程奖励模型 (PRMs) 在评估推理步骤的逻辑有效性方面仍面临挑战，尤其是在处理分布外 (OOD) 问题时表现不足。本文深入分析了 OOD 问题的成因，包括由模型类型和规模差异导致的推理模式差异引发的步骤 OOD，以及因训练数据与实际问题间数据集偏移造成的问题 OOD。为解决这些挑战，我们提出了一种创新的框架——检索增强的过程奖励模型 (RetrievalPRM)。通过引入两阶段检索增强机制，RetrievalPRM 在正式评估目标步骤前，先检索语义相似的问题和步骤作为热身，从而显著提升了 PRM 的评估能力，增强了其在不同模型和问题类型上的泛化能力和推理一致性。我们的实验证明，RetrievalPRM 在多个现实世界数据集上表现优异，超越了现有基线模型。此外，我们还开源了检索增强的数据集、PRM 训练调优框架以及 RetrievalPRM 模型，为 PRM 的性能设定了新的行业标准。

> While large language models (LLMs) have significantly advanced mathematical reasoning, Process Reward Models (PRMs) have been developed to evaluate the logical validity of reasoning steps. However, PRMs still struggle with out-of-distribution (OOD) challenges. This paper identifies key OOD issues, including step OOD, caused by differences in reasoning patterns across model types and sizes, and question OOD, which arises from dataset shifts between training data and real-world problems. To address these issues, we introduce Retrieval-Augmented Process Reward Model (RetrievalPRM), a novel framework designed to tackle these OOD issues. By utilizing a two-stage retrieval-enhanced mechanism, RetrievalPRM retrieves semantically similar questions and steps as a warmup, enhancing PRM's ability to evaluate target steps and improving generalization and reasoning consistency across different models and problem types. Our extensive experiments demonstrate that RetrievalPRM outperforms existing baselines across multiple real-world datasets. Our open-source contributions include a retrieval-enhanced dataset, a tuning framework for PRM training, and the RetrievalPRM model, establishing a new standard for PRM performance.

[Arxiv](https://arxiv.org/abs/2502.14361)