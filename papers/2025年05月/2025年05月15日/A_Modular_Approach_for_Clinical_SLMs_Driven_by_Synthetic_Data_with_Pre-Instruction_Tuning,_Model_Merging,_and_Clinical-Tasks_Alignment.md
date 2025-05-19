# 一种由合成数据驱动的临床SLMs模块化方法，结合预指令微调、模型合并与临床任务对齐

发布时间：2025年05月15日

`LLM应用

理由：这篇论文主要探讨了如何将大型语言模型（如GPT-4）应用于临床环境，解决其计算成本高和延迟大的问题。研究中开发了一种新的框架，将小语言模型（SLMs）转化为高性能临床模型，并通过预指令调优、模型合并和临床任务对齐等方法，提升其在医学任务中的表现。这些内容属于LLM的应用层面，因此归类为LLM应用。` `NLP`

> A Modular Approach for Clinical SLMs Driven by Synthetic Data with Pre-Instruction Tuning, Model Merging, and Clinical-Tasks Alignment

# 摘要

> GPT-4等大型语言模型因计算成本高和延迟大，在临床环境中难以部署。小语言模型（SLMs）虽成本低，但性能有限，需进行生物医学领域的适配，这仍是难题。此外，临床数据的获取和敏感性问题也构成障碍。为突破这些限制，我们开发了一种全新的框架，将SLMs转化为高性能临床模型。我们推出了MediPhi系列，这是一组38亿参数的SLMs，通过创新方法打造：在医学和临床语料库（如PMC、医学指南、MedWiki等）上对专家模型进行预指令调优，随后进行模型合并和临床任务对齐。为覆盖更多临床任务，我们将CLUE基准扩展为CLUE+，使其规模翻倍。我们的专家模型在无需特定任务微调的情况下，在CLUE+基准上表现优异：医学实体识别提升64.3%，放射报告生成提升49.5%，ICD-10编码提升44%（较GPT-4-0125提升14%）。通过模型合并技术，我们将各专家模型整合为统一的MediPhi，保持了其在各项基准上的优势。此外，我们打造了MediFlow数据集，包含14个医学NLP任务、98种细粒度文档类型，并支持JSON格式，总计250万条高质量指令。通过对MediPhi进行监督微调和直接偏好优化，我们进一步提升了其性能，平均提升达18.9%。


> High computation costs and latency of large language models such as GPT-4 have limited their deployment in clinical settings. Small language models (SLMs) offer a cost-effective alternative, but their limited capacity requires biomedical domain adaptation, which remains challenging. An additional bottleneck is the unavailability and high sensitivity of clinical data. To address these challenges, we propose a novel framework for adapting SLMs into high-performing clinical models. We introduce the MediPhi collection of 3.8B-parameter SLMs developed with our novel framework: pre-instruction tuning of experts on relevant medical and clinical corpora (PMC, Medical Guideline, MedWiki, etc.), model merging, and clinical-tasks alignment. To cover most clinical tasks, we extended the CLUE benchmark to CLUE+, doubling its size. Our expert models deliver relative improvements on this benchmark over the base model without any task-specific fine-tuning: 64.3% on medical entities, 49.5% on radiology reports, and 44% on ICD-10 coding (outperforming GPT-4-0125 by 14%). We unify the expert models into MediPhi via model merging, preserving gains across benchmarks. Furthermore, we built the MediFlow collection, a synthetic dataset of 2.5 million high-quality instructions on 14 medical NLP tasks, 98 fine-grained document types, and JSON format support. Alignment of MediPhi using supervised fine-tuning and direct preference optimization achieves further gains of 18.9% on average.

[Arxiv](https://arxiv.org/abs/2505.10717)