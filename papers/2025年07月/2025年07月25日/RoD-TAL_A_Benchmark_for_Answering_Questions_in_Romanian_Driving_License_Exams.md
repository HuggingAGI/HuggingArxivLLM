# # RoD-TAL：罗马尼亚驾驶考试问答基准

发布时间：2025年07月25日

`RAG

摘要中详细讨论了检索增强生成（RAG）管道在法律教育中的应用，评估了其在信息检索和问答任务中的表现，因此归类为RAG。` `法律教育` `多模态`

> RoD-TAL: A Benchmark for Answering Questions in Romanian Driving License Exams

# 摘要

> AI与法律系统的交汇点在支持法律教育方面日益增长的需求，尤其是在资源匮乏的语言如罗马尼亚语中。本研究旨在评估大型语言模型（LLMs）和视觉-语言模型（VLMs）在理解与推理罗马尼亚驾驶法方面的能力，通过文本和视觉问答任务实现。为此，我们引入了RoD-TAL，一个全新的多模态数据集，包含罗马尼亚驾驶考试问题，涵盖文本和图像形式，同时附带标注的法律参考和人工解释。我们实现了并评估了检索增强生成（RAG）管道、密集检索器和优化推理模型在信息检索（IR）、问答（QA）、视觉IR和视觉QA等任务中的表现。实验表明，领域特定的微调显著提升了检索性能。同时，链式思维提示和专用推理模型提高了问答准确性，超越了通过驾驶考试所需的最低分数。然而，视觉推理仍然具有挑战性，凸显了将LLMs和VLMs应用于法律教育的潜力与局限。

> The intersection of AI and legal systems presents a growing need for tools that support legal education, particularly in under-resourced languages such as Romanian. In this work, we aim to evaluate the capabilities of Large Language Models (LLMs) and Vision-Language Models (VLMs) in understanding and reasoning about Romanian driving law through textual and visual question-answering tasks. To facilitate this, we introduce RoD-TAL, a novel multimodal dataset comprising Romanian driving test questions, text-based and image-based, alongside annotated legal references and human explanations. We implement and assess retrieval-augmented generation (RAG) pipelines, dense retrievers, and reasoning-optimized models across tasks including Information Retrieval (IR), Question Answering (QA), Visual IR, and Visual QA. Our experiments demonstrate that domain-specific fine-tuning significantly enhances retrieval performance. At the same time, chain-of-thought prompting and specialized reasoning models improve QA accuracy, surpassing the minimum grades required to pass driving exams. However, visual reasoning remains challenging, highlighting the potential and the limitations of applying LLMs and VLMs to legal education.

[Arxiv](https://arxiv.org/abs/2507.19666)