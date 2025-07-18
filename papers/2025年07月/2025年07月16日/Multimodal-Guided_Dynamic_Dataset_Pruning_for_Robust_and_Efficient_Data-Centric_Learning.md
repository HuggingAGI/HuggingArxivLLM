# 基于多模态引导的动态数据集剪枝，实现强健且高效的数据为中心的学习

发布时间：2025年07月16日

`其他` `数据科学` `机器学习`

> Multimodal-Guided Dynamic Dataset Pruning for Robust and Efficient Data-Centric Learning

# 摘要

> 现代深度模型通常基于大规模真实数据集进行训练，这些数据集中数据质量参差不齐且数据冗余现象普遍。数据-centric方法如数据集剪枝在提升训练效率和模型性能方面展现出巨大潜力。然而，现有大多数方法依赖静态启发式规则或特定任务指标，这限制了它们在跨领域场景下的鲁棒性和泛化能力。在本研究中，我们提出了一种动态数据集剪枝框架，该框架能够根据任务驱动的难度和跨模态语义一致性自适应地选择训练样本。通过引入预训练多模态基础模型提供的监督信号，我们的方法能够有效捕捉训练动态并筛选出无用样本。这项研究凸显了跨模态对齐在实现稳健样本选择中的潜力，推动数据-centric学习向更高效和更可靠的实践方向发展，适用于多种应用场景。

> Modern deep models are trained on large real-world datasets, where data quality varies and redundancy is common. Data-centric approaches such as dataset pruning have shown promise in improving training efficiency and model performance. However, most existing methods rely on static heuristics or task-specific metrics, limiting their robustness and generalizability across domains. In this work, we introduce a dynamic dataset pruning framework that adaptively selects training samples based on both task-driven difficulty and cross-modality semantic consistency. By incorporating supervision from pretrained multimodal foundation models, our approach captures training dynamics while effectively filtering out uninformative samples. Our work highlights the potential of integrating cross-modality alignment for robust sample selection, advancing data-centric learning toward more efficient and robust practices across application domains.

[Arxiv](https://arxiv.org/abs/2507.12750)