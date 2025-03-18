# LEAVS：基于LLM的腹部CT监督标注器

发布时间：2025年03月17日

`LLM应用` `放射学` `腹部医学影像`

> LEAVS: An LLM-based Labeler for Abdominal CT Supervision

# 摘要

> 从放射报告中提取结构化标签已被用于创建视觉模型，以同时检测多种类型的异常。然而，现有研究主要集中在胸部区域。由于腹部解剖结构更为复杂且病理范围更广，鲜有研究针对腹部放射报告展开。我们提出了LEAVS（腹部视觉监督的大语言模型提取器）。此标注器能为CT放射报告中九种腹部器官的七种异常类型标注存在确定性和紧急程度。为确保广泛的适用性，我们选择了涵盖CT报告中大多数发现类型的异常。我们的方法采用了一种基于树状决策系统的句子提取和多项选择问题的专门化链式思考提示策略，适用于本地运行的大语言模型。我们证明，大语言模型能够以平均F1分数0.89提取多种腹部器官的异常类型，显著优于其他标注器和人工标注。此外，我们展示了紧急程度标签的提取性能与人工标注相当。最后，我们证明异常标签包含了训练单一视觉模型（用于分类多个器官为正常或异常）的宝贵信息。我们公开了我们的代码和对包含1,000多份CT数据集的结构化标注。

> Extracting structured labels from radiology reports has been employed to create vision models to simultaneously detect several types of abnormalities. However, existing works focus mainly on the chest region. Few works have been investigated on abdominal radiology reports due to more complex anatomy and a wider range of pathologies in the abdomen. We propose LEAVS (Large language model Extractor for Abdominal Vision Supervision). This labeler can annotate the certainty of presence and the urgency of seven types of abnormalities for nine abdominal organs on CT radiology reports. To ensure broad coverage, we chose abnormalities that encompass most of the finding types from CT reports. Our approach employs a specialized chain-of-thought prompting strategy for a locally-run LLM using sentence extraction and multiple-choice questions in a tree-based decision system. We demonstrate that the LLM can extract several abnormality types across abdominal organs with an average F1 score of 0.89, significantly outperforming competing labelers and humans. Additionally, we show that extraction of urgency labels achieved performance comparable to human annotations. Finally, we demonstrate that the abnormality labels contain valuable information for training a single vision model that classifies several organs as normal or abnormal. We release our code and structured annotations for a public CT dataset containing over 1,000 CT volumes.

[Arxiv](https://arxiv.org/abs/2503.13330)