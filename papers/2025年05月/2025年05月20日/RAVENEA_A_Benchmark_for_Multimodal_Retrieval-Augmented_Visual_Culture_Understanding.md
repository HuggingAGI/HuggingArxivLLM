# RAVENEA：多模态检索增强视觉文化理解的基准测试

发布时间：2025年05月20日

`RAG` `人工智能` `视觉文化`

> RAVENEA: A Benchmark for Multimodal Retrieval-Augmented Visual Culture Understanding

# 摘要

> 视觉语言模型（VLMs）正逐步融入日常生活，准确理解视觉文化的重要性日益凸显。然而，现有模型在捕捉文化细微差别方面仍显不足。尽管检索增强生成（RAG）在文本环境中已被证实能有效提升文化理解，但其在多模态场景中的应用尚未得到充分探索。为解决这一问题，我们推出了RAVENEA，一个专注于通过检索提升视觉文化理解的新基准，涵盖以文化为中心的视觉问答（cVQA）和文化导向的图像描述（cIC）两大任务。RAVENEA扩展了现有数据集，整合了由人工标注员精选并排序的超过10,000份维基百科文档。我们利用RAVENEA对七种多模态检索器进行训练与评估，并分析了检索增强输入对十四种先进VLMs的下游影响。实验结果表明，轻量级VLMs在文化感知检索的增强下，性能显著提升（cVQA中提升3.2%绝对值，cIC中提升6.2%绝对值）。这一发现凸显了检索增强方法及文化包容性基准在多模态理解中的重要价值。

> As vision-language models (VLMs) become increasingly integrated into daily life, the need for accurate visual culture understanding is becoming critical. Yet, these models frequently fall short in interpreting cultural nuances effectively. Prior work has demonstrated the effectiveness of retrieval-augmented generation (RAG) in enhancing cultural understanding in text-only settings, while its application in multimodal scenarios remains underexplored. To bridge this gap, we introduce RAVENEA (Retrieval-Augmented Visual culturE uNdErstAnding), a new benchmark designed to advance visual culture understanding through retrieval, focusing on two tasks: culture-focused visual question answering (cVQA) and culture-informed image captioning (cIC). RAVENEA extends existing datasets by integrating over 10,000 Wikipedia documents curated and ranked by human annotators. With RAVENEA, we train and evaluate seven multimodal retrievers for each image query, and measure the downstream impact of retrieval-augmented inputs across fourteen state-of-the-art VLMs. Our results show that lightweight VLMs, when augmented with culture-aware retrieval, outperform their non-augmented counterparts (by at least 3.2% absolute on cVQA and 6.2% absolute on cIC). This highlights the value of retrieval-augmented methods and culturally inclusive benchmarks for multimodal understanding.

[Arxiv](https://arxiv.org/abs/2505.14462)