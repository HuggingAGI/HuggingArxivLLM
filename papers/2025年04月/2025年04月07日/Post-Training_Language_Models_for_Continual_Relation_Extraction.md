# # 摘要
最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年04月07日

`其他` `问答系统`

> Post-Training Language Models for Continual Relation Extraction

# 摘要

> <翻译失败>

> Real-world data, such as news articles, social media posts, and chatbot conversations, is inherently dynamic and non-stationary, presenting significant challenges for constructing real-time structured representations through knowledge graphs (KGs). Relation Extraction (RE), a fundamental component of KG creation, often struggles to adapt to evolving data when traditional models rely on static, outdated datasets. Continual Relation Extraction (CRE) methods tackle this issue by incrementally learning new relations while preserving previously acquired knowledge. This study investigates the application of pre-trained language models (PLMs), specifically large language models (LLMs), to CRE, with a focus on leveraging memory replay to address catastrophic forgetting. We evaluate decoder-only models (eg, Mistral-7B and Llama2-7B) and encoder-decoder models (eg, Flan-T5 Base) on the TACRED and FewRel datasets. Task-incremental fine-tuning of LLMs demonstrates superior performance over earlier approaches using encoder-only models like BERT on TACRED, excelling in seen-task accuracy and overall performance (measured by whole and average accuracy), particularly with the Mistral and Flan-T5 models. Results on FewRel are similarly promising, achieving second place in whole and average accuracy metrics. This work underscores critical factors in knowledge transfer, language model architecture, and KG completeness, advancing CRE with LLMs and memory replay for dynamic, real-time relation extraction.

[Arxiv](https://arxiv.org/abs/2504.05214)