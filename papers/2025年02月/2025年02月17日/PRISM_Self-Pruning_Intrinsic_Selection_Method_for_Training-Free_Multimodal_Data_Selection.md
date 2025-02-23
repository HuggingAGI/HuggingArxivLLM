# PRISM：无需训练的多模态数据选择自我剪裁内在方法

发布时间：2025年02月17日

`LLM应用

理由：这篇论文专注于优化预训练多模态大语言模型（MLLMs）的视觉指令微调过程，提出了一种高效的数据选择方法PRISM。虽然涉及多模态模型，但其核心是提升模型在实际任务中的性能，属于LLM的应用层面。` `人工智能` `计算机视觉`

> PRISM: Self-Pruning Intrinsic Selection Method for Training-Free Multimodal Data Selection

# 摘要

> 视觉指令微调是对预训练多模态大语言模型（MLLMs）的优化，旨在提升其在现实任务中的表现。然而，视觉指令数据集的快速扩张带来了显著的数据冗余，导致计算成本激增。现有的数据筛选方法主要依赖于代理模型或基于损失的指标，这两种方法由于需要模型推理和反向传播，均会产生巨大的计算开销。为了解决这一问题，我们提出了PRISM——一种无需训练的高效多模态数据选择新方法。与现有方法不同，PRISM摆脱了对代理模型、预热预训练和基于梯度优化的依赖。相反，它通过皮尔逊相关性分析量化MLLMs的内在视觉编码特性，计算特定任务的相关性得分，从而识别高价值样本。这不仅实现了数据高效的筛选，还保持了原有性能。在多个MLLM上的实证评估表明，PRISM将视觉指令微调和数据选择的总体时间缩短至传统方法的30%，同时在八项多模态和三项语言理解基准测试中超越了完全微调的模型，最终性能实现了101.7%的相对提升。


> Visual instruction tuning refines pre-trained Multimodal Large Language Models (MLLMs) to enhance their real-world task performance. However, the rapid expansion of visual instruction datasets introduces significant data redundancy, leading to excessive computational costs. Existing data selection methods predominantly rely on proxy models or loss-based metrics, both of which impose substantial computational overheads due to the necessity of model inference and backpropagation. To address this challenge, we propose PRISM, a novel training-free approach for efficient multimodal data selection. Unlike existing methods, PRISM eliminates the reliance on proxy models, warm-up pretraining, and gradient-based optimization. Instead, it leverages Pearson correlation analysis to quantify the intrinsic visual encoding properties of MLLMs, computing a task-specific correlation score to identify high-value instances. This not only enbles data-efficient selection,but maintains the original performance. Empirical evaluations across multiple MLLMs demonstrate that PRISM reduces the overall time required for visual instruction tuning and data selection to just 30% of conventional methods, while surpassing fully fine-tuned models across eight multimodal and three language understanding benchmarks, achieving a 101.7% relative improvement in final performance.

[Arxiv](https://arxiv.org/abs/2502.12119)