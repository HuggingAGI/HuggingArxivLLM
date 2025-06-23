# TRUST：透明、健壮且超稀疏的树模型

发布时间：2025年06月18日

`LLM应用` `机器学习`

> TRUST: Transparent, Robust and Ultra-Sparse Trees

# 摘要

> 分段常数回归树因良好的可解释性而广受欢迎，但其预测准确性往往不及随机森林等黑箱模型。我们提出了一种名为TRUST（透明、稳健且超稀疏树）的新型回归树模型，它兼具随机森林的高准确性和浅层决策树与稀疏线性模型的可解释性。TRUST还通过借助大型语言模型生成定制化且易于理解的解释，进一步提升了模型的透明度。在合成数据和真实世界基准数据集上的大量实验表明，TRUST在预测准确性上超越了CART、Lasso、节点收获等可解释模型，同时其准确率可与随机森林相媲美，并在准确性和可解释性方面显著优于M5'，这是一个概念上相关的成熟模型。


> Piecewise-constant regression trees remain popular for their interpretability, yet often lag behind black-box models like Random Forest in predictive accuracy. In this work, we introduce TRUST (Transparent, Robust, and Ultra-Sparse Trees), a novel regression tree model that combines the accuracy of Random Forests with the interpretability of shallow decision trees and sparse linear models. TRUST further enhances transparency by leveraging Large Language Models to generate tailored, user-friendly explanations. Extensive validation on synthetic and real-world benchmark datasets demonstrates that TRUST consistently outperforms other interpretable models -- including CART, Lasso, and Node Harvest -- in predictive accuracy, while matching the accuracy of Random Forest and offering substantial gains in both accuracy and interpretability over M5', a well-established model that is conceptually related.

[Arxiv](https://arxiv.org/abs/2506.15791)