# InspectVLM: 理论上统一，实践中却并不可靠

发布时间：2025年08月03日

`LLM应用` `工业检测` `计算机视觉`

> InspectVLM: Unified in Theory, Unreliable in Practice

# 摘要

> 统一视觉语言模型（VLMs）通过将多种视觉任务整合到单一语言驱动界面，有望简化计算机视觉流程。这种架构在工业检测领域尤其有吸引力，因为管理独立的任务模型会增加复杂性和维护成本。在本文中，我们通过InspectVLM对这一统一范式的可行性进行了深入评估。InspectVLM是基于Florence-2的VLM模型，使用我们的新大规模多模态多任务检测数据集InspectMM训练而成。尽管InspectVLM在图像分类和关键点定位任务上表现出色，但在核心检测指标上仍逊色于传统ResNet模型。值得注意的是，该模型在低提示变异性下表现脆弱，在细粒度检测中输出退化，并经常依赖记忆化的语言响应，无视视觉输入。我们的研究结果表明，尽管语言驱动的统一在理论上优雅，但目前的VLMs在视觉定位和鲁棒性方面仍无法满足精密工业检测的需求。

> Unified vision-language models (VLMs) promise to streamline computer vision pipelines by reframing multiple visual tasks such as classification, detection, and keypoint localization within a single language-driven interface. This architecture is particularly appealing in industrial inspection, where managing disjoint task-specific models introduces complexity, inefficiency, and maintenance overhead. In this paper, we critically evaluate the viability of this unified paradigm using InspectVLM, a Florence-2-based VLM trained on InspectMM, our new large-scale multimodal, multitask inspection dataset. While InspectVLM performs competitively on image-level classification and structured keypoint tasks, we find that it fails to match traditional ResNet-based models in core inspection metrics. Notably, the model exhibits brittle behavior under low prompt variability, produces degenerate outputs for fine-grained object detection, and frequently defaults to memorized language responses regardless of visual input. Our findings suggest that while language-driven unification offers conceptual elegance, current VLMs lack the visual grounding and robustness necessary for deployment in precision critical industrial inspections.

[Arxiv](https://arxiv.org/abs/2508.01921)