# Logo-LLM：基于大语言模型的时间序列预测——局部与全局建模结合

发布时间：2025年05月16日

`LLM应用` `人工智能` `时间序列预测`

> Logo-LLM: Local and Global Modeling with Large Language Models for Time Series Forecasting

# 摘要

> 时间序列预测在多个领域中扮演着关键角色，其数据既包含局部模式又具有全局依赖关系。虽然基于Transformer的方法擅长捕捉全局依赖，但它们往往忽略了时间序列中的短期局部变化。近期将大型语言模型（LLMs）应用于时间序列预测的方法沿袭了这一局限，将其作为黑盒编码器使用，仅依赖最终层输出，未能充分利用层次化表示。为突破这一限制，我们提出了Logo-LLM，一个基于LLMs的创新框架，能够从预训练LLMs的不同层中显式提取和建模多尺度时间特征。通过实证分析，我们发现浅层的LLMs层能够捕捉时间序列的局部动态，而深层的层则编码全局趋势。此外，Logo-LLM引入了轻量级的Local-Mixer和Global-Mixer模块，用于跨层对齐和集成时间输入特征。大量实验表明，Logo-LLM在多种基准测试中表现优异，不仅在少样本和零样本设置下展现出强大的泛化能力，还保持了较低的计算开销。

> Time series forecasting is critical across multiple domains, where time series data exhibits both local patterns and global dependencies. While Transformer-based methods effectively capture global dependencies, they often overlook short-term local variations in time series. Recent methods that adapt large language models (LLMs) into time series forecasting inherit this limitation by treating LLMs as black-box encoders, relying solely on the final-layer output and underutilizing hierarchical representations. To address this limitation, we propose Logo-LLM, a novel LLM-based framework that explicitly extracts and models multi-scale temporal features from different layers of a pre-trained LLM. Through empirical analysis, we show that shallow layers of LLMs capture local dynamics in time series, while deeper layers encode global trends. Moreover, Logo-LLM introduces lightweight Local-Mixer and Global-Mixer modules to align and integrate features with the temporal input across layers. Extensive experiments demonstrate that Logo-LLM achieves superior performance across diverse benchmarks, with strong generalization in few-shot and zero-shot settings while maintaining low computational overhead.

[Arxiv](https://arxiv.org/abs/2505.11017)