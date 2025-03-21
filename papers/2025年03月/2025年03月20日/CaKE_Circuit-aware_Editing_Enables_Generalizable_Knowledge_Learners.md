# CaKE: 电路感知编辑赋能通用知识学习模型

发布时间：2025年03月20日

`LLM应用

摘要主要讨论了知识编辑（KE）在大型语言模型（LLMs）中的应用，提出了一种新的方法CaKE来改进知识编辑的效果，特别是在多跳推理任务中的应用。因此，这篇论文属于LLM应用类别。` `人工智能`

> CaKE: Circuit-aware Editing Enables Generalizable Knowledge Learners

# 摘要

> 知识编辑（KE）使我们能够修改大型语言模型（LLMs）中过时或错误的信息。然而，现有的KE方法虽然能够更新孤立的事实，但难以将这些更新推广到依赖修改后知识的多跳推理任务中。通过分析推理回路——LLMs用于知识推理的神经通路，我们发现目前仅针对单层或少数几层模型进行编辑的局部层KE方法（如MEMIT和WISE），难以有效将更新的信息整合到这些推理通路中。为了解决这一局限性，我们提出了一种名为CaKE（Circuit-aware Knowledge Editing，回路感知知识编辑）的新方法，该方法能够更有效地将更新后的知识整合到LLMs中。CaKE利用了经过精心策划的数据，并根据我们基于回路的分析进行引导，强制模型利用修改后的知识，从而刺激模型为新整合的知识发展出适当的推理回路。实验结果表明，与现有的KE方法相比，CaKE能够更准确和一致地在相关推理任务中使用更新后的知识，在MQuAKE数据集上多跳推理准确率平均提高了20%。我们已经在https://github.com/zjunlp/CaKE发布了代码和数据集。

> Knowledge Editing (KE) enables the modification of outdated or incorrect information in large language models (LLMs). While existing KE methods can update isolated facts, they struggle to generalize these updates to multi-hop reasoning tasks that depend on the modified knowledge. Through an analysis of reasoning circuits -- the neural pathways LLMs use for knowledge-based inference, we observe that current layer-localized KE approaches, such as MEMIT and WISE, which edit only single or a few model layers, struggle to effectively incorporate updated information into these reasoning pathways. To address this limitation, we propose CaKE (Circuit-aware Knowledge Editing), a novel method that enables more effective integration of updated knowledge in LLMs. CaKE leverages strategically curated data, guided by our circuits-based analysis, that enforces the model to utilize the modified knowledge, stimulating the model to develop appropriate reasoning circuits for newly integrated knowledge. Experimental results show that CaKE enables more accurate and consistent use of updated knowledge across related reasoning tasks, leading to an average of 20% improvement in multi-hop reasoning accuracy on MQuAKE dataset compared to existing KE methods. We release the code and data in https://github.com/zjunlp/CaKE.

[Arxiv](https://arxiv.org/abs/2503.16356)