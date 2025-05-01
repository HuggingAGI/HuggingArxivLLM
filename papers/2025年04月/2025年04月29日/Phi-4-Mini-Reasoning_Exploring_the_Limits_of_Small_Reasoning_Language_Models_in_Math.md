# Phi-4-Mini-Reasoning：研究小型推理语言模型在数学推理任务中的极限

发布时间：2025年04月29日

`LLM应用

LLM应用` `人工智能`

> Phi-4-Mini-Reasoning: Exploring the Limits of Small Reasoning Language Models in Math

# 摘要

> 链式思维（CoT）通过训练大型语言模型（LLMs）生成中间推理步骤，显著提升了其推理能力。然而，受限于模型容量，提升小型语言模型（SLMs）的推理能力仍具挑战性。近期Deepseek-R1的研究表明，基于LLM生成的合成数据进行蒸馏，能够大幅增强SLM的推理能力，但其具体建模方法尚未公开。在本研究中，我们为SLMs提供了一套系统化的训练方案，包含四个关键步骤：（1）在多样化的长链式思维蒸馏数据上进行大规模中期训练；（2）基于高质量长链式思维数据进行监督微调；（3）利用精心整理的偏好数据集进行Rollout DPO；（4）采用可验证奖励的强化学习（RL）。我们将该方法应用于参数量为3.8B的紧凑型模型Phi-4-Mini。实验结果表明，Phi-4-Mini-Reasoning模型在数学推理任务上表现优异，超越了规模更大的推理模型。例如，在Math-500测试中，其表现优于DeepSeek-R1-Distill-Qwen-7B 3.2个百分点，以及DeepSeek-R1-Distill-Llama-8B 7.7个百分点。这证实了通过大规模高质量的CoT数据，结合精心设计的训练方案，即使在资源受限的小型模型中，也能有效解锁强大的推理能力。

> Chain-of-Thought (CoT) significantly enhances formal reasoning capabilities in Large Language Models (LLMs) by training them to explicitly generate intermediate reasoning steps. While LLMs readily benefit from such techniques, improving reasoning in Small Language Models (SLMs) remains challenging due to their limited model capacity. Recent work by Deepseek-R1 demonstrates that distillation from LLM-generated synthetic data can substantially improve the reasoning ability of SLM. However, the detailed modeling recipe is not disclosed. In this work, we present a systematic training recipe for SLMs that consists of four steps: (1) large-scale mid-training on diverse distilled long-CoT data, (2) supervised fine-tuning on high-quality long-CoT data, (3) Rollout DPO leveraging a carefully curated preference dataset, and (4) Reinforcement Learning (RL) with Verifiable Reward. We apply our method on Phi-4-Mini, a compact 3.8B-parameter model. The resulting Phi-4-Mini-Reasoning model exceeds, on math reasoning tasks, much larger reasoning models, e.g., outperforming DeepSeek-R1-Distill-Qwen-7B by 3.2 points and DeepSeek-R1-Distill-Llama-8B by 7.7 points on Math-500. Our results validate that a carefully designed training recipe, with large-scale high-quality CoT data, is effective to unlock strong reasoning capabilities even in resource-constrained small models.

[Arxiv](https://arxiv.org/abs/2504.21233)