# CENTS: 生成罕见和未见场景的合成电力消耗时间序列

发布时间：2025年01月24日

`其他

理由：这篇论文主要讨论的是在能源和智能电网领域应用生成模型来生成高保真的电力消耗时间序列数据。虽然提到了基础模型（如生成模型），但重点并不在于大型语言模型（LLM）或其应用、理论，也不涉及Agent或RAG（检索增强生成）技术。因此，这篇论文更适合归类为“其他”。` `智能电网`

> CENTS: Generating synthetic electricity consumption time series for rare and unseen scenarios

# 摘要

> # 摘要
大规模生成建模的最新突破展示了基础模型在自然语言、计算机视觉和蛋白质结构预测等领域的巨大潜力。然而，由于高质量数据的稀缺性和异质性，这些模型在能源和智能电网领域的应用仍显不足。本文提出了一种名为CENTS（上下文编码和归一化时间序列生成）的方法，用于生成罕见和未见上下文变量（如位置、建筑类型、光伏）的高保真电力消耗时间序列数据。CENTS包含三大创新：（i）一种上下文归一化方法，支持对训练期间未见的时间序列上下文变量进行逆变换；（ii）一种新颖的上下文编码器，可将任意数量和组合的上下文变量条件化于任何最先进的时间序列生成器；（iii）一个联合训练框架，通过辅助上下文分类损失增强上下文嵌入的表达能力并提升模型性能。我们还全面梳理了生成时间序列模型的评估指标。实验结果表明，该方法在生成真实家庭级电力消耗数据方面效果显著，为在能源领域使用合成和真实数据训练更大规模的基础模型奠定了基础。

> Recent breakthroughs in large-scale generative modeling have demonstrated the potential of foundation models in domains such as natural language, computer vision, and protein structure prediction. However, their application in the energy and smart grid sector remains limited due to the scarcity and heterogeneity of high-quality data. In this work, we propose a method for creating high-fidelity electricity consumption time series data for rare and unseen context variables (e.g. location, building type, photovoltaics). Our approach, Context Encoding and Normalizing Time Series Generation, or CENTS, includes three key innovations: (i) A context normalization approach that enables inverse transformation for time series context variables unseen during training, (ii) a novel context encoder to condition any state-of-the-art time-series generator on arbitrary numbers and combinations of context variables, (iii) a framework for training this context encoder jointly with a time-series generator using an auxiliary context classification loss designed to increase expressivity of context embeddings and improve model performance. We further provide a comprehensive overview of different evaluation metrics for generative time series models. Our results highlight the efficacy of the proposed method in generating realistic household-level electricity consumption data, paving the way for training larger foundation models in the energy domain on synthetic as well as real-world data.

[Arxiv](https://arxiv.org/abs/2501.14426)