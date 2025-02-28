# 大型语言模型的几何知识编辑工具：GeoEdit

发布时间：2025年02月27日

`LLM理论` `人工智能`

> GeoEdit: Geometric Knowledge Editing for Large Language Models

# 摘要

> 定期更新对于保持大型语言模型（LLMs）的知识时效性至关重要。为此，研究人员开发了多种模型编辑方法，用于更新LLMs中的特定知识。然而，基于训练的方法在保留无关通用知识的同时，难以有效整合新知识。为解决这一难题，我们提出了一种名为几何知识编辑（GeoEdit）的新颖框架。通过分析微调过程中参数更新的几何关系，GeoEdit能够区分与新知识更新相关的神经元和与通用知识扰动相关的神经元。利用一种有方向的知识识别方法，我们避免更新与现有知识方向大致正交的神经元，从而保留了模型的泛化能力。对于剩余的神经元，我们整合旧知识和新知识的对齐方向，并对相反方向采用“先遗忘再学习”的编辑策略。此外，我们引入了一种重要性引导的任务向量融合技术，该技术不仅能过滤冗余信息，还能提供自适应的神经元级别加权，进一步提升了模型编辑的性能。在两个公开数据集上的大量实验结果表明，GeoEdit显著优于现有的最先进的方法。

> Regular updates are essential for maintaining up-to-date knowledge in large language models (LLMs). Consequently, various model editing methods have been developed to update specific knowledge within LLMs. However, training-based approaches often struggle to effectively incorporate new knowledge while preserving unrelated general knowledge. To address this challenge, we propose a novel framework called Geometric Knowledge Editing (GeoEdit). GeoEdit utilizes the geometric relationships of parameter updates from fine-tuning to differentiate between neurons associated with new knowledge updates and those related to general knowledge perturbations. By employing a direction-aware knowledge identification method, we avoid updating neurons with directions approximately orthogonal to existing knowledge, thus preserving the model's generalization ability. For the remaining neurons, we integrate both old and new knowledge for aligned directions and apply a "forget-then-learn" editing strategy for opposite directions. Additionally, we introduce an importance-guided task vector fusion technique that filters out redundant information and provides adaptive neuron-level weighting, further enhancing model editing performance. Extensive experiments on two publicly available datasets demonstrate the superiority of GeoEdit over existing state-of-the-art methods.

[Arxiv](https://arxiv.org/abs/2502.19953)