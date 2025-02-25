# 揭秘LLMs下游性能扩展规律：基于聚类的视角

发布时间：2025年02月24日

`LLM理论` `人工智能` `模型训练`

> Unveiling Downstream Performance Scaling of LLMs: A Clustering-Based Perspective

# 摘要

> 计算能力的飞速发展显著提升了大型语言模型 (LLMs) 的训练规模和成本。在模型训练前准确预测下游任务的表现对于高效资源分配至关重要，但目前仍面临两大主要挑战：(1) "涌现现象"，即下游性能指标仅在经过大量训练后才变得有意义，这限制了使用较小模型进行预测的能力；(2) 不均衡的任务难度分布以及缺乏一致的扩展规律，导致指标波动显著。现有性能预测方法存在准确性与可靠性不足的问题，从而阻碍了对潜在 LLM 能力的评估。  
为应对这些挑战，我们提出了一种基于难度的聚类（COD）下游性能预测框架。COD 首先通过聚类任务难度特征构建可预测的支持子集，战略性地排除非涌现型和非可扩展型聚类。所选子集上的得分成为完整评估集下游性能的有效中间预测指标。在理论支持下，我们推导出一个映射函数，将可预测子集的性能指标转换为完整评估集的指标，从而确保 LLM 下游性能的准确外推。  
该方法已应用于预测 700 亿参数 LLM 的性能扩展，为训练资源分配提供实用见解，并辅助监控训练过程。值得注意的是，COD 通过集成小型模型在 700 亿参数 LLM 上实现了卓越的预测精度，在八个关键 LLM 评估基准上实现了 1.36% 的绝对平均偏差。

> The rapid advancements in computing dramatically increase the scale and cost of training Large Language Models (LLMs). Accurately predicting downstream task performance prior to model training is crucial for efficient resource allocation, yet remains challenging due to two primary constraints: (1) the "emergence phenomenon", wherein downstream performance metrics become meaningful only after extensive training, which limits the ability to use smaller models for prediction; (2) Uneven task difficulty distributions and the absence of consistent scaling laws, resulting in substantial metric variability. Existing performance prediction methods suffer from limited accuracy and reliability, thereby impeding the assessment of potential LLM capabilities. To address these challenges, we propose a Clustering-On-Difficulty (COD) downstream performance prediction framework. COD first constructs a predictable support subset by clustering tasks based on difficulty features, strategically excluding non-emergent and non-scalable clusters. The scores on the selected subset serve as effective intermediate predictors of downstream performance on the full evaluation set. With theoretical support, we derive a mapping function that transforms performance metrics from the predictable subset to the full evaluation set, thereby ensuring accurate extrapolation of LLM downstream performance. The proposed method has been applied to predict performance scaling for a 70B LLM, providing actionable insights for training resource allocation and assisting in monitoring the training process. Notably, COD achieves remarkable predictive accuracy on the 70B LLM by leveraging an ensemble of small models, demonstrating an absolute mean deviation of 1.36% across eight important LLM evaluation benchmarks.

[Arxiv](https://arxiv.org/abs/2502.17262)