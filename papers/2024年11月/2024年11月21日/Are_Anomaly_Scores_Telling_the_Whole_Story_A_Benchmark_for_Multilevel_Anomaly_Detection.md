# 异常分数是否道出了全部实情？ 多级异常检测的基准

发布时间：2024年11月21日

`其他` `机器学习` `异常检测`

> Are Anomaly Scores Telling the Whole Story? A Benchmark for Multilevel Anomaly Detection

# 摘要

> 摘要：异常检测（AD）是一项通过从正常训练数据中学习模式来识别异常的机器学习任务。在众多现实场景里，异常的严重程度各异，有风险较小的轻微异常，也有需要即刻关注的严重异常。然而，现有的模型大多在二元设定下运作，其生成的异常分数通常基于数据点与正常数据的偏差，这或许无法精准反映实际的严重程度。在本文中，我们通过三项关键贡献来填补这一空缺。其一，我们提出了一种全新的设定——多级异常检测（MAD），其中的异常分数代表着现实世界应用中异常的严重程度，并且我们突出了它在各个领域的多元应用。其二，我们引入了一个新的基准——MAD-Bench，它不仅评估模型检测异常的能力，还考量其异常分数反映严重程度的有效性。该基准涵盖了多种类型的基线以及涉及严重程度的现实世界应用。最后，我们在MAD-Bench上展开了全面的性能分析。我们评估模型分配与严重程度相符分数的能力，探究其在二元和多级检测上的性能对应关系，并研究其鲁棒性。此次分析为改进与实际严重程度相匹配的AD模型提供了关键见解。用于该基准的代码框架和数据集将会公开。

> 
Abstract:Anomaly detection (AD) is a machine learning task that identifies anomalies by learning patterns from normal training data. In many real-world scenarios, anomalies vary in severity, from minor anomalies with little risk to severe abnormalities requiring immediate attention. However, existing models primarily operate in a binary setting, and the anomaly scores they produce are usually based on the deviation of data points from normal data, which may not accurately reflect practical severity. In this paper, we address this gap by making three key contributions. First, we propose a novel setting, Multilevel AD (MAD), in which the anomaly score represents the severity of anomalies in real-world applications, and we highlight its diverse applications across various domains. Second, we introduce a novel benchmark, MAD-Bench, that evaluates models not only on their ability to detect anomalies, but also on how effectively their anomaly scores reflect severity. This benchmark incorporates multiple types of baselines and real-world applications involving severity. Finally, we conduct a comprehensive performance analysis on MAD-Bench. We evaluate models on their ability to assign severity-aligned scores, investigate the correspondence between their performance on binary and multilevel detection, and study their robustness. This analysis offers key insights into improving AD models for practical severity alignment. The code framework and datasets used for the benchmark will be made publicly available.
    

[Arxiv](https://arxiv.org/pdf/2411.14515)