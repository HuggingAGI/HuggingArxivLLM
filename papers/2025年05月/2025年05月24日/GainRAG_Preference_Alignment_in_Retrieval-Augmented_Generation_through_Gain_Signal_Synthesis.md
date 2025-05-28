# GainRAG: 利用增益信号合成实现检索增强生成中的偏好对齐

发布时间：2025年05月24日

`RAG` `信息检索`

> GainRAG: Preference Alignment in Retrieval-Augmented Generation through Gain Signal Synthesis

# 摘要

> 检索增强生成（RAG）框架通过在大型语言模型（LLMs）中引入检索模块，将检索信息动态注入输入上下文，在多种NLP任务中取得了显著成功。然而，本研究发现RAG框架中检索器与LLMs之间存在偏好差距，这限制了系统性能的进一步提升。具体而言，一些高度相关的段落可能因包含复杂或矛盾信息而干扰LLMs推理；同时，一些间接相关甚至不准确的内容可能通过提供提示信息或逻辑线索，帮助LLMs生成更准确的答案。为解决这一问题，我们提出了GainRAG方法，通过定义新指标“增益”来衡量输入段落对正确输出的贡献程度，从而统一检索器和LLMs的偏好。具体而言，我们提出了一种估算增益信号的方法，并仅使用有限数据训练中间件，以对齐检索器和LLMs的偏好。此外，我们引入了伪段落策略来缓解性能下降问题。在6个数据集上的实验结果验证了GainRAG的有效性。

> The Retrieval-Augmented Generation (RAG) framework introduces a retrieval module to dynamically inject retrieved information into the input context of large language models (LLMs), and has demonstrated significant success in various NLP tasks. However, the current study points out that there is a preference gap between retrievers and LLMs in the RAG framework, which limit the further improvement of system performance. Some highly relevant passages may interfere with LLM reasoning because they contain complex or contradictory information; while some indirectly related or even inaccurate content may help LLM generate more accurate answers by providing suggestive information or logical clues. To solve this, we propose GainRAG, a novel approach that aligns the retriever's and LLM's preferences by defining a new metric, "gain", which measure how well an input passage contributes to correct outputs. Specifically, we propose a method to estimate these gain signals and train a middleware that aligns the preferences of the retriever and the LLM using only limited data. In addition, we introduce a pseudo-passage strategy to mitigate degradation. The experimental results on 6 datasets verify the effectiveness of GainRAG.

[Arxiv](https://arxiv.org/abs/2505.18710)