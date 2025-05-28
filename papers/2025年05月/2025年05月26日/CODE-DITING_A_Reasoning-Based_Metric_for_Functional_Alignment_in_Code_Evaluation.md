# CODE-DITING：基于推理的代码评估功能对齐度量

发布时间：2025年05月26日

`LLM应用` `软件开发` `人工智能`

> CODE-DITING: A Reasoning-Based Metric for Functional Alignment in Code Evaluation

# 摘要

> 可信的代码片段评估方法在神经代码生成中发挥着关键作用。传统方法依赖参考解决方案或可执行测试用例，存在灵活性和可扩展性的局限。最近，LLM-as-Judge方法通过直接评估问题描述与生成代码的功能一致性，提供了一种有前景的替代方案。

为了全面了解这些LLM-as-Judge方法的现状，我们对三个多样化数据集进行了系统性实证研究。研究发现，基于通用基础模型的方法虽能实现良好性能，但依赖复杂提示且缺乏可解释性；而基于推理基础模型的方法则在可解释性方面表现更优，提示更简单，但因参数规模庞大需要大量计算资源。

为解决这些局限，我们提出了CODE-DITING，一种在准确性、效率和可解释性之间取得平衡的新颖代码评估方法。通过数据蒸馏框架，我们将DeepSeek-R1671B的推理能力成功迁移到CODE-DITING 1.5B和7B模型中，显著提升了评估的可解释性并降低了计算成本。

在推理过程中采用多数投票策略，CODE-DITING 1.5B超越了所有同参数量模型，性能媲美参数规模大五倍的模型。CODE-DITING 7B更超越GPT-4和DeepSeek-V3 671B，尽管其参数量仅为这些模型的1%。进一步实验表明，CODE-DITING对偏好泄露具有鲁棒性，是代码评估的有力替代方案。

> Trustworthy evaluation methods for code snippets play a crucial role in neural code generation. Traditional methods, which either rely on reference solutions or require executable test cases, have inherent limitation in flexibility and scalability. The recent LLM-as-Judge methodology offers a promising alternative by directly evaluating functional consistency between the problem description and the generated code. To systematically understand the landscape of these LLM-as-Judge methods, we conduct a comprehensive empirical study across three diverse datasets. Our investigation reveals the pros and cons of two categories of LLM-as-Judge methods: the methods based on general foundation models can achieve good performance but require complex prompts and lack explainability, while the methods based on reasoning foundation models provide better explainability with simpler prompts but demand substantial computational resources due to their large parameter sizes. To address these limitations, we propose CODE-DITING, a novel code evaluation method that balances accuracy, efficiency and explainability. We develop a data distillation framework that effectively transfers reasoning capabilities from DeepSeek-R1671B to our CODE-DITING 1.5B and 7B models, significantly enhancing evaluation explainability and reducing the computational cost. With the majority vote strategy in the inference process, CODE-DITING 1.5B outperforms all models with the same magnitude of parameters and achieves performance which would normally exhibit in a model with 5 times of parameter scale. CODE-DITING 7B surpasses GPT-4o and DeepSeek-V3 671B, even though it only uses 1% of the parameter volume of these large models. Further experiments show that CODEDITING is robust to preference leakage and can serve as a promising alternative for code evaluation.

[Arxiv](https://arxiv.org/abs/2505.19502)