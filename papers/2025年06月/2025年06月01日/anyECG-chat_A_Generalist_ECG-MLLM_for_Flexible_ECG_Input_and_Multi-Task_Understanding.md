# # anyECG-chat：支持灵活ECG输入和多任务理解的通用ECG多语言大模型

发布时间：2025年06月01日

`LLM应用` `心血管`

> anyECG-chat: A Generalist ECG-MLLM for Flexible ECG Input and Multi-Task Understanding

# 摘要

> 多模态大语言模型（MLLMs）的出现为心电图（ECG）分析带来了新的可能性，但现有研究主要集中在单一场景下的报告生成任务，未能充分发挥MLLMs的潜力。为此，我们开发了支持更广泛任务和更灵活ECG输入的anyECG数据集和anyECG-chat模型。anyECG数据集涵盖了报告生成、异常波形定位和开放性问题回答等多种任务，并引入了适用于家庭环境的长时间低导联ECG以及临床实践中常见的多ECG比较场景。anyECG-chat模型支持动态长度ECG输入和多ECG输入，通过三阶段课程训练实现。实验结果表明，anyECG-chat能够支持多种实际应用场景，包括异常波形定位、多ECG比较分析等，展现了强大的实用价值。

> The advent of multimodal large language models (MLLMs) has sparked interest in their application to electrocardiogram (ECG) analysis. However, existing ECG-focused MLLMs primarily focus on report generation tasks, often limited to single 12-lead, short-duration (10s) ECG inputs, thereby underutilizing the potential of MLLMs. To this end, we aim to develop a MLLM for ECG analysis that supports a broader range of tasks and more flexible ECG inputs. However, existing ECG-QA datasets are often monotonous. To address this gap, we first constructed the anyECG dataset, which encompasses a wide variety of tasks, including report generation, abnormal waveform localization, and open-ended question answering. In addition to standard hospital ECGs, we introduced long-duration reduced-lead ECGs for home environments and multiple ECG comparison scenarios commonly encountered in clinical practice. Furthermore, we propose the anyECG-chat model, which supports dynamic-length ECG inputs and multiple ECG inputs. We trained the model using a three-stage curriculum training recipe with the anyECG dataset. A comprehensive evaluation was conducted, demonstrating that anyECG-chat is capable of supporting various practical application scenarios, including not only common report generation tasks but also abnormal waveform localization for long-duration reduced-lead ECGs in home environments and comprehensive comparative analysis of multiple ECGs.

[Arxiv](https://arxiv.org/abs/2506.00942)