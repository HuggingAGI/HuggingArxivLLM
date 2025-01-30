# 微调开源大型语言模型以提升其在放射肿瘤学任务中的性能：一项探索其在放射肿瘤学中潜在临床应用的可行性研究。

发布时间：2025年01月28日

`LLM应用

理由：这篇论文探讨了通过领域知识微调大型语言模型（LLMs）来提升放射肿瘤学中的特定任务性能，如治疗方案生成、治疗方式选择和ICD-10代码预测。这属于将LLMs应用于特定领域（放射肿瘤学）的实际问题解决，因此归类为LLM应用。` `放射肿瘤学`

> Fine-Tuning Open-Source Large Language Models to Improve Their Performance on Radiation Oncology Tasks: A Feasibility Study to Investigate Their Potential Clinical Applications in Radiation Oncology

# 摘要

> 背景：放射肿瘤学临床实践涉及多个步骤，这些步骤依赖于大量文本数据的动态交互。大型语言模型在处理复杂文本信息方面表现出色，但在放射肿瘤学等特定领域的应用仍待深入探索。
目的：本研究旨在探讨通过领域知识微调LLMs是否能够提升放射肿瘤学中任务（1）治疗方案生成、任务（2）治疗方式选择（光子、质子、电子或近距离放射治疗）和任务（3）ICD-10代码预测的性能。
方法：提取了15,724例患者病例数据，筛选出具有单一诊断记录和明确治疗计划的病例进行预处理和手动注释，最终得到7,903例包含患者诊断、治疗计划、治疗方式和ICD-10代码的病例。每个病例用于构建一个由患者诊断细节和答案（分别为治疗方案、治疗方式或ICD-10代码）组成的对，用于这三个任务的监督微调。采用开源LLaMA2-7B和Mistral-7B模型，使用低秩近似方法进行微调。报告了微调模型和原始模型的准确性和ROUGE-1分数。放射肿瘤学家对任务（1）进行了临床评估，任务（2）和（3）则评估了精确度、召回率和F1分数。使用单侧Wilcoxon符号秩检验对结果进行统计分析。
结果：微调后的LLMs在所有任务中均显著优于原始LLMs（p值<=0.001）。临床评估显示，超过60%的微调LLMs生成的治疗方案在临床上是可以接受的。精确度、召回率和F1分数均表明微调LLMs的性能有所提升。

> Background: The radiation oncology clinical practice involves many steps relying on the dynamic interplay of abundant text data. Large language models have displayed remarkable capabilities in processing complex text information. But their direct applications in specific fields like radiation oncology remain underexplored.
  Purpose: This study aims to investigate whether fine-tuning LLMs with domain knowledge can improve the performance on Task (1) treatment regimen generation, Task (2) treatment modality selection (photon, proton, electron, or brachytherapy), and Task (3) ICD-10 code prediction in radiation oncology.
  Methods: Data for 15,724 patient cases were extracted. Cases where patients had a single diagnostic record, and a clearly identifiable primary treatment plan were selected for preprocessing and manual annotation to have 7,903 cases of the patient diagnosis, treatment plan, treatment modality, and ICD-10 code. Each case was used to construct a pair consisting of patient diagnostics details and an answer (treatment regimen, treatment modality, or ICD-10 code respectively) for the supervised fine-tuning of these three tasks. Open source LLaMA2-7B and Mistral-7B models were utilized for the fine-tuning with the Low-Rank Approximations method. Accuracy and ROUGE-1 score were reported for the fine-tuned models and original models. Clinical evaluation was performed on Task (1) by radiation oncologists, while precision, recall, and F-1 score were evaluated for Task (2) and (3). One-sided Wilcoxon signed-rank tests were used to statistically analyze the results.
  Results: Fine-tuned LLMs outperformed original LLMs across all tasks with p-value <= 0.001. Clinical evaluation demonstrated that over 60% of the fine-tuned LLMs-generated treatment regimens were clinically acceptable. Precision, recall, and F1-score showed improved performance of fine-tuned LLMs.

[Arxiv](https://arxiv.org/abs/2501.17286)