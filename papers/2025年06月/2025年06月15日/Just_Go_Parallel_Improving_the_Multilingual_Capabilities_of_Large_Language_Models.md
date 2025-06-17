# 直接并行：提升大型语言模型的多语言能力

发布时间：2025年06月15日

`LLM应用` `多语言处理`

> Just Go Parallel: Improving the Multilingual Capabilities of Large Language Models

# 摘要

> 大型语言模型（LLMs）即使没有在平行数据上进行显式训练，也展现出了卓越的翻译能力。这一特性让部分研究者认为，构建多语言模型可能不再需要平行数据。虽然有人将其归因于大型语言模型因规模而产生的涌现能力，但最新研究指出，这实际上是由于训练数据中存在偶然的双语信号所致。为了更好地利用平行数据提升基于多语言编码器和编码器-解码器模型的多语言能力，研究者提出了多种方法。然而，某些基于解码器的LLMs选择忽略平行数据。本研究系统地探讨了在LLMs中加入平行数据对其多语言能力的影响，重点关注翻译和多语言常识推理领域。通过一系列受控实验，我们证实了平行数据能够显著提升LLMs的多语言能力。

> Large language models (LLMs) have demonstrated impressive translation capabilities even without being explicitly trained on parallel data. This remarkable property has led some to believe that parallel data is no longer necessary for building multilingual language models. While some attribute this to the emergent abilities of LLMs due to scale, recent work suggests that it is actually caused by incidental bilingual signals present in the training data. Various methods have been proposed to maximize the utility of parallel data to enhance the multilingual capabilities of multilingual encoder-based and encoder-decoder language models. However, some decoder-based LLMs opt to ignore parallel data instead. In this work, we conduct a systematic study on the impact of adding parallel data on LLMs' multilingual capabilities, focusing specifically on translation and multilingual common-sense reasoning. Through controlled experiments, we demonstrate that parallel data can significantly improve LLMs' multilingual capabilities.

[Arxiv](https://arxiv.org/abs/2506.13044)