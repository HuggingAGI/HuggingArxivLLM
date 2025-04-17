# SALAD：利用结构感知与LLM驱动的增强数据，通过对比学习提升模型的鲁棒性与泛化能力

发布时间：2025年04月16日

`LLM应用

理由：这篇论文提出了一种利用大语言模型生成数据的方法（SALAD），以解决微调预训练语言模型时的伪相关问题，并通过对比学习提升模型的鲁棒性和泛化能力。研究重点在于应用LLM生成结构感知和反事实增强的数据，属于LLM的应用层面。` `社交媒体分析`

> SALAD: Improving Robustness and Generalization through Contrastive Learning with Structure-Aware and LLM-Driven Augmented Data

# 摘要

> 在各种自然语言处理（NLP）任务中，微调预训练语言模型（PLMs）常常导致伪相关问题，这会负面影响性能，特别是在处理分布外数据时。为了解决这一问题，我们提出了一种名为SALAD（结构感知和大语言模型驱动的增强数据）的新方法，旨在通过生成结构感知和反事实增强的数据来提升模型的鲁棒性和泛化能力，用于对比学习。我们的方法采用基于标签的方法生成结构感知的正样本，并利用大语言模型（LLMs）生成具有多样化句式结构的反事实负样本。通过应用对比学习，SALAD使模型能够专注于学习关键句法成分之间的结构关系，同时减少对伪相关的依赖。我们在情感分类、性别歧视检测和自然语言推理三个任务上验证了我们的方法。实验结果表明，SALAD不仅显著提高了模型的鲁棒性和性能，还增强了其对分布外数据集和跨领域场景的泛化能力。

> In various natural language processing (NLP) tasks, fine-tuning Pre-trained Language Models (PLMs) often leads to the issue of spurious correlations, which negatively impacts performance, particularly when dealing with out-of-distribution data. To address this problem, we propose SALAD}(Structure Aware and LLM-driven Augmented Data), a novel approach designed to enhance model robustness and generalization by generating structure-aware and counterfactually augmented data for contrastive learning. Our method leverages a tagging-based approach to generate structure-aware positive samples and utilizes large language models (LLMs) to generate counterfactual negative samples with diverse sentence patterns. By applying contrastive learning, SALAD enables the model to focus on learning the structural relationships between key sentence components while minimizing reliance on spurious correlations. We validate our approach through experiments on three tasks: Sentiment Classification, Sexism Detection, and Natural Language Inference. The results demonstrate that SALAD not only improves model robustness and performance across different environments but also enhances generalization to out-of-distribution datasets and cross-domain scenarios.

[Arxiv](https://arxiv.org/abs/2504.12185)