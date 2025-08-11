# LoRA 递归应用：探索面向持续视觉指令微调的参数高效架构扩展

发布时间：2025年08月08日

`LLM理论` `人工智能` `多模态学习`

> LoRA in LoRA: Towards Parameter-Efficient Architecture Expansion for Continual Visual Instruction Tuning

# 摘要

> 持续视觉指令微调 (CVIT) 让多模态大语言模型 (MLLMs) 能够逐步掌握新任务。然而，这一过程面临一个重大挑战：灾难性遗忘。具体来说，当模型适应新任务时，它对之前学习任务的性能往往会下降。为了解决这个问题，通常会采用架构扩展的方法，通过引入任务特定模块来避免干扰。然而，现有的方法往往为每个任务扩展整个层，这导致了显著的参数开销和较差的扩展性。为了克服这些挑战，我们提出了针对 MLLMs CVIT 的高效架构扩展方法 LiLoRA (LoRA in LoRA)。LiLoRA 在任务间共享 LoRA 矩阵 A，从而减少冗余；对矩阵 B 进行额外的低秩分解，以最小化任务特定参数；并引入余弦正则化稳定性损失，以保持共享表示在时间上的一致性。在多样化的 CVIT 基准上进行的广泛实验表明，LiLoRA 在序列任务学习中始终表现更优，同时与现有方法相比，显著提高了参数效率。

> Continual Visual Instruction Tuning (CVIT) enables Multimodal Large Language Models (MLLMs) to incrementally learn new tasks over time. However, this process is challenged by catastrophic forgetting, where performance on previously learned tasks deteriorates as the model adapts to new ones. A common approach to mitigate forgetting is architecture expansion, which introduces task-specific modules to prevent interference. Yet, existing methods often expand entire layers for each task, leading to significant parameter overhead and poor scalability. To overcome these issues, we introduce LoRA in LoRA (LiLoRA), a highly efficient architecture expansion method tailored for CVIT in MLLMs. LiLoRA shares the LoRA matrix A across tasks to reduce redundancy, applies an additional low-rank decomposition to matrix B to minimize task-specific parameters, and incorporates a cosine-regularized stability loss to preserve consistency in shared representations over time. Extensive experiments on a diverse CVIT benchmark show that LiLoRA consistently achieves superior performance in sequential task learning while significantly improving parameter efficiency compared to existing approaches.

[Arxiv](https://arxiv.org/abs/2508.06202)