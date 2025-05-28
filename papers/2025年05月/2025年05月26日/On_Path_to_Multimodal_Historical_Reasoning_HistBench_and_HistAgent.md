# 迈向多模态历史推理：HistBench与HistAgent的探索之路

发布时间：2025年05月26日

`Agent` `历史学` `多模态分析`

> On Path to Multimodal Historical Reasoning: HistBench and HistAgent

# 摘要

> 大型语言模型（LLMs）的最新进展在各个领域取得了显著进步，但其在人文领域，尤其是历史学方面的潜力仍待探索。历史推理对AI提出了独特挑战，涉及多模态资料解读、时间推理和跨语言分析。尽管通用型智能体在现有基准测试中表现优异，但它们缺乏处理历史材料和问题所需的专业知识。为填补这一空白，我们推出了HistBench——一个包含414个高质量问题的新基准测试，由40多位专家共同编写，旨在评估AI的历史推理能力。这些问题涵盖广泛的历史难题，从基于一手资料的事实检索，到对手稿和图像的解释性分析，再到涉及考古学、语言学或文化历史的跨学科挑战。此外，该基准测试的数据集涵盖了29种古今语言，跨越了不同的历史时期和世界地区。我们发现LLMs和其他智能体在HistBench上的表现不尽如人意，因此进一步推出了HistAgent——一个专为历史推理设计的智能体，配备了一系列精心设计的工具，包括OCR、翻译、档案搜索和图像理解功能。基于GPT-4o的HistAgent在HistBench上达到了27.54%的pass@1准确率和36.47%的pass@2准确率，显著超越了配备在线搜索功能的LLMs和通用型智能体，包括GPT-4o（18.60%）、DeepSeek-R1（14.49%）以及Open Deep Research-smolagents（20.29% pass@1和25.12% pass@2）。这些结果凸显了现有LLMs和通用型智能体的局限性，同时也证明了HistAgent在历史推理方面的优势。

> Recent advances in large language models (LLMs) have led to remarkable progress across domains, yet their capabilities in the humanities, particularly history, remain underexplored. Historical reasoning poses unique challenges for AI, involving multimodal source interpretation, temporal inference, and cross-linguistic analysis. While general-purpose agents perform well on many existing benchmarks, they lack the domain-specific expertise required to engage with historical materials and questions. To address this gap, we introduce HistBench, a new benchmark of 414 high-quality questions designed to evaluate AI's capacity for historical reasoning and authored by more than 40 expert contributors. The tasks span a wide range of historical problems-from factual retrieval based on primary sources to interpretive analysis of manuscripts and images, to interdisciplinary challenges involving archaeology, linguistics, or cultural history. Furthermore, the benchmark dataset spans 29 ancient and modern languages and covers a wide range of historical periods and world regions. Finding the poor performance of LLMs and other agents on HistBench, we further present HistAgent, a history-specific agent equipped with carefully designed tools for OCR, translation, archival search, and image understanding in History. On HistBench, HistAgent based on GPT-4o achieves an accuracy of 27.54% pass@1 and 36.47% pass@2, significantly outperforming LLMs with online search and generalist agents, including GPT-4o (18.60%), DeepSeek-R1(14.49%) and Open Deep Research-smolagents(20.29% pass@1 and 25.12% pass@2). These results highlight the limitations of existing LLMs and generalist agents and demonstrate the advantages of HistAgent for historical reasoning.

[Arxiv](https://arxiv.org/abs/2505.20246)