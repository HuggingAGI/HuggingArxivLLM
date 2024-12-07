# Align-KD：为移动视觉语言模型萃取跨模态对齐知识

发布时间：2024年12月02日

`LLM应用` `人工智能` `移动设备`

> Align-KD: Distilling Cross-Modal Alignment Knowledge for Mobile Vision-Language Model

# 摘要

> 视觉语言模型（VLMs）为多模态任务赋予了强大的理解与推理能力。与此同时，诸如 AI 助手软件之类的应用，使得移动设备对强大人工智能的需求与日俱增。有人尝试将 VLMs 迁移至边缘设备以拓展其应用范畴。简化模型结构是常用手段，然而随着模型规模缩小，性能与规模的平衡愈发艰难。知识蒸馏（KD）能够在不增加规模和数据量的情况下助力模型提升综合能力。但现有的多数大型模型蒸馏技术，要么仅着眼于单模态 LLMs 的应用，要么仅让教师为学生营造新的数据环境。这些方法均未顾及 VLMs 中最为关键的跨模态对齐知识的蒸馏。我们提出了名为 Align-KD 的方法，引导学生模型学习浅层的跨模态匹配。教师还依据文本重点，帮助学生掌握视觉标记向文本嵌入空间的投影。在 Align-KD 的引领下，1.7B 的 MobileVLM V2 模型能够从 7B 的教师模型中汲取丰富知识，训练损失设计轻巧，在两个训练子集下的 6 个基准测试中，平均得分分别提升 2.0 。代码获取地址：https://github.com/fqhank/Align-KD 。

> Vision-Language Models (VLMs) bring powerful understanding and reasoning capabilities to multimodal tasks. Meanwhile, the great need for capable aritificial intelligence on mobile devices also arises, such as the AI assistant software. Some efforts try to migrate VLMs to edge devices to expand their application scope. Simplifying the model structure is a common method, but as the model shrinks, the trade-off between performance and size becomes more and more difficult. Knowledge distillation (KD) can help models improve comprehensive capabilities without increasing size or data volume. However, most of the existing large model distillation techniques only consider applications on single-modal LLMs, or only use teachers to create new data environments for students. None of these methods take into account the distillation of the most important cross-modal alignment knowledge in VLMs. We propose a method called Align-KD to guide the student model to learn the cross-modal matching that occurs at the shallow layer. The teacher also helps student learn the projection of vision token into text embedding space based on the focus of text. Under the guidance of Align-KD, the 1.7B MobileVLM V2 model can learn rich knowledge from the 7B teacher model with light design of training loss, and achieve an average score improvement of 2.0 across 6 benchmarks under two training subsets respectively. Code is available at: https://github.com/fqhank/Align-KD.

[Arxiv](https://arxiv.org/abs/2412.01282)