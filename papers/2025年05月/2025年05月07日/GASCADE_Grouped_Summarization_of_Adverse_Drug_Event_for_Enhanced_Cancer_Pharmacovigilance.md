# # GASCADE：药物不良事件的分组汇总，助力加强癌症药物警戒

发布时间：2025年05月07日

`LLM应用

理由：这篇论文主要探讨了大型语言模型（LLM）在药物警戒中的应用，特别是针对癌症治疗中的不良药物事件总结。论文提出了GASCADE框架，结合了LLM的信息提取能力和T5模型的摘要功能，并应用了直接偏好优化等技术，属于LLM的实际应用。` `药物警戒`

> GASCADE: Grouped Summarization of Adverse Drug Event for Enhanced Cancer Pharmacovigilance

# 摘要

> 在癌症治疗领域，总结患者报告的不良药物事件（ADEs）对加强药物警戒和改善药物相关决策至关重要。然而，尽管药物警戒数据日益复杂，现有研究多集中于一般性疾病，而针对癌症的研究仍显不足。本研究聚焦于癌症治疗中使用相同药物的患者群体，提出了不良药物事件的分组总结任务。

为解决癌症药物警戒资源有限的难题，我们推出了多标签癌症药物不良反应和总结（MCADRS）数据集。该数据集不仅包含患者对药物疗效及不良反应的关切描述，还涵盖了药物名称、不良事件、严重程度等关键信息的标签，以及针对每种药物的ADE摘要。

同时，我们创新性地提出了癌症不良药物事件的分组和摘要式总结（GASCADE）框架。这一框架巧妙结合大型语言模型的信息提取能力与编码器-解码器T5模型的摘要优势，开创性地将直接偏好优化等先进对齐技术应用于摘要任务。通过大量实验验证，GASCADE在多项指标上均表现出色，其性能得到了自动化评估和人工评估的双重认可。

本研究不仅为药物相关决策提供了有力支持，更深入洞察了患者关切，为个性化和响应性癌症治疗的未来发展奠定了基础。研究使用的代码和数据集现已公开，以促进更广泛的研究与应用。

> In the realm of cancer treatment, summarizing adverse drug events (ADEs) reported by patients using prescribed drugs is crucial for enhancing pharmacovigilance practices and improving drug-related decision-making. While the volume and complexity of pharmacovigilance data have increased, existing research in this field has predominantly focused on general diseases rather than specifically addressing cancer. This work introduces the task of grouped summarization of adverse drug events reported by multiple patients using the same drug for cancer treatment. To address the challenge of limited resources in cancer pharmacovigilance, we present the MultiLabeled Cancer Adverse Drug Reaction and Summarization (MCADRS) dataset. This dataset includes pharmacovigilance posts detailing patient concerns regarding drug efficacy and adverse effects, along with extracted labels for drug names, adverse drug events, severity, and adversity of reactions, as well as summaries of ADEs for each drug. Additionally, we propose the Grouping and Abstractive Summarization of Cancer Adverse Drug events (GASCADE) framework, a novel pipeline that combines the information extraction capabilities of Large Language Models (LLMs) with the summarization power of the encoder-decoder T5 model. Our work is the first to apply alignment techniques, including advanced algorithms like Direct Preference Optimization, to encoder-decoder models using synthetic datasets for summarization tasks. Through extensive experiments, we demonstrate the superior performance of GASCADE across various metrics, validated through both automated assessments and human evaluations. This multitasking approach enhances drug-related decision-making and fosters a deeper understanding of patient concerns, paving the way for advancements in personalized and responsive cancer care. The code and dataset used in this work are publicly available.

[Arxiv](https://arxiv.org/abs/2505.04284)