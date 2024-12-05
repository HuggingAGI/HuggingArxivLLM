# LLMForecaster：借助非结构化文本数据提升季节性事件预测水平

发布时间：2024年12月03日

`LLM应用` `时间序列预测`

> LLMForecaster: Improving Seasonal Event Forecasts with Unstructured Textual Data

# 摘要

> 现代的时间序列预测模型常常难以充分利用时间序列自身丰富的非结构化信息。这种恰当条件的缺失可能致使明显的模型失效；比如，模型或许不了解特定产品的详情，从而无法预料在重大外生事件（如假期）来临前，明显相关产品的客户需求季节性猛增。为弥补这一缺陷，本文引入了一种全新的预测后处理器——我们称其为 LLMForecaster——它对大型语言模型（LLMs）进行微调，以融入非结构化的语义、上下文信息以及历史数据，来优化现有需求预测流程的预测结果。在一个行业规模的零售应用里，我们表明，我们的技术在几组受假期驱动需求猛增影响的产品中，实现了具有统计学显著意义的预测改进。

> Modern time-series forecasting models often fail to make full use of rich unstructured information about the time series themselves. This lack of proper conditioning can lead to obvious model failures; for example, models may be unaware of the details of a particular product, and hence fail to anticipate seasonal surges in customer demand in the lead up to major exogenous events like holidays for clearly relevant products. To address this shortcoming, this paper introduces a novel forecast post-processor -- which we call LLMForecaster -- that fine-tunes large language models (LLMs) to incorporate unstructured semantic and contextual information and historical data to improve the forecasts from an existing demand forecasting pipeline. In an industry-scale retail application, we demonstrate that our technique yields statistically significantly forecast improvements across several sets of products subject to holiday-driven demand surges.

[Arxiv](https://arxiv.org/abs/2412.02525)