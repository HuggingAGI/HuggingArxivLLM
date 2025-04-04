# CrossCheckGPT：多模态基础模型幻觉评估的通用排名系统

发布时间：2024年05月22日

`RAG

理由：这篇论文介绍了一种名为“CrossCheckGPT”的新方法，用于评估多模态基础模型中的幻觉问题。该方法通过跨系统的一致性来评估幻觉，不依赖于黄金标准参考或标签，适用于多种模型和任务。这种方法特别关注于多模态模型输出的信息一致性，通过特定的度量方法（CrossCheck-explicit和CrossCheck-implicit）来评估。因此，它属于RAG（Retrieval-Augmented Generation）类别，因为它涉及通过检索增强生成过程的质量和准确性。` `多模态` `幻觉评估`

> CrossCheckGPT: Universal Hallucination Ranking for Multimodal Foundation Models

# 摘要

> 多模态基础模型易产生幻觉，其输出往往与输入相悖或缺乏事实依据。由于架构、训练数据及指令调整技术的多样性，系统对幻觉的敏感度差异显著。为此，针对图像标注、问答、摘要及传记生成等特定任务，已开发出幻觉排名方法。但这些方法多依赖于与黄金标准参考或标签的对比，限制了新领域幻觉评估的发展。本研究提出“CrossCheckGPT”，一种无需参考的多模态基础模型幻觉评估通用方法。其核心理念在于，不同独立系统生成相同幻觉内容的可能性极低，因此跨系统的一致性可提供准确且有意义的幻觉评分。CrossCheckGPT适用于任何模型或任务，只要能通过适当距离度量评估输出间的信息一致性。针对生成文本的多模态大型语言模型，我们研究了两种信息一致性度量：CrossCheck-explicit和CrossCheck-implicit。我们的方法在文本、图像及视听领域展示了幻觉排名的广泛适用性。此外，我们创建了首个视听幻觉基准“AVHalluBench”，并验证了CrossCheckGPT的有效性，与人类判断的相关性分别高达98%和89%。

> Multimodal foundation models are prone to hallucination, generating outputs that either contradict the input or are not grounded by factual information. Given the diversity in architectures, training data and instruction tuning techniques, there can be large variations in systems' susceptibility to hallucinations. To assess system hallucination robustness, hallucination ranking approaches have been developed for specific tasks such as image captioning, question answering, summarization, or biography generation. However, these approaches typically compare model outputs to gold-standard references or labels, limiting hallucination benchmarking for new domains. This work proposes "CrossCheckGPT", a reference-free universal hallucination ranking for multimodal foundation models. The core idea of CrossCheckGPT is that the same hallucinated content is unlikely to be generated by different independent systems, hence cross-system consistency can provide meaningful and accurate hallucination assessment scores. CrossCheckGPT can be applied to any model or task, provided that the information consistency between outputs can be measured through an appropriate distance metric. Focusing on multimodal large language models that generate text, we explore two information consistency measures: CrossCheck-explicit and CrossCheck-implicit. We showcase the applicability of our method for hallucination ranking across various modalities, namely the text, image, and audio-visual domains. Further, we propose the first audio-visual hallucination benchmark, "AVHalluBench", and illustrate the effectiveness of CrossCheckGPT, achieving correlations of 98% and 89% with human judgements on MHaluBench and AVHalluBench, respectively.

[Arxiv](https://arxiv.org/abs/2405.13684)