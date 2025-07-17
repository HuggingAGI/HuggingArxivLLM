# TAB：时间序列异常检测方法的统一基准评测

发布时间：2025年07月15日

`LLM应用` `跨领域`

> TAB: Unified Benchmarking of Time Series Anomaly Detection Methods

# 摘要

> 时间序列异常检测（TSAD）在金融、交通和医疗等领域中至关重要。随着现实世界的持续数字化，时间序列数据的激增也带来了对TSAD的更高需求。虽然已有的TSAD方法不少，但开发更优的方法仍然值得期待。然而，这一目标的实现离不开可靠的方法评估手段和公平的对比机制。我们针对现有评估程序在数据集和实验设置及协议方面的不足进行了改进。具体来说，我们推出了一种新的时间序列异常检测基准——TAB。首先，TAB整合了来自不同领域的29个公开多变量数据集和1,635个单变量时间序列，为多样化数据集上的全面评估提供了支持。其次，TAB涵盖了非学习型、机器学习型、深度学习型、基于LLM的以及时间序列预训练等多种TSAD方法。第三，TAB提供了一个统一且自动化的评估流水线，确保了对TSAD方法的公平且便捷的评估。最后，我们通过TAB对现有TSAD方法进行了系统评估，并分享了评估结果，从而为这些方法的性能提供了更深入的见解。此外，所有数据集和代码均可在GitHub仓库https://github.com/decisionintelligence/TAB中获取。

> Time series anomaly detection (TSAD) plays an important role in many domains such as finance, transportation, and healthcare. With the ongoing instrumentation of reality, more time series data will be available, leading also to growing demands for TSAD. While many TSAD methods already exist, new and better methods are still desirable. However, effective progress hinges on the availability of reliable means of evaluating new methods and comparing them with existing methods. We address deficiencies in current evaluation procedures related to datasets and experimental settings and protocols. Specifically, we propose a new time series anomaly detection benchmark, called TAB. First, TAB encompasses 29 public multivariate datasets and 1,635 univariate time series from different domains to facilitate more comprehensive evaluations on diverse datasets. Second, TAB covers a variety of TSAD methods, including Non-learning, Machine learning, Deep learning, LLM-based, and Time-series pre-trained methods. Third, TAB features a unified and automated evaluation pipeline that enables fair and easy evaluation of TSAD methods. Finally, we employ TAB to evaluate existing TSAD methods and report on the outcomes, thereby offering a deeper insight into the performance of these methods. Besides, all datasets and code are available at https://github.com/decisionintelligence/TAB.

[Arxiv](https://arxiv.org/abs/2506.18046)