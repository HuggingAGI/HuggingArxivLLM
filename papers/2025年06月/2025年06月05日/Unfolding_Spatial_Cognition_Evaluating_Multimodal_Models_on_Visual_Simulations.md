# # 解构空间认知：多模态模型在视觉模拟中的评估表现

发布时间：2025年06月05日

`LLM应用` `空间推理` `多模态模型`

> Unfolding Spatial Cognition: Evaluating Multimodal Models on Visual Simulations

# 摘要

> 空间认知是人类智能的关键，它不仅依赖语言推理，还能通过视觉模拟来解决问题。然而，现有的AI基准测试大多聚焦于语言推理，忽视了非语言、多步骤视觉模拟的复杂性。为此，我们推出了STARE（空间变换与推理评估），这是一个专门评估多模态大型语言模型在更适合通过多步骤视觉模拟解决的任务上的基准测试。STARE涵盖了基础几何变换（2D和3D）、综合空间推理（立方体折叠和七巧板谜题）以及现实世界空间推理（视角和时间推理）的4000个任务，反映了物体组装、机械图解解读和日常空间导航等实际认知挑战。我们的评估结果显示，模型在简单的2D变换推理上表现出色，但在需要多步骤视觉模拟的复杂任务（如3D立方体折叠和七巧板谜题）上表现接近随机猜测。人类在复杂任务上接近完美准确，但需要较长的时间（高达28.9秒），通过中间视觉模拟显着加快速度（平均减少7.5秒）。相比之下，模型从视觉模拟中获得的性能提升并不一致，大多数任务有所改善，但在特定情况下（如七巧板谜题（GPT-4o，o1）和立方体折叠（Claude-3.5，Gemini-2.0 Flash））表现下降，表明模型可能尚未掌握如何有效利用中间视觉信息。

> Spatial cognition is essential for human intelligence, enabling problem-solving through visual simulations rather than solely relying on verbal reasoning. However, existing AI benchmarks primarily assess verbal reasoning, neglecting the complexities of non-verbal, multi-step visual simulation. We introduce STARE(Spatial Transformations and Reasoning Evaluation), a benchmark designed to rigorously evaluate multimodal large language models on tasks better solved through multi-step visual simulation. STARE features 4K tasks spanning foundational geometric transformations (2D and 3D), integrated spatial reasoning (cube net folding and tangram puzzles), and real-world spatial reasoning (perspective and temporal reasoning), reflecting practical cognitive challenges like object assembly, mechanical diagram interpretation, and everyday spatial navigation. Our evaluations show that models excel at reasoning over simpler 2D transformations, but perform close to random chance on more complex tasks like 3D cube net folding and tangram puzzles that require multi-step visual simulations. Humans achieve near-perfect accuracy but take considerable time (up to 28.9s) on complex tasks, significantly speeding up (down by 7.5 seconds on average) with intermediate visual simulations. In contrast, models exhibit inconsistent performance gains from visual simulations, improving on most tasks but declining in specific cases like tangram puzzles (GPT-4o, o1) and cube net folding (Claude-3.5, Gemini-2.0 Flash), indicating that models may not know how to effectively leverage intermediate visual information.

[Arxiv](https://arxiv.org/abs/2506.04633)