# RGB-Th-Bench：密集型视觉-热图像理解基准测试集（针对视觉语言模型）

发布时间：2025年03月25日

`其他` `人工智能` `视觉语言模型`

> RGB-Th-Bench: A Dense benchmark for Visual-Thermal Understanding of Vision Language Models

# 摘要

> 我们推出RGB-Th-Bench，首个专注于评估视觉语言模型（VLMs）处理RGB-热图像对能力的基准测试。尽管VLMs在视觉推理和多模态理解方面取得了显著进展，但现有评估主要局限于基于RGB的基准，导致在红外视觉任务能力评估方面存在明显空白。现有的可见-红外数据集要么是特定任务的，要么缺乏高质量标注，无法满足严格模型评估需求。为了解决这些局限性，RGB-Th-Bench构建了一个全面的评估框架，涵盖14个不同技能维度，包含1600多个专家标注的Yes/No问题。该基准采用两个准确性指标：标准的问题级别准确性和更严格的技能级别准确性，后者评估模型在每个技能维度内多个问题上的鲁棒性。这种设计确保了对模型性能的全面评估，包括对抗性和幻觉响应的韧性。我们在19个最先进的VLMs上进行了广泛评估，揭示了在RGB-热理解方面存在显著性能差异。实验结果显示，即使是最强大的模型也难以准确理解热图像，其性能严重受限于基于RGB的能力。此外，预训练中缺乏大规模特定应用和专家标注的热-文字对数据集是导致性能差距的重要原因。RGB-Th-Bench凸显了进一步推进多模态学习的紧迫性，以弥合可见与热图像理解之间的差距。该数据集可通过此链接获取，评估代码也将公开发布。

> We introduce RGB-Th-Bench, the first benchmark designed to evaluate the ability of Vision-Language Models (VLMs) to comprehend RGB-Thermal image pairs. While VLMs have demonstrated remarkable progress in visual reasoning and multimodal understanding, their evaluation has been predominantly limited to RGB-based benchmarks, leaving a critical gap in assessing their capabilities in infrared vision tasks. Existing visible-infrared datasets are either task-specific or lack high-quality annotations necessary for rigorous model evaluation. To address these limitations, RGB-Th-Bench provides a comprehensive evaluation framework covering 14 distinct skill dimensions, with a total of 1,600+ expert-annotated Yes/No questions. The benchmark employs two accuracy metrics: a standard question-level accuracy and a stricter skill-level accuracy, which evaluates model robustness across multiple questions within each skill dimension. This design ensures a thorough assessment of model performance, including resilience to adversarial and hallucinated responses. We conduct extensive evaluations on 19 state-of-the-art VLMs, revealing significant performance gaps in RGB-Thermal understanding. Our results show that even the strongest models struggle with thermal image comprehension, with performance heavily constrained by their RGB-based capabilities. Additionally, the lack of large-scale application-specific and expert-annotated thermal-caption-pair datasets in pre-training is an important reason of the observed performance gap. RGB-Th-Bench highlights the urgent need for further advancements in multimodal learning to bridge the gap between visible and thermal image understanding. The dataset is available through this link, and the evaluation code will also be made publicly available.

[Arxiv](https://arxiv.org/abs/2503.19654)