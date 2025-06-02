# # 从图像到信号：大型视觉模型是否适用于时间序列分析？

发布时间：2025年05月29日

`其他` `时间序列分析` `多模态模型`

> From Images to Signals: Are Large Vision Models Useful for Time Series Analysis?

# 摘要

> 基于Transformer的模型在时间序列研究中越来越受到关注，推动了对大型语言模型（LLMs）和时间序列分析基础模型的兴趣。随着领域向多模态发展，大型视觉模型（LVMs）正成为一个有前途的方向。过去，关于Transformer和LLMs在时间序列中的有效性一直存在争议。对于LVMs，类似的问题出现了：LVMs是否真正对时间序列分析有用？为了解答这个问题，我们设计并进行了第一个基于原则的研究，涉及4种LVMs、8种成像方法、18个数据集和26个基准模型，涵盖高级（分类）和低级（预测）任务，并进行了广泛的消融分析。我们的研究发现，LVMs确实对时间序列分类有用，但在预测方面面临挑战。尽管有效，但当代最好的LVM预测器仅限于特定类型的LVMs和成像方法，对预测时期存在偏见，并且在利用长回顾窗口方面的能力有限。我们希望我们的发现能为未来基于LVM和多模态的时间序列任务解决方案的研究奠定基础。

> Transformer-based models have gained increasing attention in time series research, driving interest in Large Language Models (LLMs) and foundation models for time series analysis. As the field moves toward multi-modality, Large Vision Models (LVMs) are emerging as a promising direction. In the past, the effectiveness of Transformer and LLMs in time series has been debated. When it comes to LVMs, a similar question arises: are LVMs truely useful for time series analysis? To address it, we design and conduct the first principled study involving 4 LVMs, 8 imaging methods, 18 datasets and 26 baselines across both high-level (classification) and low-level (forecasting) tasks, with extensive ablation analysis. Our findings indicate LVMs are indeed useful for time series classification but face challenges in forecasting. Although effective, the contemporary best LVM forecasters are limited to specific types of LVMs and imaging methods, exhibit a bias toward forecasting periods, and have limited ability to utilize long look-back windows. We hope our findings could serve as a cornerstone for future research on LVM- and multimodal-based solutions to different time series tasks.

[Arxiv](https://arxiv.org/abs/2505.24030)