# RAPID: 检索增强并行推理草稿生成技术助力文本视频事件检索

发布时间：2025年01月27日

`RAG

理由：该论文提出了一个名为RAPID的系统，该系统利用大型语言模型（LLMs）和提示学习来增强用户查询的语义校正和上下文信息补充。这种方法与检索增强生成（Retrieval-Augmented Generation, RAG）的概念相符，即通过检索相关信息来增强生成模型的输出。因此，该论文应被分类为RAG。` `多媒体` `视频检索`

> RAPID: Retrieval-Augmented Parallel Inference Drafting for Text-Based Video Event Retrieval

# 摘要

> # 摘要
随着多媒体内容的爆炸式增长，使用文本查询从视频中检索事件变得愈发困难。现有的文本驱动视频事件检索方法往往过于关注对象层面的描述，忽略了上下文信息的重要性。当查询缺乏足够上下文（如缺少位置信息或背景模糊）时，这一问题尤为突出。为此，我们提出了RAPID（Retrieval-Augmented Parallel Inference Drafting）系统，它利用大型语言模型（LLMs）和提示学习的优势，对用户查询进行语义校正并补充相关上下文信息。这些增强后的查询通过并行检索处理，随后通过评估步骤筛选出与原始查询最匹配的结果。我们在自建数据集上的大量实验表明，RAPID在上下文不完整的查询场景下显著优于传统检索方法。该系统在2024年胡志明市AI挑战赛中通过了速度和准确性的双重验证，成功从超过300小时的视频中检索出目标事件。与比赛组织者提出的基线方法相比，RAPID展现了更强的有效性和鲁棒性，充分证明了我们方法的优越性。

> Retrieving events from videos using text queries has become increasingly challenging due to the rapid growth of multimedia content. Existing methods for text-based video event retrieval often focus heavily on object-level descriptions, overlooking the crucial role of contextual information. This limitation is especially apparent when queries lack sufficient context, such as missing location details or ambiguous background elements. To address these challenges, we propose a novel system called RAPID (Retrieval-Augmented Parallel Inference Drafting), which leverages advancements in Large Language Models (LLMs) and prompt-based learning to semantically correct and enrich user queries with relevant contextual information. These enriched queries are then processed through parallel retrieval, followed by an evaluation step to select the most relevant results based on their alignment with the original query. Through extensive experiments on our custom-developed dataset, we demonstrate that RAPID significantly outperforms traditional retrieval methods, particularly for contextually incomplete queries. Our system was validated for both speed and accuracy through participation in the Ho Chi Minh City AI Challenge 2024, where it successfully retrieved events from over 300 hours of video. Further evaluation comparing RAPID with the baseline proposed by the competition organizers demonstrated its superior effectiveness, highlighting the strength and robustness of our approach.

[Arxiv](https://arxiv.org/abs/2501.16303)