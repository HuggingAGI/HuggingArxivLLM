# PolySmart 与 VIREO @ TRECVid 2024 临时视频搜索

发布时间：2024年12月19日

`LLM应用` `搜索引擎`

> PolySmart and VIREO @ TRECVid 2024 Ad-hoc Video Search

# 摘要

> 今年，我们针对 TRECVid AVS 任务探索生成增强检索。具体而言，借助 Text2Text、Text2Image 以及 Image2Text 这三代技术来强化对文本查询的理解，以应对词汇外问题。通过运用它们的不同组合以及原始查询所检索出的排名列表，我们提交了四次自动运行。在手动运行方面，我们使用大型语言模型（LLM）（比如 GPT4）依据搜索引擎的概念库重新表述测试查询，并且再次人工核查，确保重新表述的查询中所用的所有概念都在库中。结果显示，原始查询与生成查询的融合在 TV24 查询集上的表现优于原始查询。生成的查询从原始查询中检索出了不同的排名列表。

> This year, we explore generation-augmented retrieval for the TRECVid AVS task. Specifically, the understanding of textual query is enhanced by three generations, including Text2Text, Text2Image, and Image2Text, to address the out-of-vocabulary problem. Using different combinations of them and the rank list retrieved by the original query, we submitted four automatic runs. For manual runs, we use a large language model (LLM) (i.e., GPT4) to rephrase test queries based on the concept bank of the search engine, and we manually check again to ensure all the concepts used in the rephrased queries are in the bank. The result shows that the fusion of the original and generated queries outperforms the original query on TV24 query sets. The generated queries retrieve different rank lists from the original query.

[Arxiv](https://arxiv.org/abs/2412.15494)