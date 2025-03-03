# 大模型是否能成为脑电分析的优秀特征提取工具？

发布时间：2025年02月28日

`LLM应用` `时间序列分析`

> Are foundation models useful feature extractors for electroencephalography analysis?

# 摘要

> 自然语言处理和计算机视觉中基础模型的成功，推动了类似方法在通用时间序列分析中的应用。尽管这些模型在多种任务中表现出色，但在医疗领域（尤其是数据有限的情况下）的应用仍鲜有探索。为解决这一问题，我们研究了基础模型在涉及脑电图（EEG）的医学时间序列分析中的有效性。

通过在年龄预测、癫痫检测以及与临床相关的EEG事件分类等任务上的广泛实验，我们将其诊断准确性与专用EEG模型进行了对比。分析表明，基础模型能够提取有意义的EEG特征，在无需领域适配的情况下超越专用模型，并定位任务特定的生物标志物。此外，我们证明了上下文长度等架构选择对诊断准确性有显著影响。

总体而言，本研究发现，具备通用时间序列理解能力的基础模型摆脱了对大规模领域特定数据集的依赖，使其成为临床实践中宝贵的工具。


> The success of foundation models in natural language processing and computer vision has motivated similar approaches for general time series analysis. While these models are effective for a variety of tasks, their applicability in medical domains with limited data remains largely unexplored. To address this, we investigate the effectiveness of foundation models in medical time series analysis involving electroencephalography (EEG). Through extensive experiments on tasks such as age prediction, seizure detection, and the classification of clinically relevant EEG events, we compare their diagnostic accuracy with that of specialised EEG models. Our analysis shows that foundation models extract meaningful EEG features, outperform specialised models even without domain adaptation, and localise task-specific biomarkers. Moreover, we demonstrate that diagnostic accuracy is substantially influenced by architectural choices such as context length. Overall, our study reveals that foundation models with general time series understanding eliminate the dependency on large domain-specific datasets, making them valuable tools for clinical practice.

[Arxiv](https://arxiv.org/abs/2502.21086)