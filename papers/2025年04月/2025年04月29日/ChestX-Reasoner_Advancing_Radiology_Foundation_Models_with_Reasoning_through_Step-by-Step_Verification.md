# ChestX-Reasoner：通过逐步验证推理提升放射学基础模型

发布时间：2025年04月29日

`LLM应用

理由：这篇论文主要探讨了将多模态大语言模型应用于医学诊断领域，特别是放射科诊断中的结构化推理过程。研究中开发了ChestX-Reasoner模型，并构建了相关的数据集和评估基准，以提升模型在医学推理中的性能。这些工作属于将LLM应用于特定领域，因此归类为LLM应用。` `放射科`

> ChestX-Reasoner: Advancing Radiology Foundation Models with Reasoning through Step-by-Step Verification

# 摘要

> 增强推理的大型语言模型（LLMs）和多模态大语言模型（MLLMs）在复杂任务中的性能有了显著提升，但医学AI模型常忽视临床实践中的结构化推理过程。本文介绍的ChestX-Reasoner是一款专为放射科诊断设计的多模态大语言模型，通过直接从临床报告中挖掘流程监督，模拟放射科医生的逐步推理。我们从常规放射科报告中提取并精炼推理链，构建了大型数据集。两阶段训练框架结合监督微调和强化学习，使模型推理更贴近临床标准。我们推出了RadRBench-CXR，一个包含59,000个视觉问答样本和301,000个临床验证推理步骤的基准测试，并提出了RadRScore，用于评估推理的事实性、完整性和有效性。ChestX-Reasoner在诊断准确性和推理能力上均超越现有医学和通用领域多模态大语言模型，推理能力较最佳医学MLLM、通用MLLM及其基础模型分别提升16%、5.9%和18%，诊断结果准确性提升3.3%、24%和27%。所有资源开源，助力医学推理MLLMs研究。

> Recent advances in reasoning-enhanced large language models (LLMs) and multimodal LLMs (MLLMs) have significantly improved performance in complex tasks, yet medical AI models often overlook the structured reasoning processes inherent in clinical practice. In this work, we present ChestX-Reasoner, a radiology diagnosis MLLM designed to leverage process supervision mined directly from clinical reports, reflecting the step-by-step reasoning followed by radiologists. We construct a large dataset by extracting and refining reasoning chains from routine radiology reports. Our two-stage training framework combines supervised fine-tuning and reinforcement learning guided by process rewards to better align model reasoning with clinical standards. We introduce RadRBench-CXR, a comprehensive benchmark featuring 59K visual question answering samples with 301K clinically validated reasoning steps, and propose RadRScore, a metric evaluating reasoning factuality, completeness, and effectiveness. ChestX-Reasoner outperforms existing medical and general-domain MLLMs in both diagnostic accuracy and reasoning ability, achieving 16%, 5.9%, and 18% improvements in reasoning ability compared to the best medical MLLM, the best general MLLM, and its base model, respectively, as well as 3.3%, 24%, and 27% improvements in outcome accuracy. All resources are open-sourced to facilitate further research in medical reasoning MLLMs.

[Arxiv](https://arxiv.org/abs/2504.20930)