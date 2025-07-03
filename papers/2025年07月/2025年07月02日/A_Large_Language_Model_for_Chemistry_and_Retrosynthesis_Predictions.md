# # 大语言模型在化学与逆合成预测中的应用

发布时间：2025年07月02日

`LLM应用` `逆合成路线规划`

> A Large Language Model for Chemistry and Retrosynthesis Predictions

# 摘要

> 大型语言模型 (LLM) 在广泛的任务中展现了强大的能力，但在化学领域仍面临挑战，主要源于缺乏领域数据和对精确推理的需求。我们推出 ECNU-ChemGPT（以华东师范大学命名），一个专注于化学的 LLM，致力于深度化学知识理解和精准逆合成路线规划。我们的方法通过四个关键策略实现突破：

1. **结构化提示的知识蒸馏**：从权威化学教材中提取知识，构建高质量问答数据集。
2. **领域特定提示工程**：结合精选化学关键词和 LLMs API，实现数据推导和知识蒸馏。
3. **大规模微调**：在清洗和增强的 Pistachio 数据集上训练，提升逆合成预测精度。
4. **动态多模型调度**：整合 BrainGPT，智能调用多个专用模型，满足多样化化学任务需求。

ECNU-ChemGPT 在化学问答和逆合成规划中表现出色，超越 Deepseek-R1、Qwen-2.5 和 GPT-4o 等主流模型。在逆合成方面，其在 USPTO_50K 数据集上达到 68.3% 的 Top-1 准确率，并成功重构 13 个真实药物分子的实验路径。这些成果证明了领域微调与多模型调度结合的强大效果，为化学研究提供了高效 robust 的解决方案。

> Large language models (LLM) have achieved impressive progress across a broad range of general-purpose tasks, but their effectiveness in chemistry remains limited due to scarce domain-specific datasets and the demand for precise symbolic and structural reasoning. Here we introduce ECNU-ChemGPT(name after East China Normal University), a chemistry-specialized LLM engineered for deep chemical knowledge understanding and accurate retrosynthetic route planning. Our approach is distinguished by four key strategies: structured prompt-based knowledge distillation from authoritative chemistry textbooks to construct a high-quality question-answering dataset; domain-specific prompt engineering using curated chemical keywords, combined with LLMs APIs for data derivation and knowledge distillation; large-scale fine-tuning on a meticulously cleaned and enriched Pistachio reaction dataset to enhance retrosynthesis prediction accuracy; and integration of BrainGPT, a dynamic multi-model scheduling framework that enables task-specific invocation of multiple specialized models trained for diverse chemistry-related tasks. ECNU-ChemGPT exhibits superior performance on chemistry question-answering and retrosynthetic planning benchmarks, outperforming leading general-purpose models-including Deepseek-R1, Qwen-2.5, and GPT-4o. In retrosynthesis, it achieves a Top-1 accuracy of 68.3% on the USPTO_50K dataset and successfully reconstructed 13 complete experimental pathways for real-world drug molecules from medicinal chemistry journals. These results underscore the effectiveness of domain-adapted fine-tuning combined with dynamic multi-model task scheduling, providing a scalable and robust solution for chemical knowledge question answering and retrosynthetic planning.

[Arxiv](https://arxiv.org/abs/2507.01444)