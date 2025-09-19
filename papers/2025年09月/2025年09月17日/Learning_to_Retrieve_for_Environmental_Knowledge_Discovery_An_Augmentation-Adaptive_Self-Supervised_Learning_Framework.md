# 学习检索助力环境知识发现：增强自适应自监督学习框架

发布时间：2025年09月17日

`其他` `能源与环保`

> Learning to Retrieve for Environmental Knowledge Discovery: An Augmentation-Adaptive Self-Supervised Learning Framework

# 摘要

> 环境知识的发现离不开标记的特定任务数据，但其往往受限于高昂的数据收集成本。现有机器学习方法在数据稀疏或非典型条件下通常难以泛化。为此，我们提出增强自适应自监督学习（A²SL）框架，通过检索相关观测样本增强目标生态系统的建模。具体而言，我们引入多级成对学习损失训练场景编码器，以捕捉不同场景间的相似度差异。这些学习到的相似度驱动检索机制，从不同地点或时间段为目标场景补充相关数据。此外，为更好地处理可变场景（尤其是传统模型难以应对的非典型或极端条件），我们设计增强自适应机制，通过目标数据增强有针对性地强化这些场景。以淡水生态系统为案例，我们在真实湖泊中评估了A²SL对水温和解氧动态的建模效果。实验结果表明，A²SL显著提升了预测准确性，并增强了在数据稀疏及非典型场景下的鲁棒性。尽管本研究聚焦于淡水生态系统，A²SL框架仍为各科学领域提供了广泛适用的解决方案。

> The discovery of environmental knowledge depends on labeled task-specific data, but is often constrained by the high cost of data collection. Existing machine learning approaches usually struggle to generalize in data-sparse or atypical conditions. To this end, we propose an Augmentation-Adaptive Self-Supervised Learning (A$^2$SL) framework, which retrieves relevant observational samples to enhance modeling of the target ecosystem. Specifically, we introduce a multi-level pairwise learning loss to train a scenario encoder that captures varying degrees of similarity among scenarios. These learned similarities drive a retrieval mechanism that supplements a target scenario with relevant data from different locations or time periods. Furthermore, to better handle variable scenarios, particularly under atypical or extreme conditions where traditional models struggle, we design an augmentation-adaptive mechanism that selectively enhances these scenarios through targeted data augmentation. Using freshwater ecosystems as a case study, we evaluate A$^2$SL in modeling water temperature and dissolved oxygen dynamics in real-world lakes. Experimental results show that A$^2$SL significantly improves predictive accuracy and enhances robustness in data-scarce and atypical scenarios. Although this study focuses on freshwater ecosystems, the A$^2$SL framework offers a broadly applicable solution in various scientific domains.

[Arxiv](https://arxiv.org/abs/2509.14563)