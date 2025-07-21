# # 数据交易或共享中的符合性污染测试
用于数据交易或共享的符合性数据污染测试

发布时间：2025年07月18日

`其他` `数据科学` `数据管理`

> Conformal Data Contamination Tests for Trading or Sharing of Data

# 摘要

> 在机器学习任务中，数据所有者本地拥有的高质量数据量往往有限。通过与外部数据代理进行交易或共享，可以扩展高质量数据的范围。然而，数据买家在下单前需要数据质量的保障，因为外部数据可能被污染或与他们的特定学习任务无关。以往的研究主要依赖于对不同代理数据的分布假设，将质量检查推迟到事后步骤，涉及昂贵的数据估值程序。我们提出了一种分布无关、关注污染的数据共享框架，用于识别对模型个性化最有价值的外部数据代理。为此，我们引入了基于符合性离群检测严格理论基础的新双样本测试程序，以确定某个代理的数据是否超过了污染阈值。我们提出的测试，称为符合性数据污染测试，在任意污染水平下保持有效，同时通过Benjamini-Hochberg过程实现误发现率控制。在各种协作学习场景中的实证评估证明了我们方法的稳健性和有效性。总的来说，符合性数据污染测试作为一种具有统计严谨性质量保证的数据聚合通用程序，脱颖而出。

> The amount of quality data in many machine learning tasks is limited to what is available locally to data owners. The set of quality data can be expanded through trading or sharing with external data agents. However, data buyers need quality guarantees before purchasing, as external data may be contaminated or irrelevant to their specific learning task. Previous works primarily rely on distributional assumptions about data from different agents, relegating quality checks to post-hoc steps involving costly data valuation procedures. We propose a distribution-free, contamination-aware data-sharing framework that identifies external data agents whose data is most valuable for model personalization. To achieve this, we introduce novel two-sample testing procedures, grounded in rigorous theoretical foundations for conformal outlier detection, to determine whether an agent's data exceeds a contamination threshold. The proposed tests, termed conformal data contamination tests, remain valid under arbitrary contamination levels while enabling false discovery rate control via the Benjamini-Hochberg procedure. Empirical evaluations across diverse collaborative learning scenarios demonstrate the robustness and effectiveness of our approach. Overall, the conformal data contamination test distinguishes itself as a generic procedure for aggregating data with statistically rigorous quality guarantees.

[Arxiv](https://arxiv.org/abs/2507.13835)