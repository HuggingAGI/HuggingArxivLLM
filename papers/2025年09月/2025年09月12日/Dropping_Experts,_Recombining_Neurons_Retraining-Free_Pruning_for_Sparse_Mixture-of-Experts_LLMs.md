# 丢弃专家模块，重组神经元：稀疏混合专家LLMs的免再训练剪枝

发布时间：2025年09月12日

`LLM理论` `基础理论`

> Dropping Experts, Recombining Neurons: Retraining-Free Pruning for Sparse Mixture-of-Experts LLMs

# 摘要

> 稀疏混合专家（SMoE）架构凭借计算效率优势，已成为大型语言模型（LLMs）的主流选择。但尽管每个token仅激活少数专家，SMoE仍需加载全部专家参数，导致内存占用过高，给部署带来难题。以往研究虽尝试通过剪枝和合并专家降低开销，但多聚焦于专家级操作，对神经元级结构的挖掘仍显不足。为此，我们提出DERN（丢弃专家，重组神经元）——一个任务无关、无需重新训练的专家剪枝与重构框架。我们发现，专家间常存在错位问题，且神经元层面存在语义冲突，直接合并难度较大。为解决这一问题，DERN通过三步实现：首先，基于路由统计剪枝冗余专家；接着，将被剪枝专家分解为神经元级片段，并将每个片段分配给最兼容的保留专家；最后，合并每个保留专家内的片段，构建紧凑表示。在Mixtral、Qwen和DeepSeek等SMoE模型上的实验显示，在50%专家稀疏度下，DERN无需额外训练，就能使常识推理和MMLU基准性能提升超5%，同时大幅减少专家数量和内存占用，让SMoE LLMs的实际部署更轻松。

> Sparse Mixture-of-Experts (SMoE) architectures are widely used in large language models (LLMs) due to their computational efficiency. However, though only a few experts are activated for each token, SMoE still requires loading all expert parameters, leading to high memory usage and challenges in deployment. Previous work has tried to reduce the overhead by pruning and merging experts, but primarily focused on expert-level operations, leaving neuron-level structure underexplored. We propose DERN (Dropping Experts, Recombining Neurons), a task-agnostic and retraining-free framework for expert pruning and reconstruction. We observe that experts are often misaligned and contain semantic conflicts at the neuron level, which poses challenges for direct merging. To solve this, DERN works in three steps: it first prunes redundant experts using router statistics; then it decomposes them into neuron-level expert segments, assigning each segment to its most compatible retained expert; and finally, it merges segments within each retained expert to build a compact representation. Experiments on Mixtral, Qwen, and DeepSeek SMoE models show that DERN improves performance by more than 5% on commonsense reasoning and MMLU benchmarks under 50% expert sparsity, without extra training. It also greatly reduces the number of experts and memory usage, making SMoE LLMs easier to deploy in practice.

[Arxiv](https://arxiv.org/abs/2509.10377)