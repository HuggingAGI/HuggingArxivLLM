# LLMs 的数据污染检测是否有效？对检测假设的调研与评估

发布时间：2024年10月24日

`LLM应用` `语言模型` `数据科学`

> Does Data Contamination Detection Work (Well) for LLMs? A Survey and Evaluation on Detection Assumptions

# 摘要

> 大型语言模型（LLMs）在各类基准测试中表现出色，展现出作为通用任务解决者的巨大潜力。然而，LLMs通常基于海量数据训练，评估时的一大关键问题是数据污染，即训练数据与评估数据集的重叠会抬高性能评估。尽管已开发出多种识别数据污染的方法，但这些方法依赖特定假设，而这些假设并非在所有不同场景中都普遍适用。为填补这一空缺，我们系统回顾了 47 篇有关数据污染检测的论文，对底层假设进行分类，并评估其是否经过严格验证。我们确定并分析了八类假设，并以其中三类作为案例研究加以测试。分析显示，在对用于预训练 LLMs 的实例进行分类时，基于这三个假设的检测方法表现近乎随机猜测，这意味着当前的 LLMs 学习的是数据分布，而非记忆单个实例。总之，此项工作突显了方法清晰阐明其底层假设，并在各种情境下测试其有效性的重要性。

> Large language models (LLMs) have demonstrated great performance across various benchmarks, showing potential as general-purpose task solvers. However, as LLMs are typically trained on vast amounts of data, a significant concern in their evaluation is data contamination, where overlap between training data and evaluation datasets inflates performance assessments. While multiple approaches have been developed to identify data contamination, these approaches rely on specific assumptions that may not hold universally across different settings. To bridge this gap, we systematically review 47 papers on data contamination detection, categorize the underlying assumptions, and assess whether they have been rigorously validated. We identify and analyze eight categories of assumptions and test three of them as case studies. Our analysis reveals that when classifying instances used for pretraining LLMs, detection approaches based on these three assumptions perform close to random guessing, suggesting that current LLMs learn data distributions rather than memorizing individual instances. Overall, this work underscores the importance of approaches clearly stating their underlying assumptions and testing their validity across various scenarios.

[Arxiv](https://arxiv.org/abs/2410.18966)