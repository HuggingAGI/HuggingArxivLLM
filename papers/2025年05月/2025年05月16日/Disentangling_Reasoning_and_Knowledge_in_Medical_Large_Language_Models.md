# 解耦医学大型语言模型中的推理与知识，深入理解模型能力

发布时间：2025年05月16日

`LLM应用` `问答系统`

> Disentangling Reasoning and Knowledge in Medical Large Language Models

# 摘要

> 大型语言模型（LLMs）在医学推理领域致力于模拟临床医生的诊断思维，但现有基准测试如MedQA-USMLE、MedMCQA和PubMedQA往往将推理与事实记忆混为一谈。我们通过PubMedBERT分类器（准确率达81%，与人类相当）将11个生物医学问答基准测试分为推理型和知识型子集。分析显示，仅32.8%的问题需要复杂推理。我们评估了生物医学模型（HuatuoGPT-o1、MedReason、m1）和通用领域模型（DeepSeek-R1、o4-mini、Qwen3），发现知识型和推理型任务的表现存在显著差异。例如，m1在知识型任务中得分60.5，但在推理型任务中仅得47.1分。对抗性测试中，当模型被错误的初始推理误导时，生物医学模型的表现大幅下降，而规模更大或经过强化学习训练的通用模型则更具鲁棒性。为解决这一问题，我们通过在推理密集型示例上进行微调和强化学习，训练出了BioMed-R1模型。该模型在同类模型中表现最佳。未来，整合临床病例报告以及采用对抗性和回溯场景进行训练，可能会进一步提升模型性能。


> Medical reasoning in large language models (LLMs) aims to emulate clinicians' diagnostic thinking, but current benchmarks such as MedQA-USMLE, MedMCQA, and PubMedQA often mix reasoning with factual recall. We address this by separating 11 biomedical QA benchmarks into reasoning- and knowledge-focused subsets using a PubMedBERT classifier that reaches 81 percent accuracy, comparable to human performance. Our analysis shows that only 32.8 percent of questions require complex reasoning. We evaluate biomedical models (HuatuoGPT-o1, MedReason, m1) and general-domain models (DeepSeek-R1, o4-mini, Qwen3), finding consistent gaps between knowledge and reasoning performance. For example, m1 scores 60.5 on knowledge but only 47.1 on reasoning. In adversarial tests where models are misled with incorrect initial reasoning, biomedical models degrade sharply, while larger or RL-trained general models show more robustness. To address this, we train BioMed-R1 using fine-tuning and reinforcement learning on reasoning-heavy examples. It achieves the strongest performance among similarly sized models. Further gains may come from incorporating clinical case reports and training with adversarial and backtracking scenarios.

[Arxiv](https://arxiv.org/abs/2505.11462)