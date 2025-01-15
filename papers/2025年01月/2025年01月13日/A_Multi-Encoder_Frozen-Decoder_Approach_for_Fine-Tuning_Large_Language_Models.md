# 多编码器冻结解码器：大型语言模型微调新方法

发布时间：2025年01月13日

`LLM应用

理由：该论文探讨了在多任务设置中冻结解码器的影响，特别是在自然语言任务中的应用。这涉及到大型语言模型（LLM）的微调策略，旨在降低部署成本并增强对新任务的适应性。因此，该论文属于LLM应用领域。` `多任务学习`

> A Multi-Encoder Frozen-Decoder Approach for Fine-Tuning Large Language Models

# 摘要

> 在参数高效微调方法中，冻结策略因其加速训练、减少灾难性遗忘和提升下游性能的优势而备受青睐。我们探讨了在多任务设置中冻结解码器的影响，涵盖多种自然语言任务，旨在降低部署成本并增强对新任务的适应性。通过在AlexaTM模型上进行单任务和多任务微调实验，我们发现冻结解码器对自然语言输出任务效果显著，且能有效缓解多语言任务中的灾难性遗忘。此外，将冻结解码器与更大模型结合，不仅能维持结构化和问答任务的性能，甚至还能进一步提升，使其成为适用于更广泛任务类型的有效策略。

> Among parameter-efficient fine-tuning methods, freezing has emerged as a popular strategy for speeding up training, reducing catastrophic forgetting, and improving downstream performance. We investigate the impact of freezing the decoder in a multi-task setup comprising diverse natural language tasks, aiming to reduce deployment overhead and enhance portability to novel tasks. Our experiments, conducted by fine-tuning both individual and multi-task setups on the AlexaTM model, reveal that freezing decoders is highly effective for tasks with natural language outputs and mitigates catastrophic forgetting in multilingual tasks. However, we find that pairing frozen decoders with a larger model can effectively maintain or even enhance performance in structured and QA tasks, making it a viable strategy for a broader range of task types.

[Arxiv](https://arxiv.org/abs/2501.07818)