# ChronoSteer：通过合成数据桥接大型语言模型与时间序列基础模型

发布时间：2025年05月15日

`LLM应用` `时间序列预测` `多模态模型`

> ChronoSteer: Bridging Large Language Model and Time Series Foundation Model via Synthetic Data

# 摘要

> 传统预测方法受限于单一模态的时间序列数据，难以充分利用丰富文本信息。近期，大型语言模型（LLMs）和时间序列基础模型（TSFMs）分别在文本推理和时间建模领域展现强大能力。将两者优势结合，构建能够同时利用时序与文本信息的多模态预测模型，成为当前研究的重要课题。

针对事件序列配对数据稀缺问题，我们提出了一种创新的解耦框架：首先利用LLM将文本事件转化为结构化的修订指令，随后运用这些指令引导TSFM的输出。为此，我们开发了ChronoSteer——一款可通过文本修订指令进行引导的多模态TSFM，成功实现了LLM与TSFM的有效连接。

为缓解跨模态指令序列数据短缺问题，我们设计了一种基于合成数据的两阶段训练策略。同时，我们构建了一个高质量的多模态时间序列预测基准，有效解决了评估过程中的信息泄露问题。

实验结果表明，ChronoSteer在与LLM集成后表现优异：仅基于合成数据训练的模型，预测精度较单一模态基础模型提升25.7%，相比现有最优多模态方法也有22.5%的性能提升。


> Conventional forecasting methods rely on unimodal time series data, limiting their ability to exploit rich textual information. Recently, large language models (LLMs) and time series foundation models (TSFMs) have demonstrated powerful capability in textual reasoning and temporal modeling, respectively. Integrating the strengths of both to construct a multimodal model that concurrently leverages both temporal and textual information for future inference has emerged as a critical research challenge. To address the scarcity of event-series paired data, we propose a decoupled framework: an LLM is employed to transform textual events into revision instructions, which are then used to steer the output of TSFM. To implement this framework, we introduce ChronoSteer, a multimodal TSFM that can be steered through textual revision instructions, effectively bridging LLM and TSFM. Moreover, to mitigate the shortage of cross-modal instruction-series paired data, we devise a two-stage training strategy based on synthetic data. In addition, we also construct a high-quality multimodal time series forecasting benchmark to address the information leakage concerns during evaluation. After integrating with an LLM, ChronoSteer, which is trained exclusively on synthetic data, achieves a 25.7% improvement in prediction accuracy compared to the unimodal backbone and a 22.5% gain over the previous state-of-the-art multimodal method.

[Arxiv](https://arxiv.org/abs/2505.10083)