# 诊断竞技场：大型语言模型诊断推理能力的评估基准

发布时间：2025年05月20日

`LLM应用` `临床诊断`

> DiagnosisArena: Benchmarking Diagnostic Reasoning for Large Language Models

# 摘要

> 大型语言模型的突破性进展，使其能够执行复杂推理任务，在解决各种科学挑战，尤其是复杂临床场景中的问题方面，展现出巨大潜力。为了让这些模型在现实医疗环境中安全有效地应用，我们迫切需要系统地评估当前模型的诊断能力。鉴于现有医疗基准在评估高级诊断推理方面的局限性，我们推出了DiagnosisArena——一个全面且具挑战性的基准测试，旨在严格评估专业水平的诊断能力。DiagnosisArena包含1,113对分段患者病例和相应的诊断，涵盖28个医学专科，源自10家顶级医学期刊发表的临床案例报告。通过精心设计的构建流程，DiagnosisArena经过多轮AI系统和人类专家的筛选和审查，并进行了全面检查以防止数据泄漏。研究发现，即使是目前最先进的推理模型o3-mini、o1和DeepSeek-R1，其准确率也只有45.82%、31.09%和17.79%。这一结果凸显了当前大型语言模型在面对临床诊断推理挑战时的重大泛化瓶颈。通过DiagnosisArena，我们致力于推动AI诊断推理能力的进一步发展，为现实世界中的临床诊断挑战提供更有效的解决方案。我们提供了基准和评估工具，供进一步研究和开发使用，链接为https://github.com/SPIRAL-MED/DiagnosisArena。

> The emergence of groundbreaking large language models capable of performing complex reasoning tasks holds significant promise for addressing various scientific challenges, including those arising in complex clinical scenarios. To enable their safe and effective deployment in real-world healthcare settings, it is urgently necessary to benchmark the diagnostic capabilities of current models systematically. Given the limitations of existing medical benchmarks in evaluating advanced diagnostic reasoning, we present DiagnosisArena, a comprehensive and challenging benchmark designed to rigorously assess professional-level diagnostic competence. DiagnosisArena consists of 1,113 pairs of segmented patient cases and corresponding diagnoses, spanning 28 medical specialties, deriving from clinical case reports published in 10 top-tier medical journals. The benchmark is developed through a meticulous construction pipeline, involving multiple rounds of screening and review by both AI systems and human experts, with thorough checks conducted to prevent data leakage. Our study reveals that even the most advanced reasoning models, o3-mini, o1, and DeepSeek-R1, achieve only 45.82%, 31.09%, and 17.79% accuracy, respectively. This finding highlights a significant generalization bottleneck in current large language models when faced with clinical diagnostic reasoning challenges. Through DiagnosisArena, we aim to drive further advancements in AIs diagnostic reasoning capabilities, enabling more effective solutions for real-world clinical diagnostic challenges. We provide the benchmark and evaluation tools for further research and development https://github.com/SPIRAL-MED/DiagnosisArena.

[Arxiv](https://arxiv.org/abs/2505.14107)