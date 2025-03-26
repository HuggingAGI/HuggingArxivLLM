# MTBench：一个多模态时间序列基准测试，针对时间推理与问答任务

发布时间：2025年03月21日

`LLM应用`

> MTBench: A Multimodal Time Series Benchmark for Temporal Reasoning and Question Answering

# 摘要

> 理解文本新闻与时间序列演变之间的关系是应用数据科学中一个关键而未被充分探索的挑战。尽管多模态学习已经引起关注，但现有的多模态时间序列数据集在评估跨模态推理和复杂问答方面仍有不足，这些能力对于捕捉叙述信息与时间模式之间的复杂交互至关重要。为了填补这一空白，我们引入了多模态时间序列基准（MTBench），这是一个大型基准测试，旨在评估大型语言模型（LLMs）在金融和天气领域对时间序列和文本的理解能力。MTbench包含配对的时间序列和文本数据，包括带有相应股票价格变动的财经新闻，以及与历史温度记录相匹配的天气报告。与现有专注于单一模态的基准不同，MTbench为模型提供了一个全面的测试环境，使其能够同时对结构化的数值趋势和非结构化的文本叙述进行推理。MTbench的丰富性使我们能够制定多样化的任务，这些任务需要对文本和时间序列数据有深刻的理解，包括时间序列预测、语义和技术趋势分析以及基于新闻的问答（QA）。这些任务旨在测试模型捕捉时间依赖性、从文本上下文中提取关键见解以及融合跨模态信息的能力。我们对最先进的LLMs在MTbench上进行了评估，分析它们在建模新闻叙述与时间模式之间复杂关系方面的有效性。我们的研究发现，当前模型面临诸多挑战，包括难以捕捉长期依赖关系、解释财务和天气趋势中的因果关系，以及有效融合多模态信息的能力不足。

> Understanding the relationship between textual news and time-series evolution is a critical yet under-explored challenge in applied data science. While multimodal learning has gained traction, existing multimodal time-series datasets fall short in evaluating cross-modal reasoning and complex question answering, which are essential for capturing complex interactions between narrative information and temporal patterns. To bridge this gap, we introduce Multimodal Time Series Benchmark (MTBench), a large-scale benchmark designed to evaluate large language models (LLMs) on time series and text understanding across financial and weather domains. MTbench comprises paired time series and textual data, including financial news with corresponding stock price movements and weather reports aligned with historical temperature records. Unlike existing benchmarks that focus on isolated modalities, MTbench provides a comprehensive testbed for models to jointly reason over structured numerical trends and unstructured textual narratives. The richness of MTbench enables formulation of diverse tasks that require a deep understanding of both text and time-series data, including time-series forecasting, semantic and technical trend analysis, and news-driven question answering (QA). These tasks target the model's ability to capture temporal dependencies, extract key insights from textual context, and integrate cross-modal information. We evaluate state-of-the-art LLMs on MTbench, analyzing their effectiveness in modeling the complex relationships between news narratives and temporal patterns. Our findings reveal significant challenges in current models, including difficulties in capturing long-term dependencies, interpreting causality in financial and weather trends, and effectively fusing multimodal information.

[Arxiv](https://arxiv.org/abs/2503.16858)