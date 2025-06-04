# # BranchLoRA：提升多模态持续指令微调的新方法

发布时间：2025年05月31日

`LLM理论

摘要讨论了多模态持续指令微调（MCIT）及其对多模态大型语言模型（MLLMs）的影响。论文提出了一种新的框架BranchLoRA，旨在解决现有方法中的参数低效和灾难性遗忘问题。这涉及到模型的训练和优化，属于LLM的理论层面。` `人工智能`

> Enhancing Multimodal Continual Instruction Tuning with BranchLoRA

# 摘要

> 多模态持续指令微调（MCIT）旨在使多模态大型语言模型（MLLMs）在序列任务中持续与人类意图保持一致。现有方法通常依赖于专家混合（MoE）的LoRA框架来保留之前的指令对齐。然而，这些方法容易出现灾难性遗忘（CF），因为它们通过简单的求和聚合所有LoRA块，随着时间的推移会损害性能。我们发现MoE LoRA框架在MCIT背景下存在一个关键的参数低效问题。基于这一发现，我们提出了BranchLoRA，一个不对称框架，以提升效率和性能。为缓解CF，我们在BranchLoRA中引入了一种灵活的调优-冻结机制，使各个分支能够专注于任务内知识，同时促进任务间的协作。此外，我们逐步引入任务特定的路由器，以确保随时间最优的分支分布，而不是偏袒最新任务。为了简化推理过程，我们引入了一个任务选择器，能够自动将测试输入路由到适当的路由器，而无需任务标识。在最新的MCIT基准上的广泛实验表明，BranchLoRA显著优于MoE LoRA，并在各种MLLM规模下保持其优势。

> Multimodal Continual Instruction Tuning (MCIT) aims to finetune Multimodal Large Language Models (MLLMs) to continually align with human intent across sequential tasks. Existing approaches often rely on the Mixture-of-Experts (MoE) LoRA framework to preserve previous instruction alignments. However, these methods are prone to Catastrophic Forgetting (CF), as they aggregate all LoRA blocks via simple summation, which compromises performance over time. In this paper, we identify a critical parameter inefficiency in the MoELoRA framework within the MCIT context. Based on this insight, we propose BranchLoRA, an asymmetric framework to enhance both efficiency and performance. To mitigate CF, we introduce a flexible tuning-freezing mechanism within BranchLoRA, enabling branches to specialize in intra-task knowledge while fostering inter-task collaboration. Moreover, we incrementally incorporate task-specific routers to ensure an optimal branch distribution over time, rather than favoring the most recent task. To streamline inference, we introduce a task selector that automatically routes test inputs to the appropriate router without requiring task identity. Extensive experiments on the latest MCIT benchmark demonstrate that BranchLoRA significantly outperforms MoELoRA and maintains its superiority across various MLLM sizes.

[Arxiv](https://arxiv.org/abs/2506.02041)