# 过于热心、过于温和、过于诚实，还是恰到好处？

发布时间：2025年09月10日

`LLM应用` `基础理论`

> Too Helpful, Too Harmless, Too Honest or Just Right?

# 摘要

> 大型语言模型（LLMs）在各类NLP任务中表现卓越，但要使其输出符合有用性、无害性与诚实性（HHH）原则，仍是一项长期挑战。现有方法往往孤立优化单个对齐维度，进而产生权衡取舍与行为不一致的问题。混合专家（MoE）架构虽具备模块化优势，却受限于路由校准不足，在对齐任务中的效果大打折扣。为此，我们提出TrinityX——一个模块化对齐框架，它在Transformer架构中融入了校准专家混合（MoCaE）机制。TrinityX为每个HHH维度配备独立训练的专家，并通过校准的任务自适应路由机制整合其输出，将专家信号融合为统一的对齐感知表示。在Alpaca（有用性）、BeaverTails（无害性）和TruthfulQA（诚实性）三个标准对齐基准上的大量实验显示，TrinityX性能超越了强大的基线模型，胜率相对提升32.5%，安全分数提升33.9%，诚实性提升28.4%。此外，与以往基于MoE的方法相比，TrinityX还将内存占用和推理延迟降低了40%以上。消融实验凸显了校准路由的关键作用，跨模型评估则证实TrinityX可在各类LLM骨干网络上有效泛化。

> Large Language Models (LLMs) exhibit strong performance across a wide range of NLP tasks, yet aligning their outputs with the principles of Helpfulness, Harmlessness, and Honesty (HHH) remains a persistent challenge. Existing methods often optimize for individual alignment dimensions in isolation, leading to trade-offs and inconsistent behavior. While Mixture-of-Experts (MoE) architectures offer modularity, they suffer from poorly calibrated routing, limiting their effectiveness in alignment tasks. We propose TrinityX, a modular alignment framework that incorporates a Mixture of Calibrated Experts (MoCaE) within the Transformer architecture. TrinityX leverages separately trained experts for each HHH dimension, integrating their outputs through a calibrated, task-adaptive routing mechanism that combines expert signals into a unified, alignment-aware representation. Extensive experiments on three standard alignment benchmarks-Alpaca (Helpfulness), BeaverTails (Harmlessness), and TruthfulQA (Honesty)-demonstrate that TrinityX outperforms strong baselines, achieving relative improvements of 32.5% in win rate, 33.9% in safety score, and 28.4% in truthfulness. In addition, TrinityX reduces memory usage and inference latency by over 40% compared to prior MoE-based approaches. Ablation studies highlight the importance of calibrated routing, and cross-model evaluations confirm TrinityX's generalization across diverse LLM backbones.

[Arxiv](https://arxiv.org/abs/2509.08486)