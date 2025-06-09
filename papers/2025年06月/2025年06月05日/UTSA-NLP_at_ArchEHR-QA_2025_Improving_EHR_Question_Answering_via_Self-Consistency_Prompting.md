# UTSA-NLP 在 ArchEHR-QA 2025 中的表现：通过自洽提示提升电子健康记录问答能力

发布时间：2025年06月05日

`LLM应用` `问答系统`

> UTSA-NLP at ArchEHR-QA 2025: Improving EHR Question Answering via Self-Consistency Prompting

# 摘要

> 我们在ArchEHR-QA共享任务中介绍了一套基于电子健康记录 (EHR) 的临床问答系统。该系统采用大型语言模型分两步走：首先精准定位 EHR 中与临床问题相关的句段；然后基于这些句段生成简明且有文献支持的回答。我们通过少量样本提示、自我一致性和阈值筛选等技术优化了句子筛选步骤，以确保关键信息的提取。实验对比发现，较小的 8B 模型在信息识别方面表现优于较大的 70B 模型。研究结果表明，精准的句子选择是生成高质量回答的关键，而结合自我一致性和阈值筛选能够显著提升选择决策的可靠性。

> We describe our system for the ArchEHR-QA Shared Task on answering clinical questions using electronic health records (EHRs). Our approach uses large language models in two steps: first, to find sentences in the EHR relevant to a clinician's question, and second, to generate a short, citation-supported response based on those sentences. We use few-shot prompting, self-consistency, and thresholding to improve the sentence classification step to decide which sentences are essential. We compare several models and find that a smaller 8B model performs better than a larger 70B model for identifying relevant information. Our results show that accurate sentence selection is critical for generating high-quality responses and that self-consistency with thresholding helps make these decisions more reliable.

[Arxiv](https://arxiv.org/abs/2506.05589)