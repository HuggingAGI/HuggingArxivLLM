# # 守护多模态大语言模型，抵御误导性可视化

发布时间：2025年02月27日

`LLM应用` `人工智能` `数据科学`

> Protecting multimodal large language models against misleading visualizations

# 摘要

> 我们研究了多模态大型语言模型对误导性图表的漏洞，这些图表通过截断或反转轴等手法扭曲数据，可能误导读者支持错误信息或阴谋论。分析发现，这些误导性图表严重损害了多模态模型的性能，使其问答准确度降至随机水平。为解决这一问题，我们提出了六种推理时优化方法，旨在提升模型在误导性图表上的表现，同时保持其在正常图表上的准确性。其中最有效的方案是（1）提取图表底层数据表，（2）使用仅基于文本的大型语言模型根据数据表回答问题。这种方法在误导性图表上的性能提升了15.4到19.6个百分点。

> We assess the vulnerability of multimodal large language models to misleading visualizations - charts that distort the underlying data using techniques such as truncated or inverted axes, leading readers to draw inaccurate conclusions that may support misinformation or conspiracy theories. Our analysis shows that these distortions severely harm multimodal large language models, reducing their question-answering accuracy to the level of the random baseline. To mitigate this vulnerability, we introduce six inference-time methods to improve performance of MLLMs on misleading visualizations while preserving their accuracy on non-misleading ones. The most effective approach involves (1) extracting the underlying data table and (2) using a text-only large language model to answer questions based on the table. This method improves performance on misleading visualizations by 15.4 to 19.6 percentage points.

[Arxiv](https://arxiv.org/abs/2502.20503)