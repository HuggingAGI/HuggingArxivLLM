# CoCoA：一种量化大语言模型输出不确定性的通用方法，通过整合置信度和一致性实现

发布时间：2025年02月07日

`LLM理论` `不确定性量化`

> CoCoA: A Generalized Approach to Uncertainty Quantification by Integrating Confidence and Consistency of LLM Outputs

# 摘要

> 针对大型语言模型（LLMs）的不确定性量化（UQ）方法包含多种途径，其中信息型和一致性型方法尤为突出。信息型方法关注模型置信度，以令牌概率形式表达；一致性型方法则评估通过重复采样生成的多个输出之间的语义关系。近期的结合方法在多种场景中表现优异，但有时却未能超越简单基线方法。我们的研究揭示了LLMs作为概率模型的独特属性，这些属性解释了为何某些UQ方法在特定任务中表现欠佳。基于这些发现，我们提出了一种全新的模型置信度与输出一致性合成方式，衍生出一系列高效且稳健的UQ方法。我们在问答、摘要生成及机器翻译等多种任务中进行评估，结果显示相较于现有方法，我们的方案实现了显著提升。

> Uncertainty quantification (UQ) methods for Large Language Models (LLMs) encompasses a variety of approaches, with two major types being particularly prominent: information-based, which focus on model confidence expressed as token probabilities, and consistency-based, which assess the semantic relationship between multiple outputs generated using repeated sampling. Several recent methods have combined these two approaches and shown impressive performance in various applications. However, they sometimes fail to outperform much simpler baseline methods. Our investigation reveals distinctive characteristics of LLMs as probabilistic models, which help to explain why these UQ methods underperform in certain tasks. Based on these findings, we propose a new way of synthesizing model confidence and output consistency that leads to a family of efficient and robust UQ methods. We evaluate our approach across a variety of tasks such as question answering, abstractive summarization, and machine translation, demonstrating sizable improvements over state-of-the-art UQ approaches.

[Arxiv](https://arxiv.org/abs/2502.04964)