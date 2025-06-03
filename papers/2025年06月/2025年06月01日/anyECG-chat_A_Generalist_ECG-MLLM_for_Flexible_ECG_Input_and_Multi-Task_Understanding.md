# # **anyECG-chat：通用ECG-MLLM，支持灵活ECG输入与多任务理解**

发布时间：2025年06月01日

`LLM应用` `人工智能`

> anyECG-chat: A Generalist ECG-MLLM for Flexible ECG Input and Multi-Task Understanding

# 摘要

> 多模态大型语言模型 (MLLMs) 的出现激发了人们对将它们应用于心电图 (ECG) 分析的兴趣。然而，现有的专注于 ECG 的 MLLMs 主要关注报告生成任务，通常仅限于单个 12 导联、短时长（10 秒）的 ECG 输入，因此未能充分利用 MLLMs 的潜力。为此，我们旨在开发一个支持更广泛任务和更灵活 ECG 输入的 ECG 分析 MLLM。

然而，现有的 ECG-QA 数据集往往单调乏味。为了解决这一差距，我们首先构建了 anyECG 数据集，涵盖了多种任务，包括报告生成、异常波形定位和开放性问题解答。除了标准的医院 ECG 外，我们还引入了适用于家庭环境的长时程减少导联 ECG 以及临床实践中常见的多个 ECG 比较场景。

此外，我们提出了支持动态长度 ECG 输入和多个 ECG 输入的 anyECG-chat 模型。我们使用任何 ECG 数据集进行了三阶段课程训练。进行了全面的评估，证明 anyECG-chat 能够支持各种实际应用场景，包括不仅常见的报告生成任务，还包括家庭环境中长时程减少导联 ECG 的异常波形定位以及多个 ECG 的综合比较分析。

> The advent of multimodal large language models (MLLMs) has sparked interest in their application to electrocardiogram (ECG) analysis. However, existing ECG-focused MLLMs primarily focus on report generation tasks, often limited to single 12-lead, short-duration (10s) ECG inputs, thereby underutilizing the potential of MLLMs. To this end, we aim to develop a MLLM for ECG analysis that supports a broader range of tasks and more flexible ECG inputs. However, existing ECG-QA datasets are often monotonous. To address this gap, we first constructed the anyECG dataset, which encompasses a wide variety of tasks, including report generation, abnormal waveform localization, and open-ended question answering. In addition to standard hospital ECGs, we introduced long-duration reduced-lead ECGs for home environments and multiple ECG comparison scenarios commonly encountered in clinical practice. Furthermore, we propose the anyECG-chat model, which supports dynamic-length ECG inputs and multiple ECG inputs. We trained the model using a three-stage curriculum training recipe with the anyECG dataset. A comprehensive evaluation was conducted, demonstrating that anyECG-chat is capable of supporting various practical application scenarios, including not only common report generation tasks but also abnormal waveform localization for long-duration reduced-lead ECGs in home environments and comprehensive comparative analysis of multiple ECGs.

[Arxiv](https://arxiv.org/abs/2506.00942)