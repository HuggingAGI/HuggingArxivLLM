# 基于大型语言模型的电子健康记录中可扩展药物提取与停药识别研究

发布时间：2025年06月10日

`LLM应用` `电子健康记录`

> Scalable Medication Extraction and Discontinuation Identification from Electronic Health Records Using Large Language Models

# 摘要

> 识别电子健康记录（EHR）中的用药中断对患者安全至关重要，但常常因信息深埋于非结构化笔记中而难以实现。本研究旨在评估先进开源和专有大型语言模型（LLMs）从EHR笔记中提取用药信息并分类用药状态的能力，重点在于其在无需人工标注的用药信息提取任务上的可扩展性。我们从多个来源收集了三个EHR数据集以构建评估基准。我们评估了12个先进LLMs，并探索了多种LLM提示策略。系统性地比较了所有实验中用药提取、用药状态分类及其联合任务（先提取后分类）的性能。我们发现，LLMs在从EHR笔记中提取用药信息和用药中断分类方面表现出了令人鼓舞的性能。GPT-4o在零样本设置下所有任务中均保持了最高的平均F1分数：用药提取为94.0%，用药中断分类为78.1%，联合任务为72.7%。开源模型紧随其后，Llama-3.1-70B-Instruct在MIV-Med数据集上的用药状态分类（68.7%）以及在Re-CASI（76.2%）和MIV-Med（60.2%）数据集上的联合任务中表现最佳。专用医疗LLMs的表现普遍低于先进通用领域LLMs。少样本学习通常能提升性能，而CoT推理则表现出不一致的增益。LLMs在EHR笔记中的用药提取和用药中断识别方面展现出巨大潜力，开源模型为专有系统提供了可扩展的替代方案，而少样本学习可以进一步提升LLMs的能力。

> Identifying medication discontinuations in electronic health records (EHRs) is vital for patient safety but is often hindered by information being buried in unstructured notes. This study aims to evaluate the capabilities of advanced open-sourced and proprietary large language models (LLMs) in extracting medications and classifying their medication status from EHR notes, focusing on their scalability on medication information extraction without human annotation. We collected three EHR datasets from diverse sources to build the evaluation benchmark. We evaluated 12 advanced LLMs and explored multiple LLM prompting strategies. Performance on medication extraction, medication status classification, and their joint task (extraction then classification) was systematically compared across all experiments. We found that LLMs showed promising performance on the medication extraction and discontinuation classification from EHR notes. GPT-4o consistently achieved the highest average F1 scores in all tasks under zero-shot setting - 94.0% for medication extraction, 78.1% for discontinuation classification, and 72.7% for the joint task. Open-sourced models followed closely, Llama-3.1-70B-Instruct achieved the highest performance in medication status classification on the MIV-Med dataset (68.7%) and in the joint task on both the Re-CASI (76.2%) and MIV-Med (60.2%) datasets. Medical-specific LLMs demonstrated lower performance compared to advanced general-domain LLMs. Few-shot learning generally improved performance, while CoT reasoning showed inconsistent gains. LLMs demonstrate strong potential for medication extraction and discontinuation identification on EHR notes, with open-sourced models offering scalable alternatives to proprietary systems and few-shot can further improve LLMs' capability.

[Arxiv](https://arxiv.org/abs/2506.11137)