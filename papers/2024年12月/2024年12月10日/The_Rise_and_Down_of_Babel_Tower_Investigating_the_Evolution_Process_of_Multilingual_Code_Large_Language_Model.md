# 《巴别塔的兴衰：探寻多语言代码大型语言模型的演进历程》

发布时间：2024年12月10日

`LLM理论` `语言模型`

> The Rise and Down of Babel Tower: Investigating the Evolution Process of Multilingual Code Large Language Model

# 摘要

> 大型语言模型（LLMs）展现出了强大的多语言能力。然而，预训练期间这些能力形成的机制还不太清楚。本文以代码大型语言模型为实验平台，探究了预训练过程中LLMs多语言能力的演化。基于观察，我们提出了巴别塔假说，它描绘了LLMs获取新语言能力的全过程。学习时，多种语言起初共用一个由主要语言主导的单一知识系统，而后逐渐形成各自语言特有的知识系统。接着，我们通过识别工作语言和语言转换神经元来追踪LLMs的内部状态，验证了上述假说。实验结果显示，LLMs的内部状态变化与我们的巴别塔假说相符。基于这些发现，我们提出了一种为多语言代码LLMs构建优化预训练语料库的新方法，其效果明显优于在原始语料库上训练的LLMs。提出的巴别塔假说为设计预训练数据分布以在LLMs中实现最优多语言能力提供了新视角。

> Large language models (LLMs) have shown significant multilingual capabilities. However, the mechanisms underlying the development of these capabilities during pre-training are not well understood. In this paper, we use code LLMs as an experimental platform to explore the evolution of multilingual capabilities in LLMs during the pre-training process. Based on our observations, we propose the Babel Tower Hypothesis, which describes the entire process of LLMs acquiring new language capabilities. During the learning process, multiple languages initially share a single knowledge system dominated by the primary language and gradually develop language-specific knowledge systems. We then validate the above hypothesis by tracking the internal states of the LLMs through identifying working languages and language transferring neurons. Experimental results show that the internal state changes of the LLM are consistent with our Babel Tower Hypothesis. Building on these insights, we propose a novel method to construct an optimized pre-training corpus for multilingual code LLMs, which significantly outperforms LLMs trained on the original corpus. The proposed Babel Tower Hypothesis provides new insights into designing pre-training data distributions to achieve optimal multilingual capabilities in LLMs.

[Arxiv](https://arxiv.org/abs/2412.07298)