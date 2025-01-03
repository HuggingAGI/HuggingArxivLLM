# CultureVLM: 提升视觉-语言模型对100多个国家的文化理解能力

发布时间：2025年01月02日

`LLM应用

理由：这篇论文主要讨论了视觉-语言模型（VLMs）在文化理解方面的挑战，并提出了一个名为CultureVerse的多模态基准来提升VLMs的多文化理解能力。虽然论文中提到了微调模型（CultureVLM），但整体内容更侧重于如何应用这些模型来解决实际问题（即提升文化理解能力），而不是深入探讨模型的理论基础或构建新的模型架构。因此，将其归类为“LLM应用”更为合适。` `文化理解` `人机交互`

> CultureVLM: Characterizing and Improving Cultural Understanding of Vision-Language Models for over 100 Countries

# 摘要

> # 摘要
视觉-语言模型（VLMs）在人机交互领域取得了显著进展，但在文化理解方面仍面临挑战，常常因训练数据中的西方中心偏见而误解符号、手势和文物。本文构建了CultureVerse，一个涵盖19,682个文化概念、188个国家/地区、15个文化概念和3种问题类型的大规模多模态基准，旨在提升VLMs的多文化理解能力。我们提出了CultureVLM，通过在我们的数据集上微调，显著提升了文化理解性能。对16个模型的评估显示，西方概念表现较强，而非洲和亚洲背景下的表现较弱。在CultureVerse上微调后，模型展现了跨文化、跨大陆和跨数据集的泛化能力，且不影响其在一般VLM基准上的性能。我们还探讨了文化泛化和遗忘的见解，希望为构建更公平、更具文化意识的多模态AI系统奠定基础。

> Vision-language models (VLMs) have advanced human-AI interaction but struggle with cultural understanding, often misinterpreting symbols, gestures, and artifacts due to biases in predominantly Western-centric training data. In this paper, we construct CultureVerse, a large-scale multimodal benchmark covering 19, 682 cultural concepts, 188 countries/regions, 15 cultural concepts, and 3 question types, with the aim of characterizing and improving VLMs' multicultural understanding capabilities. Then, we propose CultureVLM, a series of VLMs fine-tuned on our dataset to achieve significant performance improvement in cultural understanding. Our evaluation of 16 models reveals significant disparities, with a stronger performance in Western concepts and weaker results in African and Asian contexts. Fine-tuning on our CultureVerse enhances cultural perception, demonstrating cross-cultural, cross-continent, and cross-dataset generalization without sacrificing performance on models' general VLM benchmarks. We further present insights on cultural generalization and forgetting. We hope that this work could lay the foundation for more equitable and culturally aware multimodal AI systems.

[Arxiv](https://arxiv.org/abs/2501.01282)