# LLM-Prompt: 集成异构提示，释放大型语言模型在时间序列预测中的潜力

发布时间：2025年06月21日

`LLM应用`

> LLM-Prompt: Integrated Heterogeneous Prompts for Unlocking LLMs in Time Series Forecasting

# 摘要

> 时间序列预测旨在通过建模变量间的时间依赖关系推断未来状态，在现实场景中具有重要意义和广泛应用。尽管深度学习方法取得了显著进展，但在长期预测和数据稀缺场景中仍表现欠佳。近期研究表明，大型语言模型（LLMs）在时间序列预测中展现出巨大潜力。然而，现有基于LLM的方法仍存在两大问题：缺乏统一的文本提示构建范式，且忽视了文本提示与时间序列间的模态差异。为此，我们提出LLM-Prompt框架，整合多提示信息并实现跨模态语义对齐。具体而言，首先构建了包含可学习软提示和文本化硬提示的统一文本提示范式；其次，设计了语义空间嵌入和跨模态对齐模块，实现时间与文本信息的跨模态融合；最后，通过投影LLMs处理后的时间序列获得预测结果。在6个公共数据集和3个碳排放数据集上的全面评估表明，LLM-Prompt是一个强大的时间序列预测框架。

> Time series forecasting aims to model temporal dependencies among variables for future state inference, holding significant importance and widespread applications in real-world scenarios. Although deep learning-based methods have achieved remarkable progress, they still exhibit suboptimal performance in long-term forecasting and data-scarce scenarios. Recent research demonstrates that large language models (LLMs) achieve promising performance in time series forecasting. However, we find existing LLM-based methods still have shortcomings: (1) the absence of a unified paradigm for textual prompt formulation and (2) the neglect of modality discrepancies between textual prompts and time series. To address this, we propose LLM-Prompt, an LLM-based time series forecasting framework integrating multi-prompt information and cross-modal semantic alignment. Specifically, we first construct a unified textual prompt paradigm containing learnable soft prompts and textualized hard prompts. Second, to enhance LLMs' comprehensive understanding of the forecasting task, we design a semantic space embedding and cross-modal alignment module to achieve cross-modal fusion of temporal and textual information. Finally, the transformed time series from the LLMs are projected to obtain the forecasts. Comprehensive evaluations on 6 public datasets and 3 carbon emission datasets demonstrate that LLM-Prompt is a powerful framework for time series forecasting.

[Arxiv](https://arxiv.org/abs/2506.17631)