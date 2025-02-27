# TestNUC：利用邻近无标签数据的一致性提升测试时计算方法。

发布时间：2025年02月26日

`LLM应用

理由：这篇论文提出了一种新的测试时计算方法TestNUC，专注于提升大型语言模型在推理过程中的性能。该方法通过利用邻近未标记数据的一致性改进预测，属于模型应用层面的优化，因此归类为LLM应用。` `人工智能服务`

> TestNUC: Enhancing Test-Time Computing Approaches through Neighboring Unlabeled Data Consistency

# 摘要

> 测试时计算方法已被证明能有效提升大型语言模型的性能，通过在推理过程中利用额外计算资源实现。本文提出了一种全新的线性扩展方法——TestNUC，它通过利用邻近未标记数据的一致性改进测试时预测。具体而言，TestNUC不仅基于模型对输入实例的预测，还考虑了邻近未标记实例的预测结果来进行分类。我们在涵盖意图分类、主题挖掘、领域发现和情感检测等八个多样化数据集上评估了TestNUC，结果表明其在性能上始终优于标准提示和自洽性等基线方法。此外，TestNUC可与现有测试时计算方法无缝集成，显著提升其性能。我们的分析表明，TestNUC能有效扩展处理不断增加的未标记数据，并在不同嵌入模型上表现出强大的鲁棒性，使其适用于实际应用场景。我们的代码可在https://github.com/HenryPengZou/TestNUC获取。

> Test-time computing approaches, which leverage additional computational resources during inference, have been proven effective in enhancing large language model performance. This work introduces a novel, linearly scaling approach, TestNUC, that improves test-time predictions by leveraging the local consistency of neighboring unlabeled data-it classifies an input instance by considering not only the model's prediction on that instance but also on neighboring unlabeled instances. We evaluate TestNUC across eight diverse datasets, spanning intent classification, topic mining, domain discovery, and emotion detection, demonstrating its consistent superiority over baseline methods such as standard prompting and self-consistency. Furthermore, TestNUC can be seamlessly integrated with existing test-time computing approaches, substantially boosting their performance. Our analysis reveals that TestNUC scales effectively with increasing amounts of unlabeled data and performs robustly across different embedding models, making it practical for real-world applications. Our code is available at https://github.com/HenryPengZou/TestNUC.

[Arxiv](https://arxiv.org/abs/2502.19163)