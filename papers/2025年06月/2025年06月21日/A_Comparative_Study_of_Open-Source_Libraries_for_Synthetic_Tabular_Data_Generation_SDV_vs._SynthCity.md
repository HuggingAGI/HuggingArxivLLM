# 开源库对比：SDV vs. SynthCity，谁更适合生成合成表格数据？

发布时间：2025年06月21日

`LLM应用` `数据科学` `机器学习`

> A Comparative Study of Open-Source Libraries for Synthetic Tabular Data Generation: SDV vs. SynthCity

# 摘要

> 高质量的训练数据对机器学习模型的性能至关重要，尤其是大型语言模型（LLMs）。然而，获取真实且高质量的数据对小型组织和初创企业来说颇具挑战。合成数据生成器通过复制真实数据的统计和结构特性，同时保持隐私和可扩展性，提供了一个有前景的解决方案。本研究评估了来自SDV和Synthicity两个开源库的六种表格合成数据生成器的性能。我们使用来自UCI机器学习仓库的真实数据集，包含比利时的能源消耗和环境变量，通过仅训练1,000行数据来模拟低数据场景。每个生成器被要求在1:1（1,000行）和1:10（10,000行）的输入输出比例下生成合成数据集。评估标准包括统计相似性和预测效用。统计相似性在两种情况下保持一致，但预测效用在1:10情况下显著下降。Synthicity的贝叶斯网络在两种情况下保真度最高，而SDV的TVAE在1:10设置下预测任务表现最佳。尽管两个库性能相当，但SDV凭借其优秀的文档和易用性更受从业者青睐。

> High-quality training data is critical to the performance of machine learning models, particularly Large Language Models (LLMs). However, obtaining real, high-quality data can be challenging, especially for smaller organizations and early-stage startups. Synthetic data generators provide a promising solution by replicating the statistical and structural properties of real data while preserving privacy and scalability. This study evaluates the performance of six tabular synthetic data generators from two widely used open-source libraries: SDV (Gaussian Copula, CTGAN, TVAE) and Synthicity (Bayesian Network, CTGAN, TVAE). Using a real-world dataset from the UCI Machine Learning Repository, comprising energy consumption and environmental variables from Belgium, we simulate a low-data regime by training models on only 1,000 rows. Each generator is then tasked with producing synthetic datasets under two conditions: a 1:1 (1,000 rows) and a 1:10 (10,000 rows) input-output ratio. Evaluation is conducted using two criteria: statistical similarity, measured via classical statistics and distributional metrics; and predictive utility, assessed using a "Train on Synthetic, Test on Real" approach with four regression models. While statistical similarity remained consistent across models in both scenarios, predictive utility declined notably in the 1:10 case. The Bayesian Network from Synthicity achieved the highest fidelity in both scenarios, while TVAE from SDV performed best in predictive tasks under the 1:10 setting. Although no significant performance gap was found between the two libraries, SDV stands out for its superior documentation and ease of use, making it more accessible for practitioners.

[Arxiv](https://arxiv.org/abs/2506.17847)