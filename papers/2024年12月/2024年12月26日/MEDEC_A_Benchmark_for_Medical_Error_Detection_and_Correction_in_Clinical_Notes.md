# MEDEC: 临床笔记医疗错误检测与纠正基准

发布时间：2024年12月26日

`LLM应用

理由：这篇论文主要讨论了大型语言模型（LLMs）在医学领域的应用，特别是其在医学错误检测与纠正任务中的表现。论文介绍了MEDEC基准，并评估了多个LLMs在该基准上的表现。虽然涉及医学知识和推理能力，但核心内容仍然是LLMs在特定应用场景（医学错误检测与纠正）中的表现和评估，因此应归类为“LLM应用”。` `临床笔记`

> MEDEC: A Benchmark for Medical Error Detection and Correction in Clinical Notes

# 摘要

> # 摘要
多项研究显示，大型语言模型（LLMs）能够准确回答医学问题，甚至在某些医学考试中超越人类平均成绩。然而，目前尚无研究评估LLMs验证现有或生成医学文本的正确性和一致性的能力。本文介绍了MEDEC（https://github.com/abachaa/MEDEC），这是首个公开的临床笔记医学错误检测与纠正基准，涵盖诊断、管理、治疗、药物治疗和病原体五类错误。MEDEC包含3,848个临床文本，其中包括来自三个美国医院系统的488个临床笔记，这些笔记此前未被任何LLM接触过。该数据集已用于MEDIQA-CORR共享任务，评估了十七个参与系统[Ben Abacha等人，2024]。本文详细描述了数据创建方法，并评估了最新LLMs（如o1-preview、GPT-4、Claude 3.5 Sonnet和Gemini 2.0 Flash）在需要医学知识和推理能力的医学错误检测与纠正任务中的表现。我们还进行了一项比较研究，两位医学医生在MEDEC测试集上执行了相同任务。结果表明，MEDEC是一个极具挑战性的基准，能够有效评估模型验证现有或生成笔记及纠正医学错误的能力。尽管最新LLMs在错误检测与纠正方面表现优异，但仍不及医学医生。我们探讨了这一差距的潜在原因、实验中的发现、当前评估指标的局限性，并提出了未来研究的可能方向。

> Several studies showed that Large Language Models (LLMs) can answer medical questions correctly, even outperforming the average human score in some medical exams. However, to our knowledge, no study has been conducted to assess the ability of language models to validate existing or generated medical text for correctness and consistency. In this paper, we introduce MEDEC (https://github.com/abachaa/MEDEC), the first publicly available benchmark for medical error detection and correction in clinical notes, covering five types of errors (Diagnosis, Management, Treatment, Pharmacotherapy, and Causal Organism). MEDEC consists of 3,848 clinical texts, including 488 clinical notes from three US hospital systems that were not previously seen by any LLM. The dataset has been used for the MEDIQA-CORR shared task to evaluate seventeen participating systems [Ben Abacha et al., 2024]. In this paper, we describe the data creation methods and we evaluate recent LLMs (e.g., o1-preview, GPT-4, Claude 3.5 Sonnet, and Gemini 2.0 Flash) for the tasks of detecting and correcting medical errors requiring both medical knowledge and reasoning capabilities. We also conducted a comparative study where two medical doctors performed the same task on the MEDEC test set. The results showed that MEDEC is a sufficiently challenging benchmark to assess the ability of models to validate existing or generated notes and to correct medical errors. We also found that although recent LLMs have a good performance in error detection and correction, they are still outperformed by medical doctors in these tasks. We discuss the potential factors behind this gap, the insights from our experiments, the limitations of current evaluation metrics, and share potential pointers for future research.

[Arxiv](https://arxiv.org/abs/2412.19260)