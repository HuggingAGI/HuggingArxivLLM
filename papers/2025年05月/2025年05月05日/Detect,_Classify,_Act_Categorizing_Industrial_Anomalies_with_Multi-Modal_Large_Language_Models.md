# # 检测、分类、行动：基于多模态大型语言模型的工业异常分类研究

发布时间：2025年05月05日

`LLM应用` `工业检测` `计算机视觉`

> Detect, Classify, Act: Categorizing Industrial Anomalies with Multi-Modal Large Language Models

# 摘要

> 视觉工业异常检测的最新进展在保持快速推理速度的同时，展现出卓越的异常区域识别与分割能力。然而，尽管异常分类在实际检测任务中至关重要，但这一领域仍待探索。为填补这一空白，我们提出VELM——一种基于LLM的新型异常分类管道。为确保推理速度，我们首先采用无监督异常检测方法作为视觉专家，评估观测的正常性。一旦检测到异常，LLM随后进行分类。开发和评估异常分类模型的关键挑战在于现有数据集中缺乏精确的异常类别标注。为应对这一局限，我们引入了MVTec-AC和VisA-AC，这是MVTec-AD和VisA数据集的改进版本，包含准确的异常类别标签，以支持严谨的评估。我们的方法在MVTec-AD上实现了80.4%的异常分类准确率，较先前基线提升了5%，并在MVTec-AC上达到了84%的准确率，充分证明了VELM在异常理解和分类方面的有效性。我们希望我们的方法和基准能够激发进一步的异常分类研究，帮助缩小检测与全面异常表征之间的差距。

> Recent advances in visual industrial anomaly detection have demonstrated exceptional performance in identifying and segmenting anomalous regions while maintaining fast inference speeds. However, anomaly classification-distinguishing different types of anomalies-remains largely unexplored despite its critical importance in real-world inspection tasks. To address this gap, we propose VELM, a novel LLM-based pipeline for anomaly classification. Given the critical importance of inference speed, we first apply an unsupervised anomaly detection method as a vision expert to assess the normality of an observation. If an anomaly is detected, the LLM then classifies its type. A key challenge in developing and evaluating anomaly classification models is the lack of precise annotations of anomaly classes in existing datasets. To address this limitation, we introduce MVTec-AC and VisA-AC, refined versions of the widely used MVTec-AD and VisA datasets, which include accurate anomaly class labels for rigorous evaluation. Our approach achieves a state-of-the-art anomaly classification accuracy of 80.4% on MVTec-AD, exceeding the prior baselines by 5%, and 84% on MVTec-AC, demonstrating the effectiveness of VELM in understanding and categorizing anomalies. We hope our methodology and benchmark inspire further research in anomaly classification, helping bridge the gap between detection and comprehensive anomaly characterization.

[Arxiv](https://arxiv.org/abs/2505.02626)