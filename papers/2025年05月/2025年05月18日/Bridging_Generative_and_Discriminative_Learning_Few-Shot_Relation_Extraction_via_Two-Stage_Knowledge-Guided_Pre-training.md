# 连接生成与判别学习：通过两阶段知识引导预训练实现少样本关系抽取

发布时间：2025年05月18日

`LLM应用

理由：这篇论文探讨了如何将大型语言模型（LLMs）应用于小样本关系抽取（FSRE）任务，提出了一种结合LLMs和传统模型的框架，展示了其在特定任务中的应用和改进，属于LLM应用类别。` `机器学习`

> Bridging Generative and Discriminative Learning: Few-Shot Relation Extraction via Two-Stage Knowledge-Guided Pre-training

# 摘要

> 小样本关系抽取（FSRE）因标注数据稀缺和模型泛化能力有限而极具挑战性。尽管大型语言模型（LLMs）通过上下文学习（ICL）在FSRE中展现出潜力，但其通用训练目标常导致特定任务表现不佳。为解决这一问题，我们提出了TKRE框架，将LLMs与传统关系抽取模型协同结合，连接生成式与判别式学习范式。TKRE的两大创新在于：（1）利用LLMs生成解释驱动知识和模式约束合成数据，缓解数据稀缺问题；（2）结合遮蔽跨度语言建模（MSLM）和跨度级对比学习（SCL）的两阶段预训练策略，提升关系推理与泛化能力。实验表明，TKRE在FSRE任务中实现了新最先进性能，展现了其在低资源场景中的广泛应用潜力。\footnote{代码和数据已发布于https://github.com/UESTC-GQJ/TKRE。}

> Few-Shot Relation Extraction (FSRE) remains a challenging task due to the scarcity of annotated data and the limited generalization capabilities of existing models. Although large language models (LLMs) have demonstrated potential in FSRE through in-context learning (ICL), their general-purpose training objectives often result in suboptimal performance for task-specific relation extraction. To overcome these challenges, we propose TKRE (Two-Stage Knowledge-Guided Pre-training for Relation Extraction), a novel framework that synergistically integrates LLMs with traditional relation extraction models, bridging generative and discriminative learning paradigms. TKRE introduces two key innovations: (1) leveraging LLMs to generate explanation-driven knowledge and schema-constrained synthetic data, addressing the issue of data scarcity; and (2) a two-stage pre-training strategy combining Masked Span Language Modeling (MSLM) and Span-Level Contrastive Learning (SCL) to enhance relational reasoning and generalization. Together, these components enable TKRE to effectively tackle FSRE tasks. Comprehensive experiments on benchmark datasets demonstrate the efficacy of TKRE, achieving new state-of-the-art performance in FSRE and underscoring its potential for broader application in low-resource scenarios. \footnote{The code and data are released on https://github.com/UESTC-GQJ/TKRE.

[Arxiv](https://arxiv.org/abs/2505.12236)