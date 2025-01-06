# 时间序列语言模型：描述性标题生成

发布时间：2025年01月03日

`LLM应用

**理由**：这篇论文主要讨论了如何利用大型语言模型（LLM）来生成时间序列数据的自然语言描述，并提出了一个专门为时间序列描述设计的新型模型TSLM。这属于LLM在特定应用场景（时间序列分析）中的应用，因此分类为LLM应用。` `时间序列分析`

> Time Series Language Model for Descriptive Caption Generation

# 摘要

> 自动生成时间序列数据中可观察模式的代表性自然语言描述，不仅提升了数据的可解释性，简化了分析流程，还增强了时间数据的跨领域应用价值。尽管预训练基础模型在自然语言处理（NLP）和计算机视觉（CV）领域取得了显著进展，但由于数据稀缺，它们在时间序列分析中的应用仍面临挑战。虽然已有多种基于大型语言模型（LLM）的时间序列预测方法被提出，但在LLM背景下，时间序列描述的研究仍显不足。本文提出了一种新型时间序列语言模型TSLM，专为时间序列描述设计。TSLM采用编码器-解码器架构，结合文本提示和时间序列数据表示，捕捉多阶段的细微时间模式，并生成精确的时间序列文本描述。TSLM通过上下文提示的合成数据生成和跨模态密集检索评分去噪生成的数据，有效解决了时间序列描述中的数据稀缺问题。实验结果表明，TSLM在多种时间序列描述数据集上显著优于现有最先进方法。

> The automatic generation of representative natural language descriptions for observable patterns in time series data enhances interpretability, simplifies analysis and increases cross-domain utility of temporal data. While pre-trained foundation models have made considerable progress in natural language processing (NLP) and computer vision (CV), their application to time series analysis has been hindered by data scarcity. Although several large language model (LLM)-based methods have been proposed for time series forecasting, time series captioning is under-explored in the context of LLMs. In this paper, we introduce TSLM, a novel time series language model designed specifically for time series captioning. TSLM operates as an encoder-decoder model, leveraging both text prompts and time series data representations to capture subtle temporal patterns across multiple phases and generate precise textual descriptions of time series inputs. TSLM addresses the data scarcity problem in time series captioning by first leveraging an in-context prompting synthetic data generation, and second denoising the generated data via a novel cross-modal dense retrieval scoring applied to time series-caption pairs. Experimental findings on various time series captioning datasets demonstrate that TSLM outperforms existing state-of-the-art approaches from multiple data modalities by a significant margin.

[Arxiv](https://arxiv.org/abs/2501.01832)