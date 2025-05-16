# 神经对心脏意味着什么？临床专科数据在医学大语言模型中的作用探究

发布时间：2025年05月15日

`LLM应用` `医疗问答`

> What Does Neuro Mean to Cardio? Investigating the Role of Clinical Specialty Data in Medical LLMs

# 摘要

> 本文介绍了 S-MedQA，一个用于评估大型语言模型在精细临床专科领域表现的英文医疗问答（QA）数据集。我们通过 S-MedQA 探讨在医疗 QA 这一知识密集型场景中，与知识注入相关的流行假设的适用性，并得出以下结论：1) 专攻某一专科领域的训练并不一定能够使模型在该专科领域取得最佳表现；2) 无论专注于哪个专科领域，与临床相关的术语在所有专科中的概率都会持续上升。因此，我们认为性能提升主要源于领域转换（例如从通用领域转向医疗领域），而非知识注入，建议重新思考微调数据在医学领域中的作用。我们已将 S-MedQA 数据集及所有实验代码开放给研究界。

> In this paper, we introduce S-MedQA, an English medical question-answering (QA) dataset for benchmarking large language models in fine-grained clinical specialties. We use S-MedQA to check the applicability of a popular hypothesis related to knowledge injection in the knowledge-intense scenario of medical QA, and show that: 1) training on data from a speciality does not necessarily lead to best performance on that specialty and 2) regardless of the specialty fine-tuned on, token probabilities of clinically relevant terms for all specialties increase consistently. Thus, we believe improvement gains come mostly from domain shifting (e.g., general to medical) rather than knowledge injection and suggest rethinking the role of fine-tuning data in the medical domain. We release S-MedQA and all code needed to reproduce all our experiments to the research community.

[Arxiv](https://arxiv.org/abs/2505.10113)