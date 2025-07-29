# MIMII-Agent：借助带有函数调用的大型语言模型实现异常声音检测的相对评估方法

发布时间：2025年07月28日

`LLM应用` `人工智能`

> MIMII-Agent: Leveraging LLMs with Function Calling for Relative Evaluation of Anomalous Sound Detection

# 摘要

> 本文提出了一种创新方法，用于生成机器类型特定的异常声音，旨在评估无监督异常声音检测（UASD）系统在不同机器类型上的性能，即使在缺乏真实异常声音数据的情况下。传统基于关键词的数据增强方法由于依赖手动定义的标签，常常生成不真实的声音，难以应对机器类型和异常模式的多样化。虽然先进的音频生成模型如MIMII-Gen展现出潜力，但它们通常需要依赖异常训练数据，在缺乏多样化异常示例时效果受限。为了解决这些问题，我们提出了一种基于大型语言模型（LLMs）的新型合成方法。该方法能够解读故障的文本描述，并自动选择音频变换函数，将正常机器声音转化为多样化且可信的异常声音。我们通过实验验证了这一方法：仅使用五种机器类型正常声音训练的UASD系统，在真实和合成异常数据上的表现一致。实验结果表明，合成异常与真实异常在不同机器类型上的相对检测难度趋势一致。这一发现不仅验证了我们的假设，还凸显了基于LLM的合成方法在UASD系统相对评估中的有效性。

> This paper proposes a method for generating machine-type-specific anomalies to evaluate the relative performance of unsupervised anomalous sound detection (UASD) systems across different machine types, even in the absence of real anomaly sound data. Conventional keyword-based data augmentation methods often produce unrealistic sounds due to their reliance on manually defined labels, limiting scalability as machine types and anomaly patterns diversify. Advanced audio generative models, such as MIMII-Gen, show promise but typically depend on anomalous training data, making them less effective when diverse anomalous examples are unavailable. To address these limitations, we propose a novel synthesis approach leveraging large language models (LLMs) to interpret textual descriptions of faults and automatically select audio transformation functions, converting normal machine sounds into diverse and plausible anomalous sounds. We validate this approach by evaluating a UASD system trained only on normal sounds from five machine types, using both real and synthetic anomaly data. Experimental results reveal consistent trends in relative detection difficulty across machine types between synthetic and real anomalies. This finding supports our hypothesis and highlights the effectiveness of the proposed LLM-based synthesis approach for relative evaluation of UASD systems.

[Arxiv](https://arxiv.org/abs/2507.20666)