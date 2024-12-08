# 零索引互联网搜索助力大型语言模型的生成

发布时间：2024年11月29日

`RAG` `互联网` `生成推理`

> Zero-Indexing Internet Search Augmented Generation for Large Language Models

# 摘要

> 检索增强生成已成为提升大型语言模型性能的有效手段。此方法通常依靠内部检索模块，利用各类索引机制管理静态预处理的语料库。但在生成推理时，若要整合尚未更新至语料库的最新信息，这种模式往往力不从心。本文探索了一种替代方案，借助标准搜索引擎 API 动态整合最新的在线信息（无需为任何固定语料库维护索引），进而提升生成内容的质量。我们设计了基于协作 LLM 的范式，其中包含：（i）一个解析器-LLM，用于判定是否需要互联网增强生成，若需要则在单次推理中提取搜索关键词；（ii）一种混合排序策略，对检索到的 HTML 文件重新排序，以消除搜索引擎 API 引入的偏差；（iii）一个提取器-LLM，能够从每个 HTML 文件的新内容中准确高效地提取相关信息。我们开展了大量的实证研究来评估这种互联网搜索增强生成范式的性能。实验结果表明，我们的方法生成的内容质量有显著提升。我们的系统已成功部署在生产环境中，服务于 01.AI 的生成推理请求。

> Retrieval augmented generation has emerged as an effective method to enhance large language model performance. This approach typically relies on an internal retrieval module that uses various indexing mechanisms to manage a static pre-processed corpus. However, such a paradigm often falls short when it is necessary to integrate the most up-to-date information that has not been updated into the corpus during generative inference time. In this paper, we explore an alternative approach that leverages standard search engine APIs to dynamically integrate the latest online information (without maintaining any index for any fixed corpus), thereby improving the quality of generated content. We design a collaborative LLM-based paradigm, where we include: (i) a parser-LLM that determines if the Internet augmented generation is demanded and extracts the search keywords if so with a single inference; (ii) a mixed ranking strategy that re-ranks the retrieved HTML files to eliminate bias introduced from the search engine API; and (iii) an extractor-LLM that can accurately and efficiently extract relevant information from the fresh content in each HTML file. We conduct extensive empirical studies to evaluate the performance of this Internet search augmented generation paradigm. The experimental results demonstrate that our method generates content with significantly improved quality. Our system has been successfully deployed in a production environment to serve 01.AI's generative inference requests.

[Arxiv](https://arxiv.org/abs/2411.19478)