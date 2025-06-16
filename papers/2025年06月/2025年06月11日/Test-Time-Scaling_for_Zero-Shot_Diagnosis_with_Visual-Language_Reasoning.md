# 零样本诊断的测试时间缩放方法：基于视觉语言推理

发布时间：2025年06月11日

`LLM应用` `医学影像`

> Test-Time-Scaling for Zero-Shot Diagnosis with Visual-Language Reasoning

# 摘要

> 临床决策作为患者护理的基石，对患者结果有着深远影响，而大型语言模型 (LLMs) 可以进一步提升这一过程。尽管 LLMs 已展现出卓越性能，但其在医学影像视觉问答，尤其是基于推理的诊断中的应用仍鲜有探索。此外，受限于数据可用性和高标注成本，针对推理任务的监督微调在很大程度上难以实施。本研究提出了一种零样本框架，通过测试时缩放增强 LLMs 的临床推理能力，实现可靠的医学影像诊断。该框架基于一张医学影像和一个文本提示，由视觉-语言模型生成多个视觉特征描述或解释，随后输入 LLM，通过测试时缩放策略整合多个候选输出，生成可靠诊断。我们在放射学、眼科和病理学等多种医学影像模态上验证了该方法，结果表明，所提出的测试时缩放策略显著提升了诊断准确性。此外，实证分析表明，该方法在第一阶段采用无偏提示，有效提升了 LLM 生成诊断的可靠性和分类精度。

> As a cornerstone of patient care, clinical decision-making significantly influences patient outcomes and can be enhanced by large language models (LLMs). Although LLMs have demonstrated remarkable performance, their application to visual question answering in medical imaging, particularly for reasoning-based diagnosis, remains largely unexplored. Furthermore, supervised fine-tuning for reasoning tasks is largely impractical due to limited data availability and high annotation costs. In this work, we introduce a zero-shot framework for reliable medical image diagnosis that enhances the reasoning capabilities of LLMs in clinical settings through test-time scaling. Given a medical image and a textual prompt, a vision-language model processes a medical image along with a corresponding textual prompt to generate multiple descriptions or interpretations of visual features. These interpretations are then fed to an LLM, where a test-time scaling strategy consolidates multiple candidate outputs into a reliable final diagnosis. We evaluate our approach across various medical imaging modalities -- including radiology, ophthalmology, and histopathology -- and demonstrate that the proposed test-time scaling strategy enhances diagnostic accuracy for both our and baseline methods. Additionally, we provide an empirical analysis showing that the proposed approach, which allows unbiased prompting in the first stage, improves the reliability of LLM-generated diagnoses and enhances classification accuracy.

[Arxiv](https://arxiv.org/abs/2506.11166)