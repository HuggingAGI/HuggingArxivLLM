# ChatTS：借助合成数据让时间序列与LLMs对齐，以提升理解和推理能力

发布时间：2024年12月04日

`LLM应用` `时间序列` `语言模型`

> ChatTS: Aligning Time Series with LLMs via Synthetic Data for Enhanced Understanding and Reasoning

# 摘要

> 理解时间序列对于其在现实场景中的应用极为关键。近来，大型语言模型（LLMs）在时间序列任务中的应用愈发广泛，凭借其强大的语言能力提升了各类应用。然而，针对用于时间序列理解与推理的多模态大型语言模型（MLLMs）的研究尚有限，主要原因在于将时间序列与文本信息相匹配的高质量数据集稀缺。本文推出了 ChatTS，这是一款专为时间序列分析打造的新型 MLLM。ChatTS 把时间序列当作一种模态，类似于视觉 MLLMs 处理图像的方式，从而能够对时间序列进行理解和推理。为应对训练数据的稀缺问题，我们提出了一种基于属性的方法来生成带有详细属性描述的合成时间序列。我们还引入了 Time Series Evol-Instruct 这一全新方法，它能生成多样化的时间序列问答，增强了模型的推理能力。据我们了解，ChatTS 是首个以多元时间序列为输入的 MLLM，且仅在合成数据集上进行了微调。我们使用包含真实世界数据的基准数据集对其性能进行评估，涵盖了六个对齐任务和四个推理任务。我们的结果显示，ChatTS 明显优于现有的基于视觉的 MLLMs（比如 GPT-4o）和基于文本/代理的 LLMs，在对齐任务中提升了 46.0%，在推理任务中提升了 25.8%。

> Understanding time series is crucial for its application in real-world scenarios. Recently, large language models (LLMs) have been increasingly applied to time series tasks, leveraging their strong language capabilities to enhance various applications. However, research on multimodal LLMs (MLLMs) for time series understanding and reasoning remains limited, primarily due to the scarcity of high-quality datasets that align time series with textual information. This paper introduces ChatTS, a novel MLLM designed for time series analysis. ChatTS treats time series as a modality, similar to how vision MLLMs process images, enabling it to perform both understanding and reasoning with time series. To address the scarcity of training data, we propose an attribute-based method for generating synthetic time series with detailed attribute descriptions. We further introduce Time Series Evol-Instruct, a novel approach that generates diverse time series Q&As, enhancing the model's reasoning capabilities. To the best of our knowledge, ChatTS is the first MLLM that takes multivariate time series as input, which is fine-tuned exclusively on synthetic datasets. We evaluate its performance using benchmark datasets with real-world data, including six alignment tasks and four reasoning tasks. Our results show that ChatTS significantly outperforms existing vision-based MLLMs (e.g., GPT-4o) and text/agent-based LLMs, achieving a 46.0% improvement in alignment tasks and a 25.8% improvement in reasoning tasks.

[Arxiv](https://arxiv.org/abs/2412.03104)