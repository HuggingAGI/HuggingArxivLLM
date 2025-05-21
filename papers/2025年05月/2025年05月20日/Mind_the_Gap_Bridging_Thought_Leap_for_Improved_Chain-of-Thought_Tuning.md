# # 注意思维差距，弥合思维跳跃，提升链式思维调整效果
注意思维差距，弥合思维跳跃，提升链式思维调整效果

发布时间：2025年05月20日

`LLM应用`

> Mind the Gap: Bridging Thought Leap for Improved Chain-of-Thought Tuning

# 摘要

> 大型语言模型（LLMs）在数学任务中通过链式思维（CoT）推理取得了显著进展。然而，现有数学 CoT 数据集常因专家省略中间步骤而导致思维跳跃，这对模型学习和泛化能力产生负面影响。为此，我们提出了 CoT 思维跳跃搭桥任务，旨在自动检测思维跳跃并生成缺失的中间推理步骤，以恢复 CoT 的完整性和连贯性。基于结构化的 ScaleQuestMath 数据集，我们构建了专门的训练数据集 ScaleQM+，并训练了 CoT-Bridge 模型来搭桥思维跳跃。通过全面的实验评估，我们在数学推理基准上证明，基于搭桥数据集微调的模型始终优于原始数据集训练的模型，其中在 NuminaMath 上的提升幅度最高可达 +5.87%。我们的方法有效提升了蒸馏数据质量（+3.02%），并为强化学习提供了更好的起点（+3.1%），作为一个即插即用模块，与现有优化技术兼容。此外，CoT-Bridge 在跨领域逻辑推理任务中表现出更好的泛化能力，证实了增强推理完整性的广泛适用性收益。

> Large language models (LLMs) have achieved remarkable progress on mathemati-cal tasks through Chain-of-Thought (CoT) reasoning. However, existing mathematical CoT datasets often suffer from Thought Leaps due to experts omitting intermediate steps, which negatively impacts model learning and generalization. We propose the CoT Thought Leap Bridge Task, which aims to automatically detect leaps and generate missing intermediate reasoning steps to restore the completeness and coherence of CoT. To facilitate this, we constructed a specialized training dataset called ScaleQM+, based on the structured ScaleQuestMath dataset, and trained CoT-Bridge to bridge thought leaps. Through comprehensive experiments on mathematical reasoning benchmarks, we demonstrate that models fine-tuned on bridged datasets consistently outperform those trained on original datasets, with improvements of up to +5.87% on NuminaMath. Our approach effectively enhances distilled data (+3.02%) and provides better starting points for reinforcement learning (+3.1%), functioning as a plug-and-play module compatible with existing optimization techniques. Furthermore, CoT-Bridge demonstrate improved generalization to out-of-domain logical reasoning tasks, confirming that enhancing reasoning completeness yields broadly applicable benefits.

[Arxiv](https://arxiv.org/abs/2505.14684)