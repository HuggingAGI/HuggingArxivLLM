# A3：专用于注意力机制的分析性低秩近似框架

发布时间：2025年05月19日

`LLM理论` `人工智能`

> A3 : an Analytical Low-Rank Approximation Framework for Attention

# 摘要

> 大型语言模型虽然表现出色，但其庞大的参数规模导致部署成本高昂。低秩近似技术为模型压缩提供了新的可能，然而现有方法存在两大局限：(1) 它们仅关注单个线性层的输出误差最小化，忽视了Transformer的架构特性；(2) 通过将大权重矩阵分解为两个小低秩矩阵实现压缩。这些方法往往在性能上逊色于剪枝和量化等技术，同时引入了额外的运行时开销，例如为分解后的小矩阵额外启动GEMM核。针对这些问题，我们提出了$	t A^	t 3$，一个创新的后训练低秩近似框架。$	t A^	t 3$将Transformer层拆分为$	t QK$、$	t OV$和$	t MLP$三个功能组件。针对每个组件，$	t A^	t 3$提供了一种解析解，能够在减小组件内部隐藏维度的同时，最小化注意力分数误差、注意力输出误差和MLP输出误差。这种方法不仅直接减小了模型大小、KV缓存大小和计算量，还避免了额外的运行时开销。此外，它重新定义了优化问题的推进方向，从单一的线性层损失优化转向提升整体端到端性能。通过大量实验验证，$	t A^	t 3$展现了超越现有最优方法（SoTA）的性能。例如，在相同的计算和内存压缩预算下，我们的低秩近似LLaMA 3.1-70B在WikiText-2上实现了4.69的困惑度，优于前SoTA的7.87，提升了3.18。我们还展示了$	t A^	t 3$的灵活性，包括KV缓存压缩、量化以及混合秩分配以进一步提升性能。

> Large language models have demonstrated remarkable performance; however, their massive parameter counts make deployment highly expensive. Low-rank approximation offers a promising compression solution, yet existing approaches have two main limitations: (1) They focus on minimizing the output error of individual linear layers, without considering the architectural characteristics of Transformers, and (2) they decompose a large weight matrix into two small low-rank matrices. Consequently, these methods often fall short compared to other compression techniques like pruning and quantization, and introduce runtime overhead such as the extra GEMM kernel launches for decomposed small matrices. To address these limitations, we propose $\tt A^\tt 3$, a post-training low-rank approximation framework. $\tt A^\tt 3$ splits a Transformer layer into three functional components, namely $\tt QK$, $\tt OV$, and $\tt MLP$. For each component, $\tt A^\tt 3$ provides an analytical solution that reduces the hidden dimension size inside each component while minimizing the component's functional loss ($\it i.e.$, error in attention scores, attention outputs, and MLP outputs). This approach directly reduces model sizes, KV cache sizes, and FLOPs without introducing any runtime overheads. In addition, it provides a new narrative in advancing the optimization problem from singular linear layer loss optimization toward improved end-to-end performance. Through extensive experiments, we show that $\tt A^\tt 3$ maintains superior performance compared to SoTAs. For example, under the same reduction budget in computation and memory, our low-rank approximated LLaMA 3.1-70B achieves a perplexity of 4.69 on WikiText-2, outperforming the previous SoTA's 7.87 by 3.18. We also demonstrate the versatility of $\tt A^\tt 3$, including KV cache compression, quantization, and mixed-rank assignments for enhanced performance.

[Arxiv](https://arxiv.org/abs/2505.12942)