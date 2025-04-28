# 图神经网络中的个体公平性测试

发布时间：2025年04月25日

`其他` `人工智能` `图神经网络`

> Testing Individual Fairness in Graph Neural Networks

# 摘要

> 人工智能 (AI) 模型中的偏见可能导致基于性别、种族等敏感属性对群体和/或个人进行歧视的自动化决策过程。尽管在诊断和缓解各种 AI 模型中的偏见方面已有许多研究，但对图神经网络 (GNNs) 中的个体公平性研究却很少。与传统模型不同，GNNs 通过捕捉节点相互关联的图结构来建模复杂的依赖关系。然而，这种特性也让偏见更容易通过连接传播，增加了个体公平性违规检测和缓解的难度。本博士项目旨在开发一个测试框架，以评估和确保 GNNs 中的个体公平性。首先，项目将系统性地回顾文献，对现有方法进行分类，创建个体公平性分类法。随后，项目将通过调整和扩展现有技术，开发一个用于测试和确保 GNNs 公平性的框架。最后，通过工业案例研究，特别是基于图的大语言模型，验证该框架的有效性。

> The biases in artificial intelligence (AI) models can lead to automated decision-making processes that discriminate against groups and/or individuals based on sensitive properties such as gender and race. While there are many studies on diagnosing and mitigating biases in various AI models, there is little research on individual fairness in Graph Neural Networks (GNNs). Unlike traditional models, which treat data features independently and overlook their inter-relationships, GNNs are designed to capture graph-based structure where nodes are interconnected. This relational approach enables GNNs to model complex dependencies, but it also means that biases can propagate through these connections, complicating the detection and mitigation of individual fairness violations. This PhD project aims to develop a testing framework to assess and ensure individual fairness in GNNs. It first systematically reviews the literature on individual fairness, categorizing existing approaches to define, measure, test, and mitigate model biases, creating a taxonomy of individual fairness. Next, the project will develop a framework for testing and ensuring fairness in GNNs by adapting and extending current fairness testing and mitigation techniques. The framework will be evaluated through industrial case studies, focusing on graph-based large language models.

[Arxiv](https://arxiv.org/abs/2504.18353)