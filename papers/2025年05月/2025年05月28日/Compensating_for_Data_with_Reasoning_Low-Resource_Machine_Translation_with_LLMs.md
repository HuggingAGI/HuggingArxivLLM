# 用推理弥补数据不足，探索LLMs在低资源机器翻译中的应用

发布时间：2025年05月28日

`LLM应用

理由：这篇论文探讨了大型语言模型在多语言机器翻译中的应用，特别是针对低资源语言的挑战。它提出了一种创新的上下文学习方法，并通过实验验证了其有效性。因此，它属于LLM应用类别。` `机器翻译` `语言技术`

> Compensating for Data with Reasoning: Low-Resource Machine Translation with LLMs

# 摘要

> 大型语言模型（LLMs）在多语言机器翻译领域表现卓越，甚至超越传统神经翻译系统。然而，使用LLMs处理低资源语言，尤其是提示工程，仍面临诸多挑战。本文提出了一种创新的上下文学习方法——片段示例提示（Fragment-Shot Prompting），该方法基于句法覆盖范围分割输入并检索翻译示例，同时推出了其扩展版本——基于片段的跨语言示例提示（Pivoted Fragment-Shot），实现了无需直接平行数据的翻译。我们采用GPT-3.5、GPT-4、o1-mini、LLaMA-3.3和DeepSeek-R1模型，针对意大利语与两种 Ladino 方言进行评估，得出了三项重要发现：（1）片段示例提示在处理和翻译低资源语言时表现优异，句法覆盖范围与翻译质量呈正相关；（2）推理能力更强的模型能更高效地利用检索知识，显著提升翻译质量，并使基于片段的跨语言示例提示在 Ladino 方言间实现显著改进；（3）从低资源到高资源语言的翻译中，提示工程的改进有限，因为零示例提示已能产生满意结果。我们已公开发布代码和检索语料库，供进一步研究使用。

> Large Language Models (LLMs) have demonstrated strong capabilities in multilingual machine translation, sometimes even outperforming traditional neural systems. However, previous research has highlighted the challenges of using LLMs, particularly with prompt engineering, for low-resource languages. In this work, we introduce Fragment-Shot Prompting, a novel in-context learning method that segments input and retrieves translation examples based on syntactic coverage, along with Pivoted Fragment-Shot, an extension that enables translation without direct parallel data. We evaluate these methods using GPT-3.5, GPT-4o, o1-mini, LLaMA-3.3, and DeepSeek-R1 for translation between Italian and two Ladin variants, revealing three key findings: (1) Fragment-Shot Prompting is effective for translating into and between the studied low-resource languages, with syntactic coverage positively correlating with translation quality; (2) Models with stronger reasoning abilities make more effective use of retrieved knowledge, generally produce better translations, and enable Pivoted Fragment-Shot to significantly improve translation quality between the Ladin variants; and (3) prompt engineering offers limited, if any, improvements when translating from a low-resource to a high-resource language, where zero-shot prompting already yields satisfactory results. We publicly release our code and the retrieval corpora.

[Arxiv](https://arxiv.org/abs/2505.22293)