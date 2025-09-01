# 特征空间平面搜索器：面向可解释性与计算效率的通用领域自适应框架

发布时间：2025年08月26日

`其他` `基础理论`

> Feature-Space Planes Searcher: A Universal Domain Adaptation Framework for Interpretability and Computational Efficiency

# 摘要

> 领域偏移是指模型从有标签的源领域迁移到无标签的目标领域时性能下降，这一直是深度学习系统部署面临的难题。目前的无监督领域自适应（UDA）方法大多依赖微调特征提取器，这种方式存在效率低、可解释性差、对现代架构扩展性不足等局限。
  我们的分析发现，在大规模数据上预训练的模型，其特征空间存在领域不变的几何模式——类内聚集、类间分离，因此保留了可迁移的判别结构。这些发现说明，领域偏移主要体现为边界错位，而非特征退化。
  不同于微调整个预训练模型（可能导致不可预测的特征扭曲），我们提出了特征空间平面搜索器（FPS）：一种全新的领域自适应框架，它通过利用这些几何模式来优化决策边界，同时保持特征编码器冻结。这种精简方法支持对自适应过程的解释性分析，同时通过离线特征提取大幅降低内存和计算成本，可在单个计算周期内完成全数据集优化。
  在公共基准测试中，FPS的性能与现有最优方法相当甚至更优。FPS能高效扩展至多模态大模型，并在蛋白质结构预测、遥感分类、地震检测等多个领域展现出广泛适用性。我们期望FPS能为迁移学习，尤其是领域自适应任务，提供一种简单、高效且可推广的新范式。

> Domain shift, characterized by degraded model performance during transition from labeled source domains to unlabeled target domains, poses a persistent challenge for deploying deep learning systems. Current unsupervised domain adaptation (UDA) methods predominantly rely on fine-tuning feature extractors - an approach limited by inefficiency, reduced interpretability, and poor scalability to modern architectures.
  Our analysis reveals that models pretrained on large-scale data exhibit domain-invariant geometric patterns in their feature space, characterized by intra-class clustering and inter-class separation, thereby preserving transferable discriminative structures. These findings indicate that domain shifts primarily manifest as boundary misalignment rather than feature degradation.
  Unlike fine-tuning entire pre-trained models - which risks introducing unpredictable feature distortions - we propose the Feature-space Planes Searcher (FPS): a novel domain adaptation framework that optimizes decision boundaries by leveraging these geometric patterns while keeping the feature encoder frozen. This streamlined approach enables interpretative analysis of adaptation while substantially reducing memory and computational costs through offline feature extraction, permitting full-dataset optimization in a single computation cycle.
  Evaluations on public benchmarks demonstrate that FPS achieves competitive or superior performance to state-of-the-art methods. FPS scales efficiently with multimodal large models and shows versatility across diverse domains including protein structure prediction, remote sensing classification, and earthquake detection. We anticipate FPS will provide a simple, effective, and generalizable paradigm for transfer learning, particularly in domain adaptation tasks. .

[Arxiv](https://arxiv.org/abs/2508.18693)