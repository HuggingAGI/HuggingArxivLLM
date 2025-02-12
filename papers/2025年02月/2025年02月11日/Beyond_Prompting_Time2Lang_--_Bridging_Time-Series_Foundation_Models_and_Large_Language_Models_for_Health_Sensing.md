# 超越提示：Time2Lang——架起时间序列基础模型与大型语言模型之间的桥梁，助力健康感知

发布时间：2025年02月11日

`LLM应用`

> Beyond Prompting: Time2Lang -- Bridging Time-Series Foundation Models and Large Language Models for Health Sensing

# 摘要

> 大型语言模型（LLMs）在健康应用领域展现出巨大潜力，尤其是在与行为感知数据结合时。然而，传统方法通过将传感器数据转换为文本提示来实现这一目标，但这一过程存在诸多挑战：容易出错、计算成本高昂且需要领域专业知识。这些问题在处理长时间序列数据时尤为突出。尽管时间序列基础模型（TFMs）最近作为处理时序数据的强大工具崭露头角，但如何将TFMs与LLMs有效结合仍是难题。为此，我们提出Time2Lang框架，它无需中间文本转换，直接将TFM输出映射到LLM表示。我们的方法首先通过周期性预测作为预训练任务在合成数据上进行训练，随后在心理健康分类任务上进行评估。我们在两个纵向可穿戴和移动感知数据集上验证了Time2Lang框架：基于步数数据的日抑郁预测（来自256名参与者，共17,251天）和基于对话时长的繁荣分类（46名参与者，持续10周）。与传统提示方法不同，Time2Lang的推理时间几乎恒定，不受输入长度影响。生成的嵌入保留了自相关等关键时间序列特性。我们的研究结果表明，TFMs与LLMs可以有效整合，同时最大限度地减少信息丢失，并实现跨不同建模范式的表现迁移。据我们所知，我们是首个将TFM与LLM结合用于健康领域的研究，从而为未来结合通用大型模型解决复杂医疗任务的研究奠定了基础。

> Large language models (LLMs) show promise for health applications when combined with behavioral sensing data. Traditional approaches convert sensor data into text prompts, but this process is prone to errors, computationally expensive, and requires domain expertise. These challenges are particularly acute when processing extended time series data. While time series foundation models (TFMs) have recently emerged as powerful tools for learning representations from temporal data, bridging TFMs and LLMs remains challenging. Here, we present Time2Lang, a framework that directly maps TFM outputs to LLM representations without intermediate text conversion. Our approach first trains on synthetic data using periodicity prediction as a pretext task, followed by evaluation on mental health classification tasks. We validate Time2Lang on two longitudinal wearable and mobile sensing datasets: daily depression prediction using step count data (17,251 days from 256 participants) and flourishing classification based on conversation duration (46 participants over 10 weeks). Time2Lang maintains near constant inference times regardless of input length, unlike traditional prompting methods. The generated embeddings preserve essential time-series characteristics such as auto-correlation. Our results demonstrate that TFMs and LLMs can be effectively integrated while minimizing information loss and enabling performance transfer across these distinct modeling paradigms. To our knowledge, we are the first to integrate a TFM and an LLM for health, thus establishing a foundation for future research combining general-purpose large models for complex healthcare tasks.

[Arxiv](https://arxiv.org/abs/2502.07608)