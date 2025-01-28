# 通过支持性的符合性和可解释的小型专用模型，提升多模态大型语言模型在医学时间序列上的视觉检查能力

发布时间：2025年01月27日

`LLM应用

理由：这篇论文主要讨论了如何通过ConMIL（Conformalized Multiple Instance Learning）方法增强大型语言模型（LLMs）在医学时间序列分析中的性能。ConMIL通过与LLMs集成，提升了模型在特定医学任务（如心律失常检测和睡眠分期）中的精确度和解释能力。这表明论文的核心在于应用LLMs解决实际问题，特别是医学领域的决策支持问题，因此应归类为“LLM应用”。` `临床决策`

> Enhancing Visual Inspection Capability of Multi-Modal Large Language Models on Medical Time Series with Supportive Conformalized and Interpretable Small Specialized Models

# 摘要

> # 摘要
大型语言模型（LLMs）在医学时间序列数据的视觉检查中表现出色，能力堪比人类临床医生。然而，其广泛的应用范围限制了领域特定的精确性，且专有权重阻碍了对专业数据集的微调。相比之下，小型专用模型（SSMs）在特定任务中表现优异，但缺乏复杂临床决策所需的上下文推理能力。为解决这些挑战，我们提出了ConMIL（Conformalized Multiple Instance Learning），这是一种与LLMs无缝集成的决策支持SSM。通过多实例学习（MIL）识别临床显著的信号片段，并使用保形预测校准集合值输出，ConMIL增强了LLMs在医学时间序列分析中的解释能力。实验结果表明，ConMIL显著提升了ChatGPT4.0和Qwen2-VL-7B等顶尖LLMs的性能。具体而言，ConMIL支持的Qwen2-VL-7B在心律失常检测和睡眠分期中对自信样本的精确度分别达到了94.92%和96.82%，而独立LLM的准确率仅为46.13%和13.16%。这些发现表明，ConMIL能够有效桥接任务特定精确性和更广泛上下文推理，为AI驱动的临床决策支持提供了更可靠和可解释的解决方案。

> Large language models (LLMs) exhibit remarkable capabilities in visual inspection of medical time-series data, achieving proficiency comparable to human clinicians. However, their broad scope limits domain-specific precision, and proprietary weights hinder fine-tuning for specialized datasets. In contrast, small specialized models (SSMs) excel in targeted tasks but lack the contextual reasoning required for complex clinical decision-making. To address these challenges, we propose ConMIL (Conformalized Multiple Instance Learning), a decision-support SSM that integrates seamlessly with LLMs. By using Multiple Instance Learning (MIL) to identify clinically significant signal segments and conformal prediction for calibrated set-valued outputs, ConMIL enhances LLMs' interpretative capabilities for medical time-series analysis. Experimental results demonstrate that ConMIL significantly improves the performance of state-of-the-art LLMs, such as ChatGPT4.0 and Qwen2-VL-7B. Specifically, \ConMIL{}-supported Qwen2-VL-7B achieves 94.92% and 96.82% precision for confident samples in arrhythmia detection and sleep staging, compared to standalone LLM accuracy of 46.13% and 13.16%. These findings highlight the potential of ConMIL to bridge task-specific precision and broader contextual reasoning, enabling more reliable and interpretable AI-driven clinical decision support.

[Arxiv](https://arxiv.org/abs/2501.16215)