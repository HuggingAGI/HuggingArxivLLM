# 一种借助条件熵优化的多视图聚类自适应框架

发布时间：2024年12月23日

`其他` `数据处理`

> An Adaptive Framework for Multi-View Clustering Leveraging Conditional Entropy Optimization

# 摘要

> 多视图聚类（MVC）已成为从具有多种视角或模态的数据中获取宝贵见解的有力手段。尽管已有显著进步，现有的MVC方法在有效衡量视图间的一致性与互补性上存在难题，尤其易受噪声视图的不良影响，即噪声视图缺陷（NVD）。为应对这些挑战，我们提出了CE-MVC，这一新颖框架将自适应加权算法与参数解耦深度模型相融合。借助条件熵和归一化互信息的概念，CE-MVC对每个视图的信息贡献进行定量评估和加权，有利于构建稳健的统一表示。参数解耦设计能够对每个视图独立处理，有效减轻噪声影响，提升整体聚类性能。大量实验表明，CE-MVC优于现有方法，为多视图聚类任务提供了更具韧性和精准的解决方案。

> Multi-view clustering (MVC) has emerged as a powerful technique for extracting valuable insights from data characterized by multiple perspectives or modalities. Despite significant advancements, existing MVC methods struggle with effectively quantifying the consistency and complementarity among views, and are particularly susceptible to the adverse effects of noisy views, known as the Noisy-View Drawback (NVD). To address these challenges, we propose CE-MVC, a novel framework that integrates an adaptive weighting algorithm with a parameter-decoupled deep model. Leveraging the concept of conditional entropy and normalized mutual information, CE-MVC quantitatively assesses and weights the informative contribution of each view, facilitating the construction of robust unified representations. The parameter-decoupled design enables independent processing of each view, effectively mitigating the influence of noise and enhancing overall clustering performance. Extensive experiments demonstrate that CE-MVC outperforms existing approaches, offering a more resilient and accurate solution for multi-view clustering tasks.

[Arxiv](https://arxiv.org/abs/2412.17647)