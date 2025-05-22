# # UrduFactCheck：一个结合证据增强与基准测试的乌尔都语智能事实核查系统

发布时间：2025年05月20日

`LLM应用` `事实核查`

> UrduFactCheck: An Agentic Fact-Checking Framework for Urdu with Evidence Boosting and Benchmarking

# 摘要

> 大型语言模型（LLMs）的广泛应用引发了对其输出事实可靠性的担忧，尤其是乌尔都语等资源匮乏语言领域。目前的事实核查解决方案几乎全部针对英语，全球2亿多乌尔都语使用者的需求被忽视。我们推出了UrduFactCheck——首个专为乌尔都语设计的全面模块化事实核查框架。系统搭载动态多策略证据检索管道，结合单语和翻译方法，解决高质量乌尔都语证据匮乏问题。我们发布了两个全新手工标注基准数据集：用于声明验证的UrduFactBench和用于评估LLM事实性的UrduFactQA。实验表明，UrduFactCheck，特别是其翻译增强版本，在多个指标上超越基线和开源替代方案。我们对12个最先进LLM在乌尔都语事实问答任务上的表现进行了基准测试，揭示了专有模型与开源模型之间的显著差距。UrduFactCheck的代码和数据集已开源，并可在https://github.com/mbzuai-nlp/UrduFactCheck上获取。

> The rapid use of large language models (LLMs) has raised critical concerns regarding the factual reliability of their outputs, especially in low-resource languages such as Urdu. Existing automated fact-checking solutions overwhelmingly focus on English, leaving a significant gap for the 200+ million Urdu speakers worldwide. In this work, we introduce UrduFactCheck, the first comprehensive, modular fact-checking framework specifically tailored for Urdu. Our system features a dynamic, multi-strategy evidence retrieval pipeline that combines monolingual and translation-based approaches to address the scarcity of high-quality Urdu evidence. We curate and release two new hand-annotated benchmarks: UrduFactBench for claim verification and UrduFactQA for evaluating LLM factuality. Extensive experiments demonstrate that UrduFactCheck, particularly its translation-augmented variants, consistently outperforms baselines and open-source alternatives on multiple metrics. We further benchmark twelve state-of-the-art (SOTA) LLMs on factual question answering in Urdu, highlighting persistent gaps between proprietary and open-source models. UrduFactCheck's code and datasets are open-sourced and publicly available at https://github.com/mbzuai-nlp/UrduFactCheck.

[Arxiv](https://arxiv.org/abs/2505.15063)