# 加速链式思维推理：目标梯度重要性与动态跳转的结合

发布时间：2025年05月13日

`LLM应用` `人工智能`

> Accelerating Chain-of-Thought Reasoning: When Goal-Gradient Importance Meets Dynamic Skipping

# 摘要

> 大型语言模型（LLMs）利用链式思考（CoT）提示技术处理复杂任务，但其推理过程往往冗长低效，导致了高昂的计算成本和显著的延迟。现有的CoT压缩技术通常依赖通用的重要性指标和静态压缩率，这可能无意中移除关键功能标记，或无法适应不同推理复杂度的场景。为克服这些限制，我们提出了Adaptive GoGI-Skip——一个通过监督微调学习动态CoT压缩的新型框架。该方法引入了两个协同创新：(1) 目标-梯度重要性（GoGI），一种通过测量中间表示对最终答案损失的梯度影响，准确识别功能相关标记的新指标；(2) 自适应动态跳过（ADS），一种根据运行时模型不确定性动态调节压缩率的机制，同时通过自适应N标记约束确保局部连贯性。据我们所知，这是首个将目标导向的梯度重要性指标与动态、感知不确定性的跳过机制相结合用于CoT压缩的工作。在压缩的MATH数据集上训练，Adaptive GoGI-Skip在AIME、GPQA和GSM8K等多样化推理基准测试中展现了强大的跨领域泛化能力。它实现了显著的效率提升——平均减少45%以上的CoT标记数量，并带来1.6-2.0倍的推理加速——同时保持了高推理准确性。值得注意的是，它在保持准确性的同时，即使在高压缩率下也显著优于现有基线，推动了CoT推理效率-准确性权衡领域的最新进展。

> Large Language Models leverage Chain-of-Thought (CoT) prompting for complex tasks, but their reasoning traces are often excessively verbose and inefficient, leading to significant computational costs and latency. Current CoT compression techniques typically rely on generic importance metrics and static compression rates, which may inadvertently remove functionally critical tokens or fail to adapt to varying reasoning complexity. To overcome these limitations, we propose Adaptive GoGI-Skip, a novel framework learning dynamic CoT compression via supervised fine-tuning. This approach introduces two synergistic innovations: (1) Goal-Gradient Importance (GoGI), a novel metric accurately identifying functionally relevant tokens by measuring the gradient influence of their intermediate representations on the final answer loss, and (2) Adaptive Dynamic Skipping (ADS), a mechanism dynamically regulating the compression rate based on runtime model uncertainty while ensuring local coherence through an adaptive N-token constraint. To our knowledge, this is the first work unifying a goal-oriented, gradient-based importance metric with dynamic, uncertainty-aware skipping for CoT compression. Trained on compressed MATH data, Adaptive GoGI-Skip demonstrates strong cross-domain generalization across diverse reasoning benchmarks including AIME, GPQA, and GSM8K. It achieves substantial efficiency gains - reducing CoT token counts by over 45% on average and delivering 1.6-2.0 times inference speedups - while maintaining high reasoning accuracy. Notably, it significantly outperforms existing baselines by preserving accuracy even at high effective compression rates, advancing the state of the art in the CoT reasoning efficiency-accuracy trade-off.

[Arxiv](https://arxiv.org/abs/2505.08392)