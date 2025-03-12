# 时间序列多任务框架：融合大型语言模型、预训练时间序列模型与知识图谱

发布时间：2025年03月10日

`LLM应用`

> A Time Series Multitask Framework Integrating a Large Language Model, Pre-Trained Time Series Model, and Knowledge Graph

# 摘要

> 时间序列分析在金融、交通和工业等领域至关重要。然而，传统模型往往仅关注时间特征，限制了其捕捉潜在信息的能力。本文提出了一种新颖的时间序列多任务框架——LTM，它结合了时间特征与文本描述，显著提升了分析和预测能力。LTM融合了预训练的时间序列模型、大语言模型（LLM）和知识图谱，能够高效处理时间序列任务，包括预测、插补和异常检测。LTM通过少量可训练参数实现了性能提升，非常高效且实用。它将时间序列数据编码为块，并利用知识图谱丰富用户提供的提示，生成增强提示。一种新颖的特征融合方法将提示嵌入到每个块编码中，由冻结的LLM处理，随后经过特征增强模块和时间解码模块。在微调阶段，将提示与时间块之间的余弦相似性整合到损失函数中，以提升性能。在基准数据集上的实验表明，LTM显著优于现有方法，为时间序列任务提供了一种强大且灵活的解决方案。


> Time series analysis is crucial in fields like finance, transportation, and industry. However, traditional models often focus solely on temporal features, limiting their ability to capture underlying information. This paper proposes a novel time series multitask framework, called LTM, which integrates temporal features with textual descriptions to enhance analytical and predictive capabilities. LTM combines pre-trained time series model, large language model (LLM), and knowledge graph to tackle time series tasks, including forecasting, imputation, and anomaly detection. LTM achieves improved performance with a few trainable parameters. It is very efficient and practical. LTM encodes time series data into patches and enriches user-provided prompts using knowledge graphs to generate enhanced prompts. A novel feature fusion method embeds prompts into each patch encoding, which is processed by a frozen LLM, followed by a feature enhancement module and a time decoder module. During fine-tuning stage, cosine similarity between prompts and temporal patches is integrated into the loss function to boost performance. Experiments on benchmark datasets show that LTM significantly outperforms existing methods. It provides a robust and versatile solution for time series tasks.

[Arxiv](https://arxiv.org/abs/2503.07682)