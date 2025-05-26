# WiNGPT-3.0 技术报告

发布时间：2025年05月22日

`LLM应用` `医疗信息化`

> WiNGPT-3.0 Technical Report

# 摘要

> 当前大型语言模型 (LLMs) 在结构化、可解释且可验证的医疗推理领域面临显著局限性，同时在计算资源和数据隐私相关的实际部署方面也存在挑战。本报告聚焦于320亿参数规模的大型语言模型WiNGPT-3.0的开发，以提升其医疗推理能力，并探索其在医疗信息化基础设施中的有效整合潜力。研究的终极目标是推动临床适用性模型的发展。

为此，我们设计了一个多阶段的训练流程，专门针对通用、医疗及临床推理进行优化。该流程整合了监督微调（SFT）和强化学习（RL），借助精心编纂的长链式思维（CoT）数据集、辅助奖励模型，以及基于证据的诊断链模拟。WiNGPT-3.0展现出强劲性能：特定模型变体在MedCalc上取得了66.6分，在MedQA-USMLE上达到了87.1分。此外，针对性训练将临床推理任务的基准分数从58.1提升至62.5。

这些结果表明，即使在仅使用数千个示例的有限数据集上应用强化学习，也能显著提高医疗推理的准确性。尤为重要的是，这项研究证明了强化学习在数据和计算资源有限情况下的有效性，为临床工作流程和健康信息基础设施中部署更可靠、更实用的大型语言模型铺平了道路。

> Current Large Language Models (LLMs) exhibit significant limitations, notably in structured, interpretable, and verifiable medical reasoning, alongside practical deployment challenges related to computational resources and data privacy. This report focused on the development of WiNGPT-3.0, the 32-billion parameter LLMs, engineered with the objective of enhancing its capacity for medical reasoning and exploring its potential for effective integration within healthcare IT infrastructures. The broader aim is to advance towards clinically applicable models. The approach involved a multi-stage training pipeline tailored for general, medical, and clinical reasoning. This pipeline incorporated supervised fine-tuning (SFT) and reinforcement learning (RL), leveraging curated Long Chain-of-Thought (CoT) datasets, auxiliary reward models, and an evidence-based diagnostic chain simulation. WiNGPT-3.0 demonstrated strong performance: specific model variants achieved scores of 66.6 on MedCalc and 87.1 on MedQA-USMLE. Furthermore, targeted training improved performance on a clinical reasoning task from a baseline score of 58.1 to 62.5. These findings suggest that reinforcement learning, even when applied with a limited dataset of only a few thousand examples, can enhance medical reasoning accuracy. Crucially, this demonstration of RL's efficacy with limited data and computation paves the way for more trustworthy and practically deployable LLMs within clinical workflows and health information infrastructures.

[Arxiv](https://arxiv.org/abs/2505.17387)