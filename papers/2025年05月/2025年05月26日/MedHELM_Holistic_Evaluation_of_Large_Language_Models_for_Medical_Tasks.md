# # MedHELM：全面评估大型语言模型在医疗任务中的表现

发布时间：2025年05月26日

`LLM应用` `评估框架`

> MedHELM: Holistic Evaluation of Large Language Models for Medical Tasks

# 摘要

> 尽管大型语言模型 (LLMs) 在医学执照考试中表现近乎完美，但这些评估未能充分反映真实临床实践中的复杂性和多样性。我们推出 MedHELM，一个可扩展的评估框架，用于评估 LLM 在医学任务中的性能，并提出三大关键贡献。首先，我们与29位临床医生合作，开发了一个涵盖5个类别、22个子类别和121个任务的分类法。其次，构建了一个包含35个基准测试（17个现有，18个新制定）的全面基准套件，全面覆盖分类法中的所有类别和子类别。第三，通过改进的评估方法（使用 LLM-jury）对 LLM 进行了系统性比较，并进行了成本与性能分析。使用35个基准测试的9个前沿 LLM 的评估显示了显著的性能差异。高级推理模型（DeepSeek R1: 66% 胜率；o3-mini: 64% 胜率）表现出色，尽管Claude 3.5 Sonnet在估算计算成本降低40%的情况下也取得了相当的结果。在标准化准确性量表（0-1）上，大多数模型在临床笔记生成（0.73-0.85）和患者沟通与教育（0.78-0.83）方面表现强劲，在医学研究支持（0.65-0.75）方面表现适中，在临床决策支持（0.56-0.72）和行政与工作流（0.53-0.63）方面表现较低。我们的 LLM-jury 评估方法与临床医生的评分达成良好一致（ICC = 0.47），超过了临床医生之间的平均一致性和包括 ROUGE-L（0.36）和 BERTScore-F1（0.44）在内的自动化基线。Claude 3.5 Sonnet以更低的估算成本实现了与顶级模型相当的性能。这些发现突显了真实世界、任务特定评估在 LLM 医疗应用中的重要性，并提供了一个开源框架以实现这一点。

> While large language models (LLMs) achieve near-perfect scores on medical licensing exams, these evaluations inadequately reflect the complexity and diversity of real-world clinical practice. We introduce MedHELM, an extensible evaluation framework for assessing LLM performance for medical tasks with three key contributions. First, a clinician-validated taxonomy spanning 5 categories, 22 subcategories, and 121 tasks developed with 29 clinicians. Second, a comprehensive benchmark suite comprising 35 benchmarks (17 existing, 18 newly formulated) providing complete coverage of all categories and subcategories in the taxonomy. Third, a systematic comparison of LLMs with improved evaluation methods (using an LLM-jury) and a cost-performance analysis. Evaluation of 9 frontier LLMs, using the 35 benchmarks, revealed significant performance variation. Advanced reasoning models (DeepSeek R1: 66% win-rate; o3-mini: 64% win-rate) demonstrated superior performance, though Claude 3.5 Sonnet achieved comparable results at 40% lower estimated computational cost. On a normalized accuracy scale (0-1), most models performed strongly in Clinical Note Generation (0.73-0.85) and Patient Communication & Education (0.78-0.83), moderately in Medical Research Assistance (0.65-0.75), and generally lower in Clinical Decision Support (0.56-0.72) and Administration & Workflow (0.53-0.63). Our LLM-jury evaluation method achieved good agreement with clinician ratings (ICC = 0.47), surpassing both average clinician-clinician agreement (ICC = 0.43) and automated baselines including ROUGE-L (0.36) and BERTScore-F1 (0.44). Claude 3.5 Sonnet achieved comparable performance to top models at lower estimated cost. These findings highlight the importance of real-world, task-specific evaluation for medical use of LLMs and provides an open source framework to enable this.

[Arxiv](https://arxiv.org/abs/2505.23802)