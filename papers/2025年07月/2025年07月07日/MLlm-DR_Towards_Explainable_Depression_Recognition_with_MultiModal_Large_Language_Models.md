# MLlm-DR：基于多模态大型语言模型的可解释抑郁症识别方法探索

发布时间：2025年07月07日

`LLM应用` `心理健康`

> MLlm-DR: Towards Explainable Depression Recognition with MultiModal Large Language Models

# 摘要

> 自动抑郁症诊断通过分析访谈视频中的多模态信息来预测抑郁评分。然而，以往研究在解释评分依据时往往不够清晰，限制了其临床应用。尽管大型语言模型（LLMs）为可解释的抑郁症诊断提供了新途径，但现有模型在处理多模态数据时缺乏对访谈数据的训练，导致诊断效果欠佳。本文提出了一种新型多模态大型语言模型MLlm-DR，支持多模态信息输入和可解释的抑郁症诊断。MLlm-DR由小型LLMs和轻量级查询模块LQ-former组成。小型LLMs负责生成抑郁评分及评估理由，我们通过构建强大的训练数据集对其进行微调，以增强其在特定任务中的推理能力。LQ-former则从语音和视觉数据中提取与抑郁症相关的特征，帮助模型更高效地处理多模态信息，实现全面的抑郁症诊断。实验结果表明，MLlm-DR在CMDC和E-DAIC-WOZ两个基准数据集上均达到先进水平，充分验证了其有效性和优越性。

> Automated depression diagnosis aims to analyze multimodal information from interview videos to predict participants' depression scores. Previous studies often lack clear explanations of how these scores were determined, limiting their adoption in clinical practice. While the advent of LLMs provides a possible pathway for explainable depression diagnosis, current LLMs capable of processing multimodal data lack training on interview data, resulting in poor diagnostic performance when used directly. In this paper, we propose a novel multimodal large language model (MLlm-DR) that can understand multimodal information inputs and supports explainable depression diagnosis. MLlm-DR integrates a smaller LLMs and a lightweight query module (LQ-former). Specifically, the smaller LLMs is designed to generate depression scores and corresponding evaluation rationales. To enhance its logical reasoning for domain-specific tasks while maintaining practicality, we constructed a robust training dataset to fine-tune it. Meanwhile, the LQ-former captures depression-related features from speech and visual data, aiding the model's ability to process multimodal information, to achieve comprehensive depression diagnosis. Our approach achieves state-of-the-art results on two interview-based benchmark datasets, CMDC and E-DAIC-WOZ, demonstrating its effectiveness and superiority.

[Arxiv](https://arxiv.org/abs/2507.05591)