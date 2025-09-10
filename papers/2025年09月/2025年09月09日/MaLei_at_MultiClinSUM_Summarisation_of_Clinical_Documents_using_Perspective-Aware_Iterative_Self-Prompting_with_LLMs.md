# MaLei在MultiClinSUM：基于视角感知迭代式自我提示的大型语言模型临床文档摘要

发布时间：2025年09月09日

`LLM应用` `医疗健康`

> MaLei at MultiClinSUM: Summarisation of Clinical Documents using Perspective-Aware Iterative Self-Prompting with LLMs

# 摘要

> 患者与临床医生的有效沟通是共同决策的关键。但临床报告常因冗长晦涩、术语密集，导致专家难以快速定位核心信息。本文详述了我们在MultiClinSUM共享任务中提出的临床病例总结方案：通过在大型语言模型（LLMs）上部署迭代自提示（Iterative Self-Prompting）技术，让模型自主生成任务专属提示，并结合示例少样本学习持续优化。同时，我们采用ROUGE与BERT-score作为词汇及嵌入空间指标，按轮次引导模型微调。基于GPT-4和GPT-4o的视角感知ISP（PA-ISP）方案，在3396份多专科开放期刊临床病例报告的官方测评中，取得ROUGE分数（46.53、24.68、30.77）与BERT分数（87.84、83.25、85.46）（分指P、R、F1值）。高BERT分数印证了模型输出与参考摘要的语义等效性——即便ROUGE分数显示词汇重叠度较低，仍能精准传递核心含义。该研究为视角感知ISP（PA-ISP）在临床报告总结中的落地提供了实践参考，有望助力医患沟通提质增效。

> Efficient communication between patients and clinicians plays an important role in shared decision-making. However, clinical reports are often lengthy and filled with clinical jargon, making it difficult for domain experts to identify important aspects in the document efficiently. This paper presents the methodology we applied in the MultiClinSUM shared task for summarising clinical case documents. We used an Iterative Self-Prompting technique on large language models (LLMs) by asking LLMs to generate task-specific prompts and refine them via example-based few-shot learning. Furthermore, we used lexical and embedding space metrics, ROUGE and BERT-score, to guide the model fine-tuning with epochs. Our submission using perspective-aware ISP on GPT-4 and GPT-4o achieved ROUGE scores (46.53, 24.68, 30.77) and BERTscores (87.84, 83.25, 85.46) for (P, R, F1) from the official evaluation on 3,396 clinical case reports from various specialties extracted from open journals. The high BERTscore indicates that the model produced semantically equivalent output summaries compared to the references, even though the overlap at the exact lexicon level is lower, as reflected in the lower ROUGE scores. This work sheds some light on how perspective-aware ISP (PA-ISP) can be deployed for clinical report summarisation and support better communication between patients and clinicians.

[Arxiv](https://arxiv.org/abs/2509.07622)