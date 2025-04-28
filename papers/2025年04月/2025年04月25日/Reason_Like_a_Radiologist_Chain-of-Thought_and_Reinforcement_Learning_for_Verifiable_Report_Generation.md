# 像放射科医生一样推理：思路链与强化学习在可验证报告生成中的应用

发布时间：2025年04月25日

`LLM应用` `医学影像`

> Reason Like a Radiologist: Chain-of-Thought and Reinforcement Learning for Verifiable Report Generation

# 摘要

> 放射报告生成对效率至关重要，但现有模型缺乏专家式的结构化推理能力，导致临床信任和可解释性不足，因为它们无法将视觉发现与精确解剖位置关联。本文提出BoxMed-RL，一个开创性的统一训练框架，用于生成可空间验证且可解释的放射报告。BoxMed-RL基于大型视觉语言模型，通过两个创新阶段重新定义了报告生成：(1) 预训练阶段，我们通过医学概念学习优化模型，利用Chain-of-Thought监督模拟放射科医生的工作流程，随后应用空间验证强化学习，将医学发现与边界框对齐。 (2) 下游适配器阶段，我们冻结预训练权重并训练适配器，确保生成流畅且临床可信的报告。BoxMed-RL精准模拟放射科医生的工作流程，迫使模型将高级医学概念与明确解剖证据结合。在公共数据集上的实验显示，BoxMed-RL在METEOR和ROUGE-L指标上较现有方法平均提升7%，基于大型语言模型的指标平均提升5%，凸显其生成高质量放射报告的强劲实力。

> Radiology report generation is critical for efficiency but current models lack the structured reasoning of experts, hindering clinical trust and explainability by failing to link visual findings to precise anatomical locations. This paper introduces BoxMed-RL, a groundbreaking unified training framework for generating spatially verifiable and explainable radiology reports. Built on a large vision-language model, BoxMed-RL revolutionizes report generation through two integrated phases: (1) In the Pretraining Phase, we refine the model via medical concept learning, using Chain-of-Thought supervision to internalize the radiologist-like workflow, followed by spatially verifiable reinforcement, which applies reinforcement learning to align medical findings with bounding boxes. (2) In the Downstream Adapter Phase, we freeze the pretrained weights and train a downstream adapter to ensure fluent and clinically credible reports. This framework precisely mimics radiologists' workflow, compelling the model to connect high-level medical concepts with definitive anatomical evidence. Extensive experiments on public datasets demonstrate that BoxMed-RL achieves an average 7% improvement in both METEOR and ROUGE-L metrics compared to state-of-the-art methods. An average 5% improvement in large language model-based metrics further underscores BoxMed-RL's robustness in generating high-quality radiology reports.

[Arxiv](https://arxiv.org/abs/2504.18453)