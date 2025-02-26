# # 摘要  
最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年02月24日

`LLM应用

论文摘要：这项研究探讨了多模态大规模语言模型（MLLMs）在时间序列异常检测中的应用，展示了其在不同场景下的表现，属于具体应用场景的研究，因此归类为LLM应用。` `时间序列分析` `异常检测`

> Can Multimodal LLMs Perform Time Series Anomaly Detection?

# 摘要

> 大规模语言模型 (LLMs) 在时间序列分析中的应用日益广泛，但多模态 LLMs (MLLMs)，尤其是视觉语言模型，在时间序列分析中的潜力仍未得到充分挖掘。人类在检测时间序列异常时，往往通过可视化和文本描述来实现。受此启发，我们提出了一个关键且实际的研究问题：多模态 LLMs 是否能够有效进行时间序列异常检测？为解答这一问题，我们开发了 VisualTimeAnomaly 基准测试，用于评估 MLLMs 在时间序列异常检测 (TSAD) 中的表现。

我们的方法将时间序列的数值数据转化为图像格式，并将其输入到多种 MLLMs 中，包括专有模型（GPT-4o 和 Gemini-1.5）和开源模型（LLaVA-NeXT 和 Qwen2-VL），每个模型类别都包含较大和较小两种变体。VisualTimeAnomaly 数据集包含 12.4k 时间序列图像，覆盖 3 种场景和 3 种异常粒度，涉及 9 种异常类型，适用于 8 种 MLLMs。从单变量情况（点异常和区间异常）出发，我们将评估扩展到更实际的场景，包括多变量和不规则时间序列场景，以及变量异常。

研究发现：
1. MLLMs 在检测区间异常和变量异常方面表现优于点异常检测。
2. MLLMs 对不规则时间序列展现出强大的鲁棒性，即使数据缺失达 25%。
3. 开源 MLLMs 在 TSAD 中的表现与专有模型相当。开源 MLLMs 在单变量时间序列上表现优异，而专有 MLLMs 在多变量时间序列上更具优势。

据我们所知，这是首个全面研究 MLLMs 在 TSAD 中应用的工作，特别是针对多变量和不规则时间序列场景。我们已开源数据集和代码，以支持未来研究：https://github.com/mllm-ts/VisualTimeAnomaly。


> Large language models (LLMs) have been increasingly used in time series analysis. However, the potential of multimodal LLMs (MLLMs), particularly vision-language models, for time series remains largely under-explored. One natural way for humans to detect time series anomalies is through visualization and textual description. Motivated by this, we raise a critical and practical research question: Can multimodal LLMs perform time series anomaly detection? To answer this, we propose VisualTimeAnomaly benchmark to evaluate MLLMs in time series anomaly detection (TSAD). Our approach transforms time series numerical data into the image format and feed these images into various MLLMs, including proprietary models (GPT-4o and Gemini-1.5) and open-source models (LLaVA-NeXT and Qwen2-VL), each with one larger and one smaller variant. In total, VisualTimeAnomaly contains 12.4k time series images spanning 3 scenarios and 3 anomaly granularities with 9 anomaly types across 8 MLLMs. Starting with the univariate case (point- and range-wise anomalies), we extend our evaluation to more practical scenarios, including multivariate and irregular time series scenarios, and variate-wise anomalies. Our study reveals several key insights:
  1) MLLMs detect range- and variate-wise anomalies more effectively than point-wise anomalies.
  2) MLLMs are highly robust to irregular time series, even with 25% of the data missing.
  3) Open-source MLLMs perform comparably to proprietary models in TSAD. While open-source MLLMs excel on univariate time series, proprietary MLLMs demonstrate superior effectiveness on multivariate time series.
  To the best of our knowledge, this is the first work to comprehensively investigate MLLMs for TSAD, particularly for multivariate and irregular time series scenarios. We release our dataset and code at https://github.com/mllm-ts/VisualTimeAnomaly to support future research.

[Arxiv](https://arxiv.org/abs/2502.17812)