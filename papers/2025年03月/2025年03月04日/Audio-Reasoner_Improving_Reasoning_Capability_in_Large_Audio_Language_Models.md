# Audio-Reasoner：增强大型音频语言模型的推理性能

发布时间：2025年03月04日

`LLM应用` `音频处理` `推理系统`

> Audio-Reasoner: Improving Reasoning Capability in Large Audio Language Models

# 摘要

> 多模态推理的最新进展大多忽视了音频模态。我们推出Audio-Reasoner——一个专注于音频任务深度推理的大规模音频语言模型。通过精心整理，我们创建了一个大规模、多样化且标注简洁的多任务音频数据集。随后，利用闭源模型进行二次标注、问答生成以及结构化COT（Co-think）过程。这些数据集共同构成了一个高质量的推理数据集，包含120万个推理丰富样本，命名为CoTA。遵循推理扩展原则，我们在CoTA上训练Audio-Reasoner，使其在音频推理中展现出强大的逻辑能力。实验结果表明，该模型在关键基准测试中表现出色，包括MMAU-mini（+25.42%）、AIR-Bench聊天/基础模型（+14.57%/+10.13%）和MELD（+8.01%）。研究发现，结构化COT训练是推动音频推理能力的核心要素。

> Recent advancements in multimodal reasoning have largely overlooked the audio modality. We introduce Audio-Reasoner, a large-scale audio language model for deep reasoning in audio tasks. We meticulously curated a large-scale and diverse multi-task audio dataset with simple annotations. Then, we leverage closed-source models to conduct secondary labeling, QA generation, along with structured COT process. These datasets together form a high-quality reasoning dataset with 1.2 million reasoning-rich samples, which we name CoTA. Following inference scaling principles, we train Audio-Reasoner on CoTA, enabling it to achieve great logical capabilities in audio reasoning. Experiments show state-of-the-art performance across key benchmarks, including MMAU-mini (+25.42%), AIR-Bench chat/foundation(+14.57%/+10.13%), and MELD (+8.01%). Our findings stress the core of structured CoT training in advancing audio reasoning.

[Arxiv](https://arxiv.org/abs/2503.02318)