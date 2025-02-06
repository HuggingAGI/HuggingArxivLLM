# 高效微调视觉语言模型，助力基于文本的人员异常搜索

发布时间：2025年02月05日

`其他

理由：这篇论文主要讨论的是基于文本的行人异常搜索（TPAS）的解决方案，涉及到文本描述与视觉数据的关联，以及在大规模图像库中匹配个体与文本描述的问题。虽然使用了文本分析技术，但核心问题并不直接涉及大型语言模型（LLM）、检索增强生成（RAG）或智能体（Agent）等主题，因此归类为“其他”更为合适。` `计算机视觉`

> Efficient Vision Language Model Fine-tuning for Text-based Person Anomaly Search

# 摘要

> 本文展示了HFUT-LMC团队在WWW 2025挑战赛中针对基于文本的行人异常搜索（TPAS）的解决方案。该挑战旨在从海量行人图像中精准识别正常或异常行为的行人。与传统视频分析不同，TPAS更注重文本描述与视觉数据间的微妙关联。其难点在于模型不仅需在大规模图像库中匹配个体与文本描述，还需在相似描述下精准区分搜索结果。为此，我们提出了相似性覆盖分析（SCA）策略，有效解决了相似文本描述带来的识别难题，提升了模型对细微差异的处理能力，从而显著提高了搜索的准确性和可靠性。我们的方案在此挑战中表现卓越。

> This paper presents the HFUT-LMC team's solution to the WWW 2025 challenge on Text-based Person Anomaly Search (TPAS). The primary objective of this challenge is to accurately identify pedestrians exhibiting either normal or abnormal behavior within a large library of pedestrian images. Unlike traditional video analysis tasks, TPAS significantly emphasizes understanding and interpreting the subtle relationships between text descriptions and visual data. The complexity of this task lies in the model's need to not only match individuals to text descriptions in massive image datasets but also accurately differentiate between search results when faced with similar descriptions. To overcome these challenges, we introduce the Similarity Coverage Analysis (SCA) strategy to address the recognition difficulty caused by similar text descriptions. This strategy effectively enhances the model's capacity to manage subtle differences, thus improving both the accuracy and reliability of the search. Our proposed solution demonstrated excellent performance in this challenge.

[Arxiv](https://arxiv.org/abs/2502.03230)