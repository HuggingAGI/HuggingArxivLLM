# MM-PoE：借助多模态模型的排除过程实现多项选择推理

发布时间：2024年12月09日

`LLM应用` `视觉推理` `多模态模型`

> MM-PoE: Multiple Choice Reasoning via. Process of Elimination using Multi-Modal Models

# 摘要

> 这篇论文引入了借助多模态模型的排除过程来实现多项选择推理，即多模态排除过程（MM-PoE）。此创新方法旨在提升视觉语言模型（VLMs）在多项选择视觉推理任务中的效能。有别于独立评估每个选项的传统方式，MM-PoE 采用了两步评分模式，先是识别并排除不合理的选项，然后聚焦于最有可能的剩余选项。这种方法效仿了人类的应试策略，即人们通常会先排除明显错误的答案，再选择最佳答案。我们在三个基准数据集上开展的实证评估显示，MM-PoE 显著提升了当代顶尖 VLMs 的零样本和少样本性能。重要的是，该方法不仅将排除过程的应用拓展至多模态情境，还允许进行少样本实验，从而解决了仅在零样本设置以及仅在纯语言框架中使用 PoE 的两大主要限制。因此，MM-PoE 不但优化了 VLMs 的推理能力，还拓宽了其在复杂视觉问答场景中的适用性。支持我们工作的所有代码和文档均可在 https://pypi.org/project/mm-poe/ 找到，方便研究人员和从业者轻松整合并进一步开发这些技术。

> This paper introduces Multiple Choice Reasoning via. Process of Elimination using Multi-Modal models, herein referred to as Multi-Modal Process of Elimination (MM-PoE). This novel methodology is engineered to augment the efficacy of Vision-Language Models (VLMs) in multiple-choice visual reasoning tasks. Diverging from conventional approaches that evaluate each option independently, MM-PoE employs a dual-step scoring paradigm that initially identifies and excludes implausible choices, subsequently concentrating on the most probable remaining options. This method emulates human test-taking strategies, where individuals typically eliminate clearly incorrect answers prior to selecting the optimal response. Our empirical evaluations, conducted across three benchmark datasets, reveal that MM-PoE significantly improves both zero-shot and few-shot performance of contemporary state-of-the-art VLMs. Critically, this approach not only broadens the application of the elimination process to multi-modal contexts but also allows few-shot experiments, thereby addressing two principal limitations concerning usage of PoE only in zero-shot settings and only with a language-only framework. As a result, MM-PoE not only refines the reasoning capabilities of VLMs but also broadens their applicability to complex visual question-answering scenarios. All code and documentation supporting our work are available at https://pypi.org/project/mm-poe/, enabling researchers and practitioners to easily integrate and further develop these techniques.

[Arxiv](https://arxiv.org/abs/2412.07148)