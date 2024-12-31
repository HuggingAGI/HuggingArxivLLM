# TimeRAF：用于零样本时间序列预测的检索增强型基础模型

发布时间：2024年12月30日

`RAG` `数据挖掘` `时间序列预测`

> TimeRAF: Retrieval-Augmented Foundation model for Zero-shot Time Series Forecasting

# 摘要

> 时间序列预测在数据挖掘领域至关重要，有力推动了众多行业的快速进步。随着大型模型的问世，时间序列基础模型（TSFMs）通过大规模预训练展现出出色的泛化能力，像零样本学习等。与此同时，检索增强生成（RAG）方法被广泛应用于提升基础模型在未知数据上的表现，让模型能够获取外部知识。在本文中，我们推出了 TimeRAF，这是一种借助检索增强技术来强化零样本时间序列预测的检索增强预测模型。我们构建了专为特定预测任务定制的时间序列知识库。TimeRAF 运用端到端可学习的检索器从知识库中提取有价值的信息。另外，我们提出了通道提示用于知识整合，能有效地从检索到的知识中沿通道维度提取相关内容。大量实验表明我们的模型成效显著，在各个领域和数据集上均有显著提升。

> Time series forecasting plays a crucial role in data mining, driving rapid advancements across numerous industries. With the emergence of large models, time series foundation models (TSFMs) have exhibited remarkable generalization capabilities, such as zero-shot learning, through large-scale pre-training. Meanwhile, Retrieval-Augmented Generation (RAG) methods have been widely employed to enhance the performance of foundation models on unseen data, allowing models to access to external knowledge. In this paper, we introduce TimeRAF, a Retrieval-Augmented Forecasting model that enhance zero-shot time series forecasting through retrieval-augmented techniques. We develop customized time series knowledge bases that are tailored to the specific forecasting tasks. TimeRAF employs an end-to-end learnable retriever to extract valuable information from the knowledge base. Additionally, we propose Channel Prompting for knowledge integration, which effectively extracts relevant information from the retrieved knowledge along the channel dimension. Extensive experiments demonstrate the effectiveness of our model, showing significant improvement across various domains and datasets.

[Arxiv](https://arxiv.org/abs/2412.20810)