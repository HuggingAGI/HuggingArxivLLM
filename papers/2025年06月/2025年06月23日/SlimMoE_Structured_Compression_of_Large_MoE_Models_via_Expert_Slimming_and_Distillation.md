# SlimMoE：通过专家剪枝与知识蒸馏对大型专家混合模型进行结构化压缩

发布时间：2025年06月23日

`LLM理论` `模型压缩`

> SlimMoE: Structured Compression of Large MoE Models via Expert Slimming and Distillation

# 摘要

> 专家混合（MoE）架构在保持推理效率的同时，为扩展大型语言模型（LLMs）提供了一种强大范式。然而，这些模型巨大的内存需求使其在资源受限环境中难以进行微调或部署。为解决这一难题，我们提出了SlimMoE——一个多阶段压缩框架，能够将大型MoE模型高效压缩为更小、更精简的版本，无需高昂的从头训练成本。

我们的方法通过系统性地精简专家网络，并借助中间阶段的知识迁移，有效减少了参数数量。这种多阶段压缩策略显著优于传统一次性剪枝方法，避免了性能大幅下降的问题。仅使用原模型10%的训练数据（4000亿token），我们就成功将Phi 3.5-MoE（419亿总参数/66亿激活参数）压缩为Phi-mini-MoE（76亿总参数/24亿激活参数）和Phi-tiny-MoE（38亿总参数/11亿激活参数）。这些压缩模型可在单GPU（A100或A6000）上轻松微调，特别适合学术研究和资源有限场景。

实验结果表明，这些压缩模型不仅在同尺寸模型中表现优异，甚至能与更大规模模型相媲美。Phi-mini-MoE仅使用原模型2/3的激活参数，即可实现与Phi-3-mini相当甚至更优的性能。在多语言理解评估（MMLU）中，其得分可与Llama 3.1 8B模型比肩，同时延迟大幅降低。我们的研究表明，结构化剪枝与分阶段蒸馏的结合为创建高质量、紧凑MoE模型提供了有效路径，为MoE架构的广泛应用铺平了道路。这些模型已在Hugging Face平台公开，地址为：https://huggingface.co/microsoft/Phi-mini-MoE-instruct 和 https://huggingface.co/microsoft/Phi-tiny-MoE-instruct。


> The Mixture of Experts (MoE) architecture has emerged as a powerful paradigm for scaling large language models (LLMs) while maintaining inference efficiency. However, their enormous memory requirements make them prohibitively expensive to fine-tune or deploy in resource-constrained environments. To address this challenge, we introduce SlimMoE, a multi-stage compression framework for transforming large MoE models into much smaller, efficient variants without incurring the prohibitive costs of training from scratch. Our method systematically reduces parameter counts by slimming experts and transferring knowledge through intermediate stages, effectively mitigating the performance degradation common in one-shot pruning approaches. Using this framework, we compress Phi 3.5-MoE (41.9B total/6.6B activated parameters) to create Phi-mini-MoE (7.6B total/2.4B activated parameters) and Phi-tiny-MoE (3.8B total/1.1B activated parameters) using only 400B tokens--less than 10% of the original model's training data. These compressed models can be fine-tuned on a single GPU (A100 for Phi-mini-MoE, A6000 for Phi-tiny-MoE), making them highly suitable for academic and resource-limited settings. Our experiments demonstrate that these compressed models outperform others of similar size and remain competitive with larger models. For instance, Phi-mini-MoE achieves similar or better performance to Phi-3-mini using only 2/3 of the activated parameters and yields comparable MMLU scores to Llama 3.1 8B despite having significantly lower latency. Our findings demonstrate that structured pruning combined with staged distillation offers an effective path to creating high-quality, compact MoE models, paving the way for broader adoption of MoE architectures. We make our models publicly available at https://huggingface.co/microsoft/Phi-mini-MoE-instruct and https://huggingface.co/microsoft/Phi-tiny-MoE-instruct .

[Arxiv](https://arxiv.org/abs/2506.18349)