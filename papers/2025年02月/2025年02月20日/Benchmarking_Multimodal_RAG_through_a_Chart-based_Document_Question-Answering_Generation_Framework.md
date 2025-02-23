# 评估多模态 RAG：基于图表的文档问答生成框架

发布时间：2025年02月20日

`RAG` `问答系统` `文档理解`

> Benchmarking Multimodal RAG through a Chart-based Document Question-Answering Generation Framework

# 摘要

> 多模态检索增强生成（MRAG）通过整合外部知识增强了推理能力。然而，现有的基准测试主要集中在简单的图像-文本交互上，忽视了在现实世界应用中广泛存在的复杂视觉格式，如图表。为此，我们提出了基于图表的MRAG（Chart-based MRAG）这一新任务。为了高效生成高质量的评估样本，我们开发了CHARt-based document question-answering GEneration（CHARGE），一个通过结构化关键点提取、跨模态验证和基于关键点生成来创建评估数据的框架。通过将CHARGE与专家验证相结合，我们构建了Chart-MRAG Bench，这是一个全面的基于图表的MRAG评估基准，包含来自8个现实文档领域的4,738个问答对。我们的评估揭示了当前方法的三大局限：（1）统一的多模态嵌入检索方法在图表场景中表现欠佳，（2）即使在真实检索条件下，最先进的多模态大语言模型（MLLMs）也只能达到58.19%的正确率和73.87%的覆盖率，（3）MLLMs在基于图表的MRAG推理中表现出持续的文本优于视觉模态的偏好。CHARGE和Chart-MRAG Bench已发布在https://github.com/Nomothings/CHARGE.git。

> Multimodal Retrieval-Augmented Generation (MRAG) enhances reasoning capabilities by integrating external knowledge. However, existing benchmarks primarily focus on simple image-text interactions, overlooking complex visual formats like charts that are prevalent in real-world applications. In this work, we introduce a novel task, Chart-based MRAG, to address this limitation. To semi-automatically generate high-quality evaluation samples, we propose CHARt-based document question-answering GEneration (CHARGE), a framework that produces evaluation data through structured keypoint extraction, crossmodal verification, and keypoint-based generation. By combining CHARGE with expert validation, we construct Chart-MRAG Bench, a comprehensive benchmark for chart-based MRAG evaluation, featuring 4,738 question-answering pairs across 8 domains from real-world documents. Our evaluation reveals three critical limitations in current approaches: (1) unified multimodal embedding retrieval methods struggles in chart-based scenarios, (2) even with ground-truth retrieval, state-of-the-art MLLMs achieve only 58.19% Correctness and 73.87% Coverage scores, and (3) MLLMs demonstrate consistent text-over-visual modality bias during Chart-based MRAG reasoning. The CHARGE and Chart-MRAG Bench are released at https://github.com/Nomothings/CHARGE.git.

[Arxiv](https://arxiv.org/abs/2502.14864)