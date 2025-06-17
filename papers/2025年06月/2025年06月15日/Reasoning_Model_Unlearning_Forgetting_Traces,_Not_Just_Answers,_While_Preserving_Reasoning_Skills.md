# 推理模型的遗忘：遗忘的不仅是答案，更是推理的痕迹，同时保留推理能力

发布时间：2025年06月15日

`LLM应用` `人工智能安全` `机器学习`

> Reasoning Model Unlearning: Forgetting Traces, Not Just Answers, While Preserving Reasoning Skills

# 摘要

> 大型推理模型（LRMs）的最新进展通过推理时计算，实现了强大的链式思维（CoT）生成能力。然而，这种多步推理能力在提升语言模型性能的同时，也带来了新的安全风险。本文首次系统性地研究了大型推理模型背景下的机器遗忘问题。机器遗忘是指在不进行完全重新训练的情况下，从训练好的模型中移除敏感、有害或不受欢迎的数据或知识的过程。我们发现，传统遗忘算法难以满足LRMs的需求。即使最终答案被成功擦除，敏感信息仍可能残留在中间推理步骤中。针对这一挑战，我们扩展了传统遗忘方法，提出了基于推理的遗忘表示误导方法（R²MU）。该方法能够有效抑制敏感推理轨迹，防止生成相关最终答案，同时保留模型的推理能力。实验结果表明，R²MU显著减少了推理轨迹中的敏感信息泄露，并在安全性和推理能力方面均取得了优异表现，测试模型包括DeepSeek-R1-Distill-LLaMA-8B和DeepSeek-R1-Distill-Qwen-14B等最新模型。


> Recent advances in large reasoning models (LRMs) have enabled strong chain-of-thought (CoT) generation through test-time computation. While these multi-step reasoning capabilities represent a major milestone in language model performance, they also introduce new safety risks. In this work, we present the first systematic study to revisit the problem of machine unlearning in the context of LRMs. Machine unlearning refers to the process of removing the influence of sensitive, harmful, or undesired data or knowledge from a trained model without full retraining. We show that conventional unlearning algorithms, originally designed for non-reasoning models, are inadequate for LRMs. In particular, even when final answers are successfully erased, sensitive information often persists within the intermediate reasoning steps, i.e., CoT trajectories. To address this challenge, we extend conventional unlearning and propose Reasoning-aware Representation Misdirection for Unlearning ($R^2MU$), a novel method that effectively suppresses sensitive reasoning traces and prevents the generation of associated final answers, while preserving the model's reasoning ability. Our experiments demonstrate that $R^2MU$ significantly reduces sensitive information leakage within reasoning traces and achieves strong performance across both safety and reasoning benchmarks, evaluated on state-of-the-art models such as DeepSeek-R1-Distill-LLaMA-8B and DeepSeek-R1-Distill-Qwen-14B.

[Arxiv](https://arxiv.org/abs/2506.12963)