# QualiSpeech：融合自然语言推理与描述的语音质量评估数据集

发布时间：2025年03月26日

`LLM应用

理由：这篇论文主要探讨了大语言模型在语音质量评估中的应用，通过自然语言描述提供更详细的评估，并开发了一个新的数据集和基准测试。因此，它属于LLM的应用领域。` `语音技术` `语音评估`

> QualiSpeech: A Speech Quality Assessment Dataset with Natural Language Reasoning and Descriptions

# 摘要

> 本文从全新视角探索语音质量评估，通过自然语言描述提供比传统数值评分更丰富、细腻的见解。自然语言反馈虽能提供有指导性的建议和详细评估，但现有数据集难以满足这一需求。为此，我们推出了QualiSpeech——一个全面的低级别语音质量评估数据集，涵盖11个关键维度，并包含包含推理和上下文见解的详细自然语言评论。同时，我们提出了QualiSpeech基准测试，用于评估听觉大语言模型（LLMs）的低级别语音理解能力。实验结果表明，微调后的听觉LLMs能可靠生成噪声和失真类型的详细描述，并有效识别其类型和时间特性。研究结果进一步凸显了通过引入推理提升质量评估准确性和可靠性的潜力。该数据集将发布于https://huggingface.co/datasets/tsinghua-ee/QualiSpeech。

> This paper explores a novel perspective to speech quality assessment by leveraging natural language descriptions, offering richer, more nuanced insights than traditional numerical scoring methods. Natural language feedback provides instructive recommendations and detailed evaluations, yet existing datasets lack the comprehensive annotations needed for this approach. To bridge this gap, we introduce QualiSpeech, a comprehensive low-level speech quality assessment dataset encompassing 11 key aspects and detailed natural language comments that include reasoning and contextual insights. Additionally, we propose the QualiSpeech Benchmark to evaluate the low-level speech understanding capabilities of auditory large language models (LLMs). Experimental results demonstrate that finetuned auditory LLMs can reliably generate detailed descriptions of noise and distortion, effectively identifying their types and temporal characteristics. The results further highlight the potential for incorporating reasoning to enhance the accuracy and reliability of quality assessments. The dataset will be released at https://huggingface.co/datasets/tsinghua-ee/QualiSpeech.

[Arxiv](https://arxiv.org/abs/2503.20290)