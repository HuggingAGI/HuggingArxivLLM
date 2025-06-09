# MoA: 异构适配器混合用于大型语言模型的参数高效微调

发布时间：2025年06月06日

`LLM理论` `人工智能` `模型优化`

> MoA: Heterogeneous Mixture of Adapters for Parameter-Efficient Fine-Tuning of Large Language Models

# 摘要

> 近期研究将低秩适配（LoRA）与专家混合（MoE）相结合，进一步提升了参数高效微调（PEFT）方法在大型语言模型（LLM）中的性能。然而，现有方法采用的同构MoE-LoRA架构存在表示坍塌和专家负载不平衡的问题，限制了LLM的潜力。为解决这些挑战，我们提出了一种异构的	extbf{适配器混合（MoA）}方法。该方法通过动态整合结构各异的PEFT适配器专家，充分利用其互补的表示能力，促进专家专业化，从而更高效地将预训练知识迁移至下游任务。MoA具有两种变体：	extbf{(i)} 	extit{软MoA}通过加权融合所有专家输出实现细粒度整合；	extbf{(ii)} 	extit{稀疏MoA}根据专家贡献稀疏激活适配器专家，在几乎不影响性能的情况下完成任务。实验结果表明，异构MoA在性能和参数效率上均优于传统的MoE-LoRA方法。我们的项目已开源，地址为https://github.com/DCDmllm/MoA。

> Recent studies integrate Low-Rank Adaptation (LoRA) and Mixture-of-Experts (MoE) to further enhance the performance of parameter-efficient fine-tuning (PEFT) methods in Large Language Model (LLM) applications. Existing methods employ \emph{homogeneous} MoE-LoRA architectures composed of LoRA experts with either similar or identical structures and capacities. However, these approaches often suffer from representation collapse and expert load imbalance, which negatively impact the potential of LLMs. To address these challenges, we propose a \emph{heterogeneous} \textbf{Mixture-of-Adapters (MoA)} approach. This method dynamically integrates PEFT adapter experts with diverse structures, leveraging their complementary representational capabilities to foster expert specialization, thereby enhancing the effective transfer of pre-trained knowledge to downstream tasks. MoA supports two variants: \textbf{(i)} \textit{Soft MoA} achieves fine-grained integration by performing a weighted fusion of all expert outputs; \textbf{(ii)} \textit{Sparse MoA} activates adapter experts sparsely based on their contribution, achieving this with negligible performance degradation. Experimental results demonstrate that heterogeneous MoA outperforms homogeneous MoE-LoRA methods in both performance and parameter efficiency. Our project is available at https://github.com/DCDmllm/MoA.

[Arxiv](https://arxiv.org/abs/2506.05928)