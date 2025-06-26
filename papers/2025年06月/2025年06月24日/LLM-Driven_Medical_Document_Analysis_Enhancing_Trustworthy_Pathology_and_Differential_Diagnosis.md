# LLM驱动的医学文档分析：提升病理学与鉴别诊断的可信度

发布时间：2025年06月24日

`LLM应用` `医疗信息系统`

> LLM-Driven Medical Document Analysis: Enhancing Trustworthy Pathology and Differential Diagnosis

# 摘要

> 医学文档分析在从非结构化的医疗记录中提取关键临床见解方面扮演着关键角色，尤其在支持如鉴别诊断等关键医疗任务中发挥着重要作用。面对症状重叠的复杂情况，准确判断最可能的诊断不仅需要精准的评估，更需要深厚的医学专业知识。尽管大型语言模型（LLMs）在医学文档分析领域取得了显著进展，但敏感患者数据的隐私问题限制了在线LLMs服务在临床环境中的广泛应用。

为了解决这一难题，我们提出了一种值得信赖的医学文档分析平台。该平台基于LLaMA-v3模型，通过低秩适应（LoRA）技术进行优化，特别针对鉴别诊断任务进行了深入调整。我们的研究采用了目前最大的鉴别诊断基准数据集DDXPlus，并在病理预测和变长鉴别诊断方面展现了优于现有方法的性能。此外，我们开发了一个基于网络的平台，用户可以上传自己的非结构化医疗文档，并获得准确且可解释的诊断结果。

通过整合先进的可解释性技术，该系统不仅确保了预测结果的透明性和可靠性，更显著增强了用户对诊断结果的信任和信心。经过全面评估，我们的方法在预测准确性方面超越了当前最先进的模型，同时在临床应用中展现了极高的实用价值。这项研究不仅满足了医疗领域对可靠、可解释且保护隐私的人工智能解决方案的迫切需求，更代表了智能医学文档分析技术在现实世界医疗应用中的重要突破。相关代码可在\href{https://github.com/leitro/Differential-Diagnosis-LoRA}{https://github.com/leitro/Differential-Diagnosis-LoRA}获取。

> Medical document analysis plays a crucial role in extracting essential clinical insights from unstructured healthcare records, supporting critical tasks such as differential diagnosis. Determining the most probable condition among overlapping symptoms requires precise evaluation and deep medical expertise. While recent advancements in large language models (LLMs) have significantly enhanced performance in medical document analysis, privacy concerns related to sensitive patient data limit the use of online LLMs services in clinical settings. To address these challenges, we propose a trustworthy medical document analysis platform that fine-tunes a LLaMA-v3 using low-rank adaptation, specifically optimized for differential diagnosis tasks. Our approach utilizes DDXPlus, the largest benchmark dataset for differential diagnosis, and demonstrates superior performance in pathology prediction and variable-length differential diagnosis compared to existing methods. The developed web-based platform allows users to submit their own unstructured medical documents and receive accurate, explainable diagnostic results. By incorporating advanced explainability techniques, the system ensures transparent and reliable predictions, fostering user trust and confidence. Extensive evaluations confirm that the proposed method surpasses current state-of-the-art models in predictive accuracy while offering practical utility in clinical settings. This work addresses the urgent need for reliable, explainable, and privacy-preserving artificial intelligence solutions, representing a significant advancement in intelligent medical document analysis for real-world healthcare applications. The code can be found at \href{https://github.com/leitro/Differential-Diagnosis-LoRA}{https://github.com/leitro/Differential-Diagnosis-LoRA}.

[Arxiv](https://arxiv.org/abs/2506.19702)