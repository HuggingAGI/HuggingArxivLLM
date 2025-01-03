# Tailored-LLaMA: 利用任务特定提示优化剪枝LLaMA模型的少样本学习

发布时间：2024年10月24日

`LLM应用

理由：这篇论文主要讨论了如何通过任务特定微调和剪枝技术来优化大型语言模型（LLM）的性能和计算资源需求。具体来说，论文提出了Tailored LLaMA方法，通过结构剪枝和LoRA方法加速微调，以在保持高性能的同时显著减小模型规模。这些技术和方法都是针对LLM在实际应用中的优化和改进，因此属于LLM应用的范畴。` `模型压缩`

> Tailored-LLaMA: Optimizing Few-Shot Learning in Pruned LLaMA Models with Task-Specific Prompts

# 摘要

> 大型语言模型在语言理解和生成方面表现出色，但训练这些模型，即使是简单的十亿参数版本，也需要大量计算资源，对许多组织来说经济上不可行。本文探讨了这些模型的任务特定微调。我们使用任务特定数据集和提示，微调了两个剪枝后的LLaMA模型（50亿和40亿参数），利用预训练权重，并通过LoRA方法专注于部分权重。微调LLaMA模型的一个挑战是设计精确的任务特定提示。为此，我们提出了一种新方法，在任务特异性和提示有效性约束下微调LLaMA模型。Tailored LLaMA方法首先通过结构剪枝将模型从7B缩减到5B和4B参数，然后应用精心设计的任务提示，并使用LoRA方法加速微调。通过50次少样本学习，剪枝50%的模型在不到一小时的微调后，分类任务的平均准确率在20%压缩比下恢复到95.68%，在50%压缩比下恢复到86.54%。验证结果表明，即使压缩到50%，模型在少样本分类和生成任务中仍保持超过65%的基线准确率，证明了我们方法在保持高性能的同时显著减小模型规模的有效性。

> Large language models demonstrate impressive proficiency in language understanding and generation. Nonetheless, training these models from scratch, even the least complex billion-parameter variant demands significant computational resources rendering it economically impractical for many organizations. With large language models functioning as general-purpose task solvers, this paper investigates their task-specific fine-tuning. We employ task-specific datasets and prompts to fine-tune two pruned LLaMA models having 5 billion and 4 billion parameters. This process utilizes the pre-trained weights and focuses on a subset of weights using the LoRA method. One challenge in fine-tuning the LLaMA model is crafting a precise prompt tailored to the specific task. To address this, we propose a novel approach to fine-tune the LLaMA model under two primary constraints: task specificity and prompt effectiveness. Our approach, Tailored LLaMA initially employs structural pruning to reduce the model sizes from 7B to 5B and 4B parameters. Subsequently, it applies a carefully designed prompt specific to the task and utilizes the LoRA method to accelerate the fine-tuning process. Moreover, fine-tuning a model pruned by 50\% for less than one hour restores the mean accuracy of classification tasks to 95.68\% at a 20\% compression ratio and to 86.54\% at a 50\% compression ratio through few-shot learning with 50 shots. Our validation of Tailored LLaMA on these two pruned variants demonstrates that even when compressed to 50\%, the models maintain over 65\% of the baseline model accuracy in few-shot classification and generation tasks. These findings highlight the efficacy of our tailored approach in maintaining high performance with significantly reduced model sizes.

[Arxiv](https://arxiv.org/abs/2410.19185)