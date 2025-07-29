# 在资源受限环境中利用开源大型语言模型进行临床信息提取

发布时间：2025年07月28日

`LLM应用`

> Leveraging Open-Source Large Language Models for Clinical Information Extraction in Resource-Constrained Settings

# 摘要

> 医疗报告蕴含丰富临床信息，但因其结构松散且使用专业术语，信息提取颇具挑战。尽管商业化的大型语言模型在临床自然语言处理领域展现出潜力，但其不透明性和隐私问题限制了在医疗领域的应用。本研究在包含28个荷兰语临床信息提取任务的DRAGON基准上评估了九个开源生成型LLMs。我们开发了公开可用的	exttt{llm\_extractinator}框架，用于基于开源生成型LLMs的信息提取，并在零-shot设置下评估模型性能。多个140亿参数模型（Phi-4-14B、Qwen-2.5-14B、DeepSeek-R1-14B）表现优异，而更大规模的Llama-3.3-70B模型则以更高计算成本实现略优性能。将文本翻译为英文后再进行推理会显著降低性能，凸显了原语言处理的重要性。结合我们的框架，开源LLMs为资源有限环境下的临床信息提取提供了有效、可扩展且注重隐私的解决方案。

> Medical reports contain rich clinical information but are often unstructured and written in domain-specific language, posing challenges for information extraction. While proprietary large language models (LLMs) have shown promise in clinical natural language processing, their lack of transparency and data privacy concerns limit their utility in healthcare. This study therefore evaluates nine open-source generative LLMs on the DRAGON benchmark, which includes 28 clinical information extraction tasks in Dutch. We developed \texttt{llm\_extractinator}, a publicly available framework for information extraction using open-source generative LLMs, and used it to assess model performance in a zero-shot setting. Several 14 billion parameter models, Phi-4-14B, Qwen-2.5-14B, and DeepSeek-R1-14B, achieved competitive results, while the bigger Llama-3.3-70B model achieved slightly higher performance at greater computational cost. Translation to English prior to inference consistently degraded performance, highlighting the need of native-language processing. These findings demonstrate that open-source LLMs, when used with our framework, offer effective, scalable, and privacy-conscious solutions for clinical information extraction in low-resource settings.

[Arxiv](https://arxiv.org/abs/2507.20859)