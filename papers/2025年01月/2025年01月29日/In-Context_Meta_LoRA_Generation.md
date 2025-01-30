# 上下文元 LoRA 生成

发布时间：2025年01月29日

`LLM应用

理由：这篇论文主要讨论了如何通过In-Context Meta LoRA（ICM-LoRA）方法在多任务场景下高效地生成任务感知的LoRA权重，从而优化大型语言模型（LLMs）的任务定制。该方法通过条件变分自编码器（CVAE）和上下文元学习来捕捉任务间的关联，并生成适用于多种任务的LoRA参数。这些内容涉及如何在实际应用中优化和定制LLMs，因此属于LLM应用的范畴。` `多任务学习`

> In-Context Meta LoRA Generation

# 摘要

> # 摘要
低秩适应（LoRA）在任务特定微调中表现出色，但在多任务场景下，为每个任务单独训练LoRA模型会导致存储和推理效率低下。现有方法难以捕捉任务间的关联，使得多任务LoRA参数生成颇具挑战。为此，我们提出了In-Context Meta LoRA（ICM-LoRA），一种高效实现LLMs任务定制的新方法。我们利用所有任务的训练数据，训练了一个条件变分自编码器（CVAE）作为生成器。CVAE以任务描述为输入，输出任务感知的LoRA权重，这些权重与LLMs结合，无需额外微调即可生成任务专用模型。我们还通过上下文元学习进行知识增强和任务映射，以捕捉任务与参数分布的关系。因此，ICM-LoRA能够更准确地生成适用于多种任务的LoRA参数，其重建精度优于现有方法，并有助于实现LoRA参数的任务特定增强。此外，该方法仅占用283MB存储空间，仅为原始LoRA的1%。

> Low-rank Adaptation (LoRA) has demonstrated remarkable capabilities for task specific fine-tuning. However, in scenarios that involve multiple tasks, training a separate LoRA model for each one results in considerable inefficiency in terms of storage and inference. Moreover, existing parameter generation methods fail to capture the correlations among these tasks, making multi-task LoRA parameter generation challenging. To address these limitations, we propose In-Context Meta LoRA (ICM-LoRA), a novel approach that efficiently achieves task-specific customization of large language models (LLMs). Specifically, we use training data from all tasks to train a tailored generator, Conditional Variational Autoencoder (CVAE). CVAE takes task descriptions as inputs and produces task-aware LoRA weights as outputs. These LoRA weights are then merged with LLMs to create task-specialized models without the need for additional fine-tuning. Furthermore, we utilize in-context meta-learning for knowledge enhancement and task mapping, to capture the relationship between tasks and parameter distributions. As a result, our method achieves more accurate LoRA parameter generation for diverse tasks using CVAE. ICM-LoRA enables more accurate LoRA parameter reconstruction than current parameter reconstruction methods and is useful for implementing task-specific enhancements of LoRA parameters. At the same time, our method occupies 283MB, only 1\% storage compared with the original LoRA.

[Arxiv](https://arxiv.org/abs/2501.17635)