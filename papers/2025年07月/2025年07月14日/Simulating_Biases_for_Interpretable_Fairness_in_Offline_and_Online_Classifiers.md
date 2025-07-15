# 用于离线和在线分类器的可解释公平性，通过模拟偏见实现

发布时间：2025年07月14日

`Agent` `公平性`

> Simulating Biases for Interpretable Fairness in Offline and Online Classifiers

# 摘要

> 预测模型常通过有偏决策强化训练数据中的原有偏见。为确保公平性，缓解方法至关重要。我们通过系统生成带有特定偏见的数据集，训练机器学习分类器，并利用预测结果理解偏见嵌入过程。为此，我们开发了一个基于智能体的模型（ABM），模拟贷款申请流程，体现两个群体间的系统性偏见，生成合成数据集。通过在这些数据集上训练分类器预测贷款结果，我们评估偏见数据如何导致不公平。本研究的主要贡献包括：一个带有可控偏见注入的合成数据集生成框架，以及一种通过二阶Shapley值展示缓解措施影响的新可解释性技术。实验中，我们采用了离线和在线学习方法，并在预处理和处理阶段应用缓解措施。

> Predictive models often reinforce biases which were originally embedded in their training data, through skewed decisions. In such cases, mitigation methods are critical to ensure that, regardless of the prevailing disparities, model outcomes are adjusted to be fair. To assess this, datasets could be systematically generated with specific biases, to train machine learning classifiers. Then, predictive outcomes could aid in the understanding of this bias embedding process. Hence, an agent-based model (ABM), depicting a loan application process that represents various systemic biases across two demographic groups, was developed to produce synthetic datasets. Then, by applying classifiers trained on them to predict loan outcomes, we can assess how biased data leads to unfairness. This highlights a main contribution of this work: a framework for synthetic dataset generation with controllable bias injection. We also contribute with a novel explainability technique, which shows how mitigations affect the way classifiers leverage data features, via second-order Shapley values. In experiments, both offline and online learning approaches are employed. Mitigations are applied at different stages of the modelling pipeline, such as during pre-processing and in-processing.

[Arxiv](https://arxiv.org/abs/2507.10154)