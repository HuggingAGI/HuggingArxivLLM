# # WaterDrum：面向数据的无学习度量水印技术

发布时间：2025年05月08日

`LLM应用` `数据管理` `数据评估`

> WaterDrum: Watermarking for Data-centric Unlearning Metric

# 摘要

> 大型语言模型（LLM）的遗忘机制在现实应用中至关重要，尤其是在需要高效移除某些用户提供的隐私、版权或有害数据的影响时。然而，现有的基于效用的遗忘指标在以下现实场景中可能无法准确评估遗忘程度：（a）遗忘集和保留集内容语义相似，（b）从头开始在保留集上重新训练模型不切实际，以及（c）模型所有者可在不直接执行遗忘操作的情况下改善遗忘指标。本文提出了第一个以数据为中心的LLM遗忘指标——WaterDrum，它利用鲁棒文本水印技术克服这些限制。我们还引入了新的LLM遗忘基准数据集，其中包含不同相似程度的数据点，可用于使用WaterDrum严格评估遗忘算法。我们的代码可在GitHub上获取，新的基准数据集已发布在Hugging Face平台。

> Large language model (LLM) unlearning is critical in real-world applications where it is necessary to efficiently remove the influence of private, copyrighted, or harmful data from some users. However, existing utility-centric unlearning metrics (based on model utility) may fail to accurately evaluate the extent of unlearning in realistic settings such as when (a) the forget and retain set have semantically similar content, (b) retraining the model from scratch on the retain set is impractical, and/or (c) the model owner can improve the unlearning metric without directly performing unlearning on the LLM. This paper presents the first data-centric unlearning metric for LLMs called WaterDrum that exploits robust text watermarking for overcoming these limitations. We also introduce new benchmark datasets for LLM unlearning that contain varying levels of similar data points and can be used to rigorously evaluate unlearning algorithms using WaterDrum. Our code is available at https://github.com/lululu008/WaterDrum and our new benchmark datasets are released at https://huggingface.co/datasets/Glow-AI/WaterDrum-Ax.

[Arxiv](https://arxiv.org/abs/2505.05064)