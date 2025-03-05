# # EchoQA：专为超声心动图报告设计的大型指令微调数据集

发布时间：2025年03月04日

`LLM应用` `心脏病学`

> EchoQA: A Large Collection of Instruction Tuning Data for Echocardiogram Reports

# 摘要

> 我们推出了一款基于重症监护医疗信息仓库数据库的超声心动图报告的新型问答（QA）数据集。该数据集专为提升心脏病学领域的问答系统而设计，包含771,244对问答，全面覆盖心脏异常及其严重程度。我们对比了开源与生物医学专用的大型语言模型（LLMs）在零样本评估中的表现，以及闭源模型在零样本和三样本评估中的表现。实验结果表明，对LLMs进行微调可显著提升其问答性能，充分证明了本数据集的价值。临床专家对表现最佳的模型进行了质量评估，以验证LLMs回答的准确性。此外，我们还进行了细致的公平性审核，评估了LLMs在不同健康社会决定因素中的偏见与性能权衡。我们的目标是为支持临床医生进行心脏鉴别诊断的LLM AI代理建立基准，从而推动该领域的发展，减轻临床医生的文书负担，使 healthcare professionals 更多地关注患者护理。

> We introduce a novel question-answering (QA) dataset using echocardiogram reports sourced from the Medical Information Mart for Intensive Care database. This dataset is specifically designed to enhance QA systems in cardiology, consisting of 771,244 QA pairs addressing a wide array of cardiac abnormalities and their severity. We compare large language models (LLMs), including open-source and biomedical-specific models for zero-shot evaluation, and closed-source models for zero-shot and three-shot evaluation. Our results show that fine-tuning LLMs improves performance across various QA metrics, validating the value of our dataset. Clinicians also qualitatively evaluate the best-performing model to assess the LLM responses for correctness. Further, we conduct fine-grained fairness audits to assess the bias-performance trade-off of LLMs across various social determinants of health. Our objective is to propel the field forward by establishing a benchmark for LLM AI agents aimed at supporting clinicians with cardiac differential diagnoses, thereby reducing the documentation burden that contributes to clinician burnout and enabling healthcare professionals to focus more on patient care.

[Arxiv](https://arxiv.org/abs/2503.02365)