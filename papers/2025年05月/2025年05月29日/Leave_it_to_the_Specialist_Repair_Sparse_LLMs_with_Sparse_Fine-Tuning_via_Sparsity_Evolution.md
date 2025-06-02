# 交给专家处理：通过稀疏性进化，使用稀疏微调修复稀疏LLMs。

发布时间：2025年05月29日

`LLM理论` `机器学习` `AI模型`

> Leave it to the Specialist: Repair Sparse LLMs with Sparse Fine-Tuning via Sparsity Evolution

# 摘要

> 大型语言模型 (LLMs) 在各类任务中表现出色，但其高昂的计算需求在实际部署中带来了挑战。现有的后训练剪枝方法如 SparseGPT 和 Wanda 虽能有效压缩模型规模，却难以在高稀疏度下维持性能，限制了其应用。目前的微调技术，包括全微调和 LoRA，由于需要更新全部密集参数，无法适应稀疏模型。针对这一问题，我们提出了一种专为稀疏 LLMs 设计的新方法——Sparsity Evolution Fine-Tuning (SEFT)。SEFT 在微调过程中动态优化剪枝模型的稀疏结构，同时保持整体稀疏性。通过“权重删除与生长”策略，SEFT 赋予模型根据目标数据集自我调整稀疏连接模式的能力。此外，采用敏感度驱动的剪枝标准，确保在整个微调过程中维持目标稀疏度。我们在 LLaMA 系列、DeepSeek 和 Mistral 等多种 LLMs 上的实验表明，SEFT 不仅性能更优，还在内存和时间效率上显著超越现有方法。我们的代码已公开，欢迎访问 https://github.com/QiaoXiao7282/SEFT。


> Large language models (LLMs) have achieved remarkable success across various tasks but face deployment challenges due to their massive computational demands. While post-training pruning methods like SparseGPT and Wanda can effectively reduce the model size, but struggle to maintain model performance at high sparsity levels, limiting their utility for downstream tasks. Existing fine-tuning methods, such as full fine-tuning and LoRA, fail to preserve sparsity as they require updating the whole dense metrics, not well-suited for sparse LLMs. In this paper, we propose Sparsity Evolution Fine-Tuning (SEFT), a novel method designed specifically for sparse LLMs. SEFT dynamically evolves the sparse topology of pruned models during fine-tuning, while preserving the overall sparsity throughout the process. The strengths of SEFT lie in its ability to perform task-specific adaptation through a weight drop-and-grow strategy, enabling the pruned model to self-adapt its sparse connectivity pattern based on the target dataset. Furthermore, a sensitivity-driven pruning criterion is employed to ensure that the desired sparsity level is consistently maintained throughout fine-tuning. Our experiments on various LLMs, including LLaMA families, DeepSeek, and Mistral, across a diverse set of benchmarks demonstrate that SEFT achieves stronger performance while offering superior memory and time efficiency compared to existing baselines. Our code is publicly available at: https://github.com/QiaoXiao7282/SEFT.

[Arxiv](https://arxiv.org/abs/2505.24037)