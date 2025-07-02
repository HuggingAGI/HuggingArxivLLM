# 强化学习助力多语言大模型多图像接地推理能力提升

发布时间：2025年07月01日

`LLM应用` `多模态模型`

> Improving the Reasoning of Multi-Image Grounding in MLLMs via Reinforcement Learning

# 摘要

> 最近，多模态大型语言模型 (MLLMs) 在单图像场景中表现出色，但面对复杂多图像组合和多模态指令的现实任务时，性能明显下降，这表明其跨图像推理和泛化能力存在局限。为解决这一问题，我们提出了一种基于强化学习 (RL) 的后训练策略，以提升 MLLMs 在多图像接地任务中的推理性能。我们的方法首先通过合成高质量的思维链 (CoT) 数据进行冷启动初始化，随后利用低秩适应 (LoRA) 进行监督微调 (SFT)。冷启动训练阶段帮助模型识别正确解决方案，随后我们使用合并的 SFT 模型进行拒绝采样，整理高质量 RL 数据，并借助基于规则的 RL 引导模型走向最优推理路径。实验结果表明，我们的方法在 MIG-Bench 上比 SFT 基线提升了 +9.04\% 的性能，并在多个跨领域推理接地基准测试中提升了 +4.98\%。此外，我们在多图像感知方面展示了强大的泛化能力，在 BLINK 和 MMIU 基准测试的子集上分别比基础模型提升了 +3.1\% 和 +2.4\%。

> Recently, Multimodal Large Language Models (MLLMs) excel at visual grounding in single-image scenarios with textual references. However, their performance degrades when handling real-world applications involving complex multi-image compositions and multimodal instructions, which reveals limitations in cross-image reasoning and generalization. To address these challenges, we adopt a Reinforcement Learning (RL) based post-training strategy to improve the reasoning performance of MLLMs in multi-image grounding tasks. Our approach begins with synthesizing high-quality chain-of-thought (CoT) data for cold-start initialization, followed by supervised fine-tuning (SFT) using low-rank adaptation (LoRA). The cold-start training stage enables the model to identify correct solutions. Subsequently, we perform rejection sampling using the merged SFT model to curate high-quality RL data and leverage rule-based RL to guide the model toward optimal reasoning paths. Extensive experimental results demonstrate the effectiveness of our approach, achieving +9.04\% improvements on MIG-Bench and +4.98\% improvements on several out-of-domain reasoning grounding benchmarks over the SFT baseline. Furthermore, our approach exhibits strong generalization in multi-image perception, with gains of +3.1\% and +2.4\% over the base model on subsets of the BLINK and MMIU benchmarks, respectively.

[Arxiv](https://arxiv.org/abs/2507.00748)