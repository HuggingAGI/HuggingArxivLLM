# 利用幻觉偏好优化减少大型语言模型中的幻觉翻译

发布时间：2025年01月28日

`LLM应用

理由：这篇论文讨论了如何通过微调大型语言模型（LLM）来减少机器翻译中的幻觉问题，并提出了一个数据创建框架来生成专注于幻觉的偏好数据集。这属于LLM在实际应用中的改进和优化，因此应归类为LLM应用。` `机器翻译`

> Mitigating Hallucinated Translations in Large Language Models with Hallucination-focused Preference Optimization

# 摘要

> 机器翻译（MT）正经历一场范式转变，基于微调大型语言模型（LLM）的系统正逐渐超越传统编码器-解码器模型。然而，LLM系统更容易产生幻觉，严重影响用户信任和安全。以往研究多聚焦于传统MT模型，采用事后缓解策略——检测并重译幻觉翻译。虽然有效，但这种方法增加了部署复杂性和延迟。为此，我们提出了一种在模型训练阶段内在缓解幻觉的方法。具体而言，我们开发了一个数据创建框架，生成专注于幻觉的偏好数据集。在这些数据集上微调LLM，平均减少了96%的幻觉率，同时保持翻译质量。在零-shot场景下，我们的方法在三个未见目标语言上平均减少了89%的幻觉。

> Machine Translation (MT) is undergoing a paradigm shift, with systems based on fine-tuned large language models (LLM) becoming increasingly competitive with traditional encoder-decoder models trained specifically for translation tasks. However, LLM-based systems are at a higher risk of generating hallucinations, which can severely undermine user's trust and safety. Most prior research on hallucination mitigation focuses on traditional MT models, with solutions that involve post-hoc mitigation - detecting hallucinated translations and re-translating them. While effective, this approach introduces additional complexity in deploying extra tools in production and also increases latency. To address these limitations, we propose a method that intrinsically learns to mitigate hallucinations during the model training phase. Specifically, we introduce a data creation framework to generate hallucination focused preference datasets. Fine-tuning LLMs on these preference datasets reduces the hallucination rate by an average of 96% across five language pairs, while preserving overall translation quality. In a zero-shot setting our approach reduces hallucinations by 89% on an average across three unseen target languages.

[Arxiv](https://arxiv.org/abs/2501.17295)