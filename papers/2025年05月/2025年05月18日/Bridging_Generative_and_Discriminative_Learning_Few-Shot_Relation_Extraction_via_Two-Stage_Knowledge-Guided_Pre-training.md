# 连接生成式与判别式学习：通过两阶段知识引导预训练实现少样本关系抽取

发布时间：2025年05月18日

`LLM应用

理由：这篇论文探讨了如何利用大型语言模型（LLMs）来解决零样本关系抽取（FSRE）中的挑战，通过创新的预训练框架结合LLMs和传统模型，提升关系抽取的性能。因此，它属于LLM的应用领域。` `关系抽取`

> Bridging Generative and Discriminative Learning: Few-Shot Relation Extraction via Two-Stage Knowledge-Guided Pre-training

# 摘要

> FSRE仍然是一个具有挑战性的任务，因为标注数据的稀缺性和现有模型有限的泛化能力。尽管LLMs通过ICL在FSRE中展现了潜力，但其通用训练目标通常导致特定任务的关系抽取性能不佳。为了解决这些问题，我们提出了TKRE（分阶段知识引导的关系抽取预训练框架），一个创新性框架，通过协同整合LLMs与传统关系抽取模型，连接生成式和判别式学习范式。TKRE引入了两个关键创新点：（1）利用LLMs生成基于解释的知识和模式约束的合成数据，解决数据稀缺性问题；（2）结合遮蔽跨度语言建模（MSLM）和跨度级对比学习（SCL）的两阶段预训练策略，增强关系推理和泛化能力。这些组件共同使TKRE能够有效处理FSRE任务。在基准数据集上的全面实验验证了TKRE的有效性，实现了FSRE的新最优性能，并突显了其在低资源场景中更广泛应用的潜力。\footnote{代码和数据已发布在https://github.com/UESTC-GQJ/TKRE。

> Few-Shot Relation Extraction (FSRE) remains a challenging task due to the scarcity of annotated data and the limited generalization capabilities of existing models. Although large language models (LLMs) have demonstrated potential in FSRE through in-context learning (ICL), their general-purpose training objectives often result in suboptimal performance for task-specific relation extraction. To overcome these challenges, we propose TKRE (Two-Stage Knowledge-Guided Pre-training for Relation Extraction), a novel framework that synergistically integrates LLMs with traditional relation extraction models, bridging generative and discriminative learning paradigms. TKRE introduces two key innovations: (1) leveraging LLMs to generate explanation-driven knowledge and schema-constrained synthetic data, addressing the issue of data scarcity; and (2) a two-stage pre-training strategy combining Masked Span Language Modeling (MSLM) and Span-Level Contrastive Learning (SCL) to enhance relational reasoning and generalization. Together, these components enable TKRE to effectively tackle FSRE tasks. Comprehensive experiments on benchmark datasets demonstrate the efficacy of TKRE, achieving new state-of-the-art performance in FSRE and underscoring its potential for broader application in low-resource scenarios. \footnote{The code and data are released on https://github.com/UESTC-GQJ/TKRE.

[Arxiv](https://arxiv.org/abs/2505.12236)