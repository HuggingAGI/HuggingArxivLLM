# MedCaseReasoning：基于临床病历报告的诊断推理评估与学习方法

发布时间：2025年05月16日

`LLM应用` `诊断推理`

> MedCaseReasoning: Evaluating and learning diagnostic reasoning from clinical case reports

# 摘要

> 医生和患者越来越多地使用大型语言模型（LLMs）来诊断临床病例。然而，与数学或编程等领域不同，这些领域的正确性可以通过最终答案客观定义，而医学诊断不仅需要结果准确，还需要推理过程无误。目前，广泛使用的医学基准测试如MedQA和MMLU仅评估最终答案的准确性，忽视了临床推理过程的质量和忠实性。为了解决这一局限性，我们引入了MedCaseReasoning，这是首个开放获取的数据集，用于评估LLMs是否能与临床医生撰写的诊断推理相一致。该数据集包含14,489个诊断问答案例，每个案例都配有一系列详细推理陈述，这些陈述源自开放获取的医疗案例报告。我们在MedCaseReasoning上评估了最先进的推理型LLMs，发现它们在诊断和推理方面存在显著缺陷：例如，表现最佳的开源模型DeepSeek-R1仅实现了48%的10-shot诊断准确率，并且仅提到了64%的临床医生推理陈述（召回率）。然而，我们证明，通过在MedCaseReasoning的推理轨迹上对LLMs进行微调，可以将诊断准确率和临床推理召回率分别平均相对提高29%和41%。该开源数据集、代码和模型可在https://github.com/kevinwu23/Stanford-MedCaseReasoning获取。

> Doctors and patients alike increasingly use Large Language Models (LLMs) to diagnose clinical cases. However, unlike domains such as math or coding, where correctness can be objectively defined by the final answer, medical diagnosis requires both the outcome and the reasoning process to be accurate. Currently, widely used medical benchmarks like MedQA and MMLU assess only accuracy in the final answer, overlooking the quality and faithfulness of the clinical reasoning process. To address this limitation, we introduce MedCaseReasoning, the first open-access dataset for evaluating LLMs on their ability to align with clinician-authored diagnostic reasoning. The dataset includes 14,489 diagnostic question-and-answer cases, each paired with detailed reasoning statements derived from open-access medical case reports. We evaluate state-of-the-art reasoning LLMs on MedCaseReasoning and find significant shortcomings in their diagnoses and reasoning: for instance, the top-performing open-source model, DeepSeek-R1, achieves only 48% 10-shot diagnostic accuracy and mentions only 64% of the clinician reasoning statements (recall). However, we demonstrate that fine-tuning LLMs on the reasoning traces derived from MedCaseReasoning significantly improves diagnostic accuracy and clinical reasoning recall by an average relative gain of 29% and 41%, respectively. The open-source dataset, code, and models are available at https://github.com/kevinwu23/Stanford-MedCaseReasoning.

[Arxiv](https://arxiv.org/abs/2505.11733)