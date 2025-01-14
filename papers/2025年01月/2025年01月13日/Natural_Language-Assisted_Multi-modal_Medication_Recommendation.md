# 自然语言辅助的多模态药物推荐

发布时间：2025年01月13日

`LLM应用

**理由**：这篇论文主要讨论了如何利用预训练语言模型（PLMs）来提取患者和药物的领域知识，并将其应用于组合药物推荐（CMR）任务。虽然论文中提到了多模态对齐框架，但其核心是利用语言模型来处理文本信息，并将其应用于医疗领域的实际问题。因此，这篇论文应归类为LLM应用。` `药物推荐`

> Natural Language-Assisted Multi-modal Medication Recommendation

# 摘要

> # 组合药物推荐（CMR）是医疗保健中的核心任务，尤其在长期医疗护理中，为复杂健康状况患者提供精准处方。以往研究多从电子健康记录（EHRs）中提取信息以辅助药物推荐，现有方法虽考虑了药物化学结构，却忽视了描述药物功能的文本信息。此外，患者EHRs中的文本知识也未被充分利用。为此，我们提出了自然语言辅助的多模态药物推荐（NLA-MMR），这是一个多模态对齐框架，旨在联合学习患者和药物视角的知识。具体而言，NLA-MMR将CMR视为患者和药物模态的对齐问题，利用预训练语言模型（PLMs）提取患者和药物的领域知识作为基础表示。在药物模态中，我们结合化学结构和文本描述构建药物表示；在患者模态中，则基于诊断、程序和症状的文本描述生成患者表示。在三个公开数据集上的实验表明，NLA-MMR达到了新的SOTA性能，Jaccard评分平均提升4.72%。源代码已开源：https://github.com/jtan1102/NLA-MMR_CIKM_2024。

> Combinatorial medication recommendation(CMR) is a fundamental task of healthcare, which offers opportunities for clinical physicians to provide more precise prescriptions for patients with intricate health conditions, particularly in the scenarios of long-term medical care. Previous research efforts have sought to extract meaningful information from electronic health records (EHRs) to facilitate combinatorial medication recommendations. Existing learning-based approaches further consider the chemical structures of medications, but ignore the textual medication descriptions in which the functionalities are clearly described. Furthermore, the textual knowledge derived from the EHRs of patients remains largely underutilized. To address these issues, we introduce the Natural Language-Assisted Multi-modal Medication Recommendation(NLA-MMR), a multi-modal alignment framework designed to learn knowledge from the patient view and medication view jointly. Specifically, NLA-MMR formulates CMR as an alignment problem from patient and medication modalities. In this vein, we employ pretrained language models(PLMs) to extract in-domain knowledge regarding patients and medications, serving as the foundational representation for both modalities. In the medication modality, we exploit both chemical structures and textual descriptions to create medication representations. In the patient modality, we generate the patient representations based on textual descriptions of diagnosis, procedure, and symptom. Extensive experiments conducted on three publicly accessible datasets demonstrate that NLA-MMR achieves new state-of-the-art performance, with a notable average improvement of 4.72% in Jaccard score. Our source code is publicly available on https://github.com/jtan1102/NLA-MMR_CIKM_2024.

[Arxiv](https://arxiv.org/abs/2501.07166)