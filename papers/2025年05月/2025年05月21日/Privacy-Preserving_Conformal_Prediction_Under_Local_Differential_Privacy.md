# # **隐私保护的一致性预测**  
在局部差分隐私约束下的隐私保护符合性预测

发布时间：2025年05月21日

`其他` `人工智能`

> Privacy-Preserving Conformal Prediction Under Local Differential Privacy

# 摘要

> 符合性预测（CP）能提供一组候选类，保证包含真实类的概率。然而，这种技术通常依赖于带有干净标签的校准集。我们针对聚合器不可信且只能访问扰动后真实标签的隐私敏感场景，提出两种互补方法，基于局部差分隐私（LDP）。第一种方法中，用户不直接访问模型，而是提供输入特征和使用k元随机响应的扰动标签。第二种方法在更严格的隐私约束下，用户通过二分搜索响应向符合性分数添加噪声。此方法需要访问分类模型，但保留数据和标签隐私。两种方法均直接从噪声数据计算符合性阈值，无需访问真实标签。我们证明了有限样本覆盖保证，并展示了在严重随机化下的稳健覆盖。此方法成功统一了强局部隐私与预测不确定性控制，使其非常适合医学影像或大型语言模型查询等敏感应用，无论用户是否能够（或愿意）计算自身分数。

> Conformal prediction (CP) provides sets of candidate classes with a guaranteed probability of containing the true class. However, it typically relies on a calibration set with clean labels. We address privacy-sensitive scenarios where the aggregator is untrusted and can only access a perturbed version of the true labels. We propose two complementary approaches under local differential privacy (LDP). In the first approach, users do not access the model but instead provide their input features and a perturbed label using a k-ary randomized response. In the second approach, which enforces stricter privacy constraints, users add noise to their conformity score by binary search response. This method requires access to the classification model but preserves both data and label privacy. Both approaches compute the conformal threshold directly from noisy data without accessing the true labels. We prove finite-sample coverage guarantees and demonstrate robust coverage even under severe randomization. This approach unifies strong local privacy with predictive uncertainty control, making it well-suited for sensitive applications such as medical imaging or large language model queries, regardless of whether users can (or are willing to) compute their own scores.

[Arxiv](https://arxiv.org/abs/2505.15721)