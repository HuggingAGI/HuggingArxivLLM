# Enigmata：利用合成可验证谜题提升大型语言模型的逻辑推理能力

发布时间：2025年05月26日

`LLM应用` `逻辑推理`

> Enigmata: Scaling Logical Reasoning in Large Language Models with Synthetic Verifiable Puzzles

# 摘要

> 大型语言模型（LLMs）如 OpenAI 的 o1 和 DeepSeek 的 R1，擅长通过可验证奖励的强化学习（RLVR）处理数学和编程等高级推理任务，但对人类无需专业知识即可解决的谜题仍显吃力。为此，我们推出了 Enigmata，首个专为提升 LLM 解谜推理能力而设计的综合套件。它涵盖七个类别的 36 项任务，每项任务都配备了 1）一个能生成无限数量、难度可控的示例生成器，以及 2）一个用于自动评估的基于规则的验证器。这种生成器-验证器设计不仅支持多任务 RL 的可扩展训练，还便于细致分析和与 RLVR 的无缝整合。我们还提出了 Enigmata-Eval 严格基准测试，并开发了优化的多任务 RLVR 策略。我们的训练模型 Qwen2.5-32B-Enigmata 在 Enigmata-Eval、ARC-AGI（提升 32.8%）和 ARC-AGI 2（提升 0.6%）等解谜推理基准测试中表现优异，超越了 o3-mini-high 和 o1。它不仅在跨领域的解谜基准测试和数学推理任务中表现出色，且几乎无需多任务权衡。当在更大规模的模型（如 Seed1.5-Thinking，激活参数 20B，总参数 200B）上训练时，Enigmata 的解谜数据进一步提升了在高级数学和 STEM 推理任务（如 AIME (2024-2025)、BeyondAIME 和 GPQA (Diamond)）上的 SOTA 性能，充分展现了 Enigmata 在泛化能力上的优势。这项研究为提升 LLM 的逻辑推理能力提供了一个统一且可控的框架。更多资源请访问 https://seed-enigmata.github.io。


> Large Language Models (LLMs), such as OpenAI's o1 and DeepSeek's R1, excel at advanced reasoning tasks like math and coding via Reinforcement Learning with Verifiable Rewards (RLVR), but still struggle with puzzles solvable by humans without domain knowledge. We introduce Enigmata, the first comprehensive suite tailored for improving LLMs with puzzle reasoning skills. It includes 36 tasks across seven categories, each with 1) a generator that produces unlimited examples with controllable difficulty and 2) a rule-based verifier for automatic evaluation. This generator-verifier design supports scalable, multi-task RL training, fine-grained analysis, and seamless RLVR integration. We further propose Enigmata-Eval, a rigorous benchmark, and develop optimized multi-task RLVR strategies. Our trained model, Qwen2.5-32B-Enigmata, consistently surpasses o3-mini-high and o1 on the puzzle reasoning benchmarks like Enigmata-Eval, ARC-AGI (32.8%), and ARC-AGI 2 (0.6%). It also generalizes well to out-of-domain puzzle benchmarks and mathematical reasoning, with little multi-tasking trade-off. When trained on larger models like Seed1.5-Thinking (20B activated parameters and 200B total parameters), puzzle data from Enigmata further boosts SoTA performance on advanced math and STEM reasoning tasks such as AIME (2024-2025), BeyondAIME and GPQA (Diamond), showing nice generalization benefits of Enigmata. This work offers a unified, controllable framework for advancing logical reasoning in LLMs. Resources of this work can be found at https://seed-enigmata.github.io.

[Arxiv](https://arxiv.org/abs/2505.19914)