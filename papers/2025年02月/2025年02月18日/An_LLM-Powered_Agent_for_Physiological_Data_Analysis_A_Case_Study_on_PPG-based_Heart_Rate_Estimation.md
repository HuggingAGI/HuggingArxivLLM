# LLM驱动的生理数据分析代理：基于PPG的心率估计案例分析

发布时间：2025年02月18日

`Agent` `健康监测`

> An LLM-Powered Agent for Physiological Data Analysis: A Case Study on PPG-based Heart Rate Estimation

# 摘要

> 大型语言模型（LLMs）正在通过交互式沟通推动医疗领域的革命，显著提升了诊断、患者护理和决策支持的水平。最近，它们被应用于分析生理时间序列数据，例如可穿戴设备数据，以提取健康见解。然而，现有方法直接将原始数值序列嵌入提示中，这不仅超过了令牌限制，还增加了计算成本。一些研究尝试将从时间序列中提取的特征整合到文本提示中，或采用多模态方法。然而，由于LLMs在分析严谨性上的局限性以及在解释连续波形方面的低效，这些方法往往产生通用且不可靠的输出。为了解决这一问题，本文开发了一个基于LLM的生理时间序列分析代理，旨在弥合LLMs与现有分析工具之间的差距。该代理基于开源的LLM框架OpenCHA，集成了用户交互、数据源和分析工具，以生成准确的健康见解。为了验证其有效性，我们实施了一个案例研究，使用PPG信号进行心率（HR）估计，数据集来自远程健康监测研究中的PPG和心电图（ECG）记录。代理的性能与OpenAI GPT-4o-mini和GPT-4o进行了比较，ECG作为HR估计的黄金标准。实验结果表明，我们的代理显著优于基准模型，实现了更低的错误率和更可靠的HR估计。代理的实现已公开发布在GitHub上。

> Large language models (LLMs) are revolutionizing healthcare by improving diagnosis, patient care, and decision support through interactive communication. More recently, they have been applied to analyzing physiological time-series like wearable data for health insight extraction. Existing methods embed raw numerical sequences directly into prompts, which exceeds token limits and increases computational costs. Additionally, some studies integrated features extracted from time-series in textual prompts or applied multimodal approaches. However, these methods often produce generic and unreliable outputs due to LLMs' limited analytical rigor and inefficiency in interpreting continuous waveforms. In this paper, we develop an LLM-powered agent for physiological time-series analysis aimed to bridge the gap in integrating LLMs with well-established analytical tools. Built on the OpenCHA, an open-source LLM-powered framework, our agent features an orchestrator that integrates user interaction, data sources, and analytical tools to generate accurate health insights. To evaluate its effectiveness, we implement a case study on heart rate (HR) estimation from Photoplethysmogram (PPG) signals using a dataset of PPG and Electrocardiogram (ECG) recordings in a remote health monitoring study. The agent's performance is benchmarked against OpenAI GPT-4o-mini and GPT-4o, with ECG serving as the gold standard for HR estimation. Results demonstrate that our agent significantly outperforms benchmark models by achieving lower error rates and more reliable HR estimations. The agent implementation is publicly available on GitHub.

[Arxiv](https://arxiv.org/abs/2502.12836)