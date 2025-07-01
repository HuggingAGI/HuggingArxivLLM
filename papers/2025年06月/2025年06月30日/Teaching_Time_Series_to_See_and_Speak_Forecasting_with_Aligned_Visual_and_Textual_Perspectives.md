# 让时间序列学会观察与表达：基于视觉与文本视角一致性的预测方法

发布时间：2025年06月30日

`其他`

> Teaching Time Series to See and Speak: Forecasting with Aligned Visual and Textual Perspectives

# 摘要

> 传统时间序列预测依赖单一模式的数值输入，这类输入因密集且无结构的特性，难以有效捕捉高层次语义模式。近期研究尝试利用大型语言模型（LLMs）将时间序列转化为文本表示，但受限于离散的token序列特性和缺乏人类常用的感知直觉（如视觉模式识别）。本文提出了一种多模态对比学习框架，将原始时间序列转化为结构化的视觉与文本视角。我们直接从数值序列构建这两种模态，而非使用自然语言或真实图像。通过对比学习，我们在共享语义空间中对齐这些视角，使模型能够捕获更丰富和互补的表示。此外，我们引入变量选择模块，利用对齐表示识别多变量预测中最有信息量的变量。在十五个短期和六个长期预测基准上的大量实验表明，我们的方法始终优于单一模式和跨模式基线，凸显了多模态对齐在提升时间序列预测中的有效性。代码可在GitHub获取：https://github.com/Ironieser/TimesCLIP.

> Time series forecasting traditionally relies on unimodal numerical inputs, which often struggle to capture high-level semantic patterns due to their dense and unstructured nature. While recent approaches have explored representing time series as text using large language models (LLMs), these methods remain limited by the discrete nature of token sequences and lack the perceptual intuition humans typically apply, such as interpreting visual patterns. In this paper, we propose a multimodal contrastive learning framework that transforms raw time series into structured visual and textual perspectives. Rather than using natural language or real-world images, we construct both modalities directly from numerical sequences. We then align these views in a shared semantic space via contrastive learning, enabling the model to capture richer and more complementary representations. Furthermore, we introduce a variate selection module that leverages the aligned representations to identify the most informative variables for multivariate forecasting. Extensive experiments on fifteen short-term and six long-term forecasting benchmarks demonstrate that our approach consistently outperforms strong unimodal and cross-modal baselines, highlighting the effectiveness of multimodal alignment in enhancing time series forecasting. Code is available at: https://github.com/Ironieser/TimesCLIP.

[Arxiv](https://arxiv.org/abs/2506.24124)