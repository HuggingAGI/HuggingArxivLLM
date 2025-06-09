# 生成、验证、迭代：构建广义视觉关系检测的新框架

发布时间：2025年06月05日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLMs）在视觉关系检测中的应用，提出了一种基于LLM的迭代视觉定位框架，用于改进模型对未见谓词的泛化能力。研究主要集中在如何利用LLM生成结构化的关联先验，并通过与视觉模型的交互来提升性能。这属于将LLM技术应用于具体领域，因此归类为LLM应用。` `视觉智能` `视觉关系检测`

> Hallucinate, Ground, Repeat: A Framework for Generalized Visual Relationship Detection

# 摘要

> 理解物体间关系是视觉智能的核心，广泛应用于具身智能、辅助系统和场景理解。然而，现有视觉关系检测（VRD）模型大多依赖固定谓词集，限制了对新交互的泛化能力。关键挑战在于无法对语义合理但未标注的关系进行视觉定位。本研究提出了一种基于大型语言模型（LLMs）的迭代视觉定位框架，作为结构化的关联先验。受期望最大化（EM）启发，我们的方法通过LLM从检测对象生成候选场景图（期望），并训练视觉模型使其假设与感知证据对齐（最大化）。这一过程超越了标注数据，引导关系理解并实现对未见谓词的泛化。我们在Visual Genome上引入了一个新的开放世界VRD基准，包含21个保留谓词，并在已见、未见和混合三种设置下评估。我们的模型在谓词分类上分别在三个数据集上实现了15.9、13.1和11.7的平均召回率（mR@50），优于仅LLM、少样本和无偏见基线。这些结果凸显了基于LLM先验在可扩展开放世界视觉理解中的潜力。


> Understanding relationships between objects is central to visual intelligence, with applications in embodied AI, assistive systems, and scene understanding. Yet, most visual relationship detection (VRD) models rely on a fixed predicate set, limiting their generalization to novel interactions. A key challenge is the inability to visually ground semantically plausible, but unannotated, relationships hypothesized from external knowledge. This work introduces an iterative visual grounding framework that leverages large language models (LLMs) as structured relational priors. Inspired by expectation-maximization (EM), our method alternates between generating candidate scene graphs from detected objects using an LLM (expectation) and training a visual model to align these hypotheses with perceptual evidence (maximization). This process bootstraps relational understanding beyond annotated data and enables generalization to unseen predicates. Additionally, we introduce a new benchmark for open-world VRD on Visual Genome with 21 held-out predicates and evaluate under three settings: seen, unseen, and mixed. Our model outperforms LLM-only, few-shot, and debiased baselines, achieving mean recall (mR@50) of 15.9, 13.1, and 11.7 on predicate classification on these three sets. These results highlight the promise of grounded LLM priors for scalable open-world visual understanding.

[Arxiv](https://arxiv.org/abs/2506.05651)