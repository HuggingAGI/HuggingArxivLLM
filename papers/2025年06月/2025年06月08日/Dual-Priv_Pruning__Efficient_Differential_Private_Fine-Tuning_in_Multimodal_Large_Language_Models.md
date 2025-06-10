# # 双隐私剪枝：在多模态大型语言模型中实现高效差分隐私微调

发布时间：2025年06月08日

`LLM应用` `隐私保护`

> Dual-Priv Pruning : Efficient Differential Private Fine-Tuning in Multimodal Large Language Models

# 摘要

> 差分隐私 (DP) 是保护数据隐私的利器，因其有效性而被广泛采用，尤其在大型语言模型中扮演着关键角色。然而，其在多模态大型语言模型 (MLLMs) 中的实际效果仍有待验证。DP 的应用不可避免地带来计算开销，这一问题在处理海量文本和视觉数据的 MLLMs 中尤为凸显。更棘手的是，DP 为保护隐私而注入的噪声会随参数维度增加而放大，导致模型性能显著下降；这种隐私与效用的权衡让 DP 在复杂架构（如 MLLMs）中的应用变得尤为困难。

为了解决这些难题，我们提出了 Dual-Priv Pruning，一个专为 MLLMs 设计的差分隐私微调框架，通过两种互补机制实现优化：(i) 视觉令牌剪枝，通过移除冗余视觉信息降低输入维度；(ii) 基于噪声梯度幅度的更新剪枝。这种机制能在优化过程中选择性地剪枝参数更新，有效缓解噪声影响并提升模型效用。

实验结果表明，我们的方法在保持性能的同时实现了极具竞争力的效果。在计算效率方面，Dual-Priv Pruning 的内存占用始终低于标准 DP-SGD。值得注意的是，与存在严重性能瓶颈的零阶方法相比，我们的方法仅需额外 1.74% 的内存，而在 H20 GPU 上更展现了卓越的内存效率。据我们所知，这是首个针对 MLLMs 的 DP 微调研究。我们的代码即将开源，敬请期待！


> Differential Privacy (DP) is a widely adopted technique, valued for its effectiveness in protecting the privacy of task-specific datasets, making it a critical tool for large language models. However, its effectiveness in Multimodal Large Language Models (MLLMs) remains uncertain. Applying Differential Privacy (DP) inherently introduces substantial computation overhead, a concern particularly relevant for MLLMs which process extensive textual and visual data. Furthermore, a critical challenge of DP is that the injected noise, necessary for privacy, scales with parameter dimensionality, leading to pronounced model degradation; This trade-off between privacy and utility complicates the application of Differential Privacy (DP) to complex architectures like MLLMs. To address these, we propose Dual-Priv Pruning, a framework that employs two complementary pruning mechanisms for DP fine-tuning in MLLMs: (i) visual token pruning to reduce input dimensionality by removing redundant visual information, and (ii) gradient-update pruning during the DP optimization process. This second mechanism selectively prunes parameter updates based on the magnitude of noisy gradients, aiming to mitigate noise impact and improve utility. Experiments demonstrate that our approach achieves competitive results with minimal performance degradation. In terms of computational efficiency, our approach consistently utilizes less memory than standard DP-SGD. While requiring only 1.74% more memory than zeroth-order methods which suffer from severe performance issues on A100 GPUs, our method demonstrates leading memory efficiency on H20 GPUs. To the best of our knowledge, we are the first to explore DP fine-tuning in MLLMs. Our code is coming soon.

[Arxiv](https://arxiv.org/abs/2506.07077)