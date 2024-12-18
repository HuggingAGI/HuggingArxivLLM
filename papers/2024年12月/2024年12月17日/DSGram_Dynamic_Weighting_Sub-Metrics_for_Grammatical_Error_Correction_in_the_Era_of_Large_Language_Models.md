# DSGram：在大型语言模型时代用于语法错误纠正的动态加权子指标

发布时间：2024年12月17日

`LLM应用` `语言模型` `语法错误纠正`

> DSGram: Dynamic Weighting Sub-Metrics for Grammatical Error Correction in the Era of Large Language Models

# 摘要

> 评估语法错误纠正（GEC）模型的性能愈发困难，因为基于大型语言模型（LLM）的 GEC 系统所给出的纠正常常与提供的黄金参考存在差异。这种不一致削弱了传统基于参考的评估指标的可靠性。在本研究中，我们为 GEC 模型提出了一个全新的评估框架——DSGram，它融合了语义连贯性、编辑级别和流畅性，并采用了动态加权机制。我们的框架将层次分析法（AHP）与大型语言模型相结合，以确定各种评估标准的相对重要性。此外，我们还开发了一个包含人类注释和 LLM 模拟句子的数据集，用于验证我们的算法并微调更具成本效益的模型。实验结果显示，我们提出的方法增强了 GEC 模型评估的有效性。

> Evaluating the performance of Grammatical Error Correction (GEC) models has become increasingly challenging, as large language model (LLM)-based GEC systems often produce corrections that diverge from provided gold references. This discrepancy undermines the reliability of traditional reference-based evaluation metrics. In this study, we propose a novel evaluation framework for GEC models, DSGram, integrating Semantic Coherence, Edit Level, and Fluency, and utilizing a dynamic weighting mechanism. Our framework employs the Analytic Hierarchy Process (AHP) in conjunction with large language models to ascertain the relative importance of various evaluation criteria. Additionally, we develop a dataset incorporating human annotations and LLM-simulated sentences to validate our algorithms and fine-tune more cost-effective models. Experimental results indicate that our proposed approach enhances the effectiveness of GEC model evaluations.

[Arxiv](https://arxiv.org/abs/2412.12832)