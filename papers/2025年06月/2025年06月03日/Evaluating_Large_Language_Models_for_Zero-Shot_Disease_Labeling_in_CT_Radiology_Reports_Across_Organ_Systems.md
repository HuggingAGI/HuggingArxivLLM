# # 摘要  
    最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年06月03日

`LLM应用` `放射学`

> Evaluating Large Language Models for Zero-Shot Disease Labeling in CT Radiology Reports Across Organ Systems

# 摘要

> # 目的
本研究旨在评估大型语言模型（LLMs）在CT放射报告疾病标注自动化中的有效性。我们比较了基于规则的算法（RBA）、RadBERT以及三种轻量级开源LLMs在胸部、腹部和盆腔（CAP）CT报告多疾病标注中的表现。

# 材料与方法
本回顾性研究分析了29,540名患者的40,833份CT报告，其中1,789份CAP报告在三个器官系统上进行了人工标注。我们使用CT-RATE数据集进行外部验证。三种开源LLMs在零样本提示下进行了测试。性能评估采用Cohen's Kappa系数和微/宏平均F1分数。

# 结果
在来自8,854名患者的12,197份杜克CAP报告中，Llama-3.1 8B和Gemma-3 27B显示出最高的一致性（κ值中位数：0.87）。在人工标注数据集上，Gemma-3 27B实现了最高的宏-F1分数（0.82），其次是Llama-3.1 8B（0.79），而RBA得分最低（0.64）。在CT-RATE数据集（仅限肺部/胸膜）中，Llama-3.1 8B表现最佳（0.91），Gemma-3 27B紧随其后（0.89）。性能差异主要源于不同的标注实践，尤其是对于肺部的肺不张。

# 结论
轻量级LLMs在CT报告标注中优于基于规则的方法，并且在零样本提示下可跨器官系统泛化。然而，仅靠二元标签无法完全捕捉报告语言的细微差别。LLMs可提供一种灵活高效、与临床判断和用户需求相契合的解决方案。


> Purpose: This study aims to evaluate the effectiveness of large language models (LLMs) in automating disease annotation of CT radiology reports. We compare a rule-based algorithm (RBA), RadBERT, and three lightweight open-weight LLMs for multi-disease labeling of chest, abdomen, and pelvis (CAP) CT reports.
  Materials and Methods: This retrospective study analyzed 40,833 CT reports from 29,540 patients, with 1,789 CAP reports manually annotated across three organ systems. External validation was conducted using the CT-RATE dataset. Three open-weight LLMs were tested with zero-shot prompting. Performance was evaluated using Cohen's Kappa and micro/macro-averaged F1 scores.
  Results: In 12,197 Duke CAP reports from 8,854 patients, Llama-3.1 8B and Gemma-3 27B showed the highest agreement ($κ$ median: 0.87). On the manually annotated set, Gemma-3 27B achieved the top macro-F1 (0.82), followed by Llama-3.1 8B (0.79), while the RBA scored lowest (0.64). On the CT-RATE dataset (lungs/pleura only), Llama-3.1 8B performed best (0.91), with Gemma-3 27B close behind (0.89). Performance differences were mainly due to differing labeling practices, especially for lung atelectasis.
  Conclusion: Lightweight LLMs outperform rule-based methods for CT report annotation and generalize across organ systems with zero-shot prompting. However, binary labels alone cannot capture the full nuance of report language. LLMs can provide a flexible, efficient solution aligned with clinical judgment and user needs.

[Arxiv](https://arxiv.org/abs/2506.03259)