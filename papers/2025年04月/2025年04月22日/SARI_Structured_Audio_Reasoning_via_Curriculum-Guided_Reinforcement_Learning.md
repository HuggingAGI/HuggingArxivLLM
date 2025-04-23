# SARI: 基于课程引导强化学习的结构化音频推理

发布时间：2025年04月22日

`LLM应用` `音频处理` `语言模型`

> SARI: Structured Audio Reasoning via Curriculum-Guided Reinforcement Learning

# 摘要

> 近期研究表明，强化学习（RL）可以通过提示大语言模型（LLMs）“先思考后作答”，显著提升其推理能力。然而，这些改进是否以及如何迁移至音频语言推理领域仍 largely unexplored。我们将 DeepSeek-R1 的 Group-Relative Policy Optimization (GRPO) 框架扩展至大型音频语言模型（LALM），并构建了一个包含32,000个样本的多项选择语料库。通过分阶段的监督微调，首先针对结构化与非结构化的思维链进行训练，随后采用基于课程的 GRPO 进行优化，我们系统性地比较了相同架构下隐式与显式推理，以及结构化与自由形式推理的差异。我们的结构化音频推理模型 SARI（通过基于课程引导的强化学习实现结构化音频推理），相较于基础模型 Qwen2-Audio-7B-Instruct，平均准确率提升了16.35%。此外，基于 Qwen2.5-Omni 构建的变体在 MMAU 测试小型基准上达到了67.08%的 state-of-the-art 性能。通过消融实验，我们发现：(i) SFT 预热对稳定 RL 训练至关重要，(ii) 结构化思维链比非结构化思维链具有更强的泛化能力，(iii) 从易到难的课程设置加速了收敛并提升了最终性能。这些发现表明，显式的结构化推理与课程学习显著提升了音频语言理解能力。


> Recent work shows that reinforcement learning(RL) can markedly sharpen the reasoning ability of large language models (LLMs) by prompting them to "think before answering." Yet whether and how these gains transfer to audio-language reasoning remains largely unexplored. We extend the Group-Relative Policy Optimization (GRPO) framework from DeepSeek-R1 to a Large Audio-Language Model (LALM), and construct a 32k sample multiple-choice corpus. Using a two-stage regimen supervised fine-tuning on structured and unstructured chains-of-thought, followed by curriculum-guided GRPO, we systematically compare implicit vs. explicit, and structured vs. free form reasoning under identical architectures. Our structured audio reasoning model, SARI (Structured Audio Reasoning via Curriculum-Guided Reinforcement Learning), achieves a 16.35% improvement in average accuracy over the base model Qwen2-Audio-7B-Instruct. Furthermore, the variant built upon Qwen2.5-Omni reaches state-of-the-art performance of 67.08% on the MMAU test-mini benchmark. Ablation experiments show that on the base model we use: (i) SFT warm-up is important for stable RL training, (ii) structured chains yield more robust generalization than unstructured ones, and (iii) easy-to-hard curricula accelerate convergence and improve final performance. These findings demonstrate that explicit, structured reasoning and curriculum learning substantially enhances audio-language understanding.

[Arxiv](https://arxiv.org/abs/2504.15900)