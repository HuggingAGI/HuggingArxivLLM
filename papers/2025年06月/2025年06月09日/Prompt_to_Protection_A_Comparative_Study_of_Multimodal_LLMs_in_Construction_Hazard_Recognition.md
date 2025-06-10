# 从提示到防护：多模态大语言模型在建筑风险识别中的对比研究

发布时间：2025年06月09日

`LLM应用

理由：这篇论文主要探讨了多模态大型语言模型在建筑工地视觉风险识别中的应用，属于LLM应用的范畴。` `建筑安全`

> Prompt to Protection: A Comparative Study of Multimodal LLMs in Construction Hazard Recognition

# 摘要

> 近年来，多模态大型语言模型（LLMs）的出现为提升建筑工地的视觉风险识别带来了全新的机遇。与传统的计算机视觉模型依赖特定领域训练和大量数据集不同，现代LLMs能够通过简单的自然语言提示来理解和描述复杂的视觉场景。然而，尽管人们对多模态LLMs的应用表现出浓厚兴趣，但目前对其在建筑领域安全关键视觉任务中的表现研究仍然有限。

为填补这一空白，本研究对Claude-3 Opus、GPT-4.5、GPT-4o、GPT-o3和Gemini 2.0 Pro这五种先进LLMs进行了对比评估，旨在测试它们从真实建筑工地图像中识别潜在风险的能力。每种模型均在三种提示策略下接受测试：零样本提示、少样本提示和链式思维（CoT）提示。零样本提示采用了最少的指令，少样本提示则加入了基础安全背景和风险源记忆辅助，而CoT提示则提供了分步推理示例以引导模型思考。

研究采用精确率、召回率和F1值等指标对所有条件下的模型表现进行了定量分析。结果显示，提示策略对模型性能产生了显著影响，其中CoT提示在所有模型中均表现出更高的准确性。此外，不同条件下模型的表现存在差异，GPT-4.5和GPT-o3在大多数情况下优于其他模型。研究结果还凸显了提示设计在提升多模态LLMs在建筑安全应用中准确性和一致性方面的重要性。

本研究为将提示工程与LLMs相结合的实际风险识别提供了可操作的见解，为开发更可靠的AI辅助安全系统做出了贡献。

> The recent emergence of multimodal large language models (LLMs) has introduced new opportunities for improving visual hazard recognition on construction sites. Unlike traditional computer vision models that rely on domain-specific training and extensive datasets, modern LLMs can interpret and describe complex visual scenes using simple natural language prompts. However, despite growing interest in their applications, there has been limited investigation into how different LLMs perform in safety-critical visual tasks within the construction domain. To address this gap, this study conducts a comparative evaluation of five state-of-the-art LLMs: Claude-3 Opus, GPT-4.5, GPT-4o, GPT-o3, and Gemini 2.0 Pro, to assess their ability to identify potential hazards from real-world construction images. Each model was tested under three prompting strategies: zero-shot, few-shot, and chain-of-thought (CoT). Zero-shot prompting involved minimal instruction, few-shot incorporated basic safety context and a hazard source mnemonic, and CoT provided step-by-step reasoning examples to scaffold model thinking. Quantitative analysis was performed using precision, recall, and F1-score metrics across all conditions. Results reveal that prompting strategy significantly influenced performance, with CoT prompting consistently producing higher accuracy across models. Additionally, LLM performance varied under different conditions, with GPT-4.5 and GPT-o3 outperforming others in most settings. The findings also demonstrate the critical role of prompt design in enhancing the accuracy and consistency of multimodal LLMs for construction safety applications. This study offers actionable insights into the integration of prompt engineering and LLMs for practical hazard recognition, contributing to the development of more reliable AI-assisted safety systems.

[Arxiv](https://arxiv.org/abs/2506.07436)