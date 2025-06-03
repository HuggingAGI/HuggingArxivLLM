# 多语言定义建模

发布时间：2025年06月02日

`LLM应用` `多语言`

> Multilingual Definition Modeling

# 摘要

> 本文首次提出了一项关于定义建模的多语言研究。我们利用西班牙语、法语、葡萄牙语和德语四种新语言的单语词典数据，深入研究了在这些数据上微调的预训练多语言模型在单义词定义建模中的表现。同时，我们采用零样本方法，评估了两种流行的基于聊天的大型语言模型（LLMs）在该任务中的多语言能力。实验结果显示，多语言模型的性能与英语相当，但未能有效利用跨语言的协同优势，而LLMs则在整体性能上表现更优。通过人工评估LLM生成的定义，我们不仅发现了这些模型在零样本和少样本任务中的潜力，也揭示了它们的局限性。最后，我们发现，使用BERTScore评估的任务表现与多语言LLM基准测试中的表现高度相关，这表明我们的任务为现有方法提供了一个计算高效、稳定且自然的替代方案。

> In this paper, we propose the first multilingual study on definition modeling. We use monolingual dictionary data for four new languages (Spanish, French, Portuguese, and German) and perform an in-depth empirical study to test the performance of pre-trained multilingual language models on definition modeling of monosemic words when finetuned on this data. Furthermore, we use a zero-shot approach to test the multilingual capabilities of two popular chat-based Large Language Models (LLMs) in the task. Results show that multilingual language models can perform on-pair with English but cannot leverage potential cross-lingual synergies, with LLMs generally offering better performance overall. A comprehensive human evaluation of the LLM-generated definition highlights the zero and few-shot capabilities of these models in this new task, also showing their shortcomings. Finally, we show that performance on our task via BERTScore strongly correlates to the performance on multilingual LLM benchmarks, suggesting that our task offers a viable compute-constrained, stable and natural alternative to these.

[Arxiv](https://arxiv.org/abs/2506.01489)