# 大型语言模型助力生成高保真伪标签，训练稳健的放射科报告分类器

发布时间：2025年05月03日

`LLM应用`

> High-Fidelity Pseudo-label Generation by Large Language Models for Training Robust Radiology Report Classifiers

# 摘要

> 胸部X光报告的自动标注对实现下游任务至关重要，包括训练基于图像的诊断模型、开展人群健康研究以及提供临床决策支持。然而，自由文本报告中的高度变异性、复杂性以及大量否定和不确定性表达，给传统自然语言处理方法带来了巨大挑战。尽管大型语言模型（LLMs）在文本理解方面表现出色，但受限于计算成本和速度，它们在大规模高效标注任务中的直接应用仍受到限制。

本文提出了一种创新的两阶段框架——DeBERTa-RAD，结合了先进的LLM伪标注能力和高效的DeBERTa知识蒸馏，以实现精准快速的胸部X光报告标注。我们利用先进的LLM为大量报告生成高质量伪标签，包括确定性状态。随后，采用定制的知识蒸馏策略，基于这些伪标签数据训练DeBERTa-Base模型。

在专家标注的MIMIC-500基准测试中，DeBERTa-RAD达到了0.9120的Macro F1分数，显著超越了现有基于规则的系统、微调的Transformer模型以及直接的LLM推理，同时保持了适用于高吞吐量应用的实用推理速度。我们的分析表明，该方法在处理不确定发现方面表现尤为突出。

这项工作展示了通过将LLM能力与高效蒸馏训练的学生模型相结合，克服数据标注瓶颈、实现高性能医学文本处理的可行路径。


> Automated labeling of chest X-ray reports is essential for enabling downstream tasks such as training image-based diagnostic models, population health studies, and clinical decision support. However, the high variability, complexity, and prevalence of negation and uncertainty in these free-text reports pose significant challenges for traditional Natural Language Processing methods. While large language models (LLMs) demonstrate strong text understanding, their direct application for large-scale, efficient labeling is limited by computational cost and speed. This paper introduces DeBERTa-RAD, a novel two-stage framework that combines the power of state-of-the-art LLM pseudo-labeling with efficient DeBERTa-based knowledge distillation for accurate and fast chest X-ray report labeling. We leverage an advanced LLM to generate high-quality pseudo-labels, including certainty statuses, for a large corpus of reports. Subsequently, a DeBERTa-Base model is trained on this pseudo-labeled data using a tailored knowledge distillation strategy. Evaluated on the expert-annotated MIMIC-500 benchmark, DeBERTa-RAD achieves a state-of-the-art Macro F1 score of 0.9120, significantly outperforming established rule-based systems, fine-tuned transformer models, and direct LLM inference, while maintaining a practical inference speed suitable for high-throughput applications. Our analysis shows particular strength in handling uncertain findings. This work demonstrates a promising path to overcome data annotation bottlenecks and achieve high-performance medical text processing through the strategic combination of LLM capabilities and efficient student models trained via distillation.

[Arxiv](https://arxiv.org/abs/2505.01693)