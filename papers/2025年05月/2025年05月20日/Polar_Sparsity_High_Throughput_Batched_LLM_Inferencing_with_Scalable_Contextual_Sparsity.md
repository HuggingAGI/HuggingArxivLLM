# 极稀疏性：高吞吐量批量LLM推理，基于可扩展上下文稀疏性

发布时间：2025年05月20日

`LLM应用` `人工智能`

> Polar Sparsity: High Throughput Batched LLM Inferencing with Scalable Contextual Sparsity

# 摘要

> 加速大型语言模型（LLM）推理对于需要高吞吐量和低延迟的现实部署至关重要。上下文稀疏性展示了潜力，但因活跃神经元的并集迅速逼近密集计算，难以扩展至大批次规模。我们引入Polar稀疏性，揭示了在扩展批次规模和序列长度时，稀疏性重要性从MLP层向注意力层的转变。尽管MLP层在批处理下变得更高效，但其稀疏性消失。相比之下，注意力层在扩展时成本增加，但头部稀疏性保持稳定且与批次无关。我们开发了硬件高效的稀疏感知GPU内核，针对选择性MLP和注意力计算，为OPT、LLaMA-2 & 3等模型在各种批次规模和序列长度下提供了高达【数学公式】的端到端加速，且不影响准确性。据我们所知，这是首个证明上下文稀疏性可有效扩展至大批次规模的工作，通过极小改动实现显著推理加速，使Polar稀疏性适用于大规模高吞吐量的LLM部署系统。我们的代码可在以下链接获取：https://github.com/susavlsh10/Polar-Sparsity。

> Accelerating large language model (LLM) inference is critical for real-world deployments requiring high throughput and low latency. Contextual sparsity, where each token dynamically activates only a small subset of the model parameters, shows promise but does not scale to large batch sizes due to union of active neurons quickly approaching dense computation. We introduce Polar Sparsity, highlighting a key shift in sparsity importance from MLP to Attention layers as we scale batch size and sequence length. While MLP layers become more compute-efficient under batching, their sparsity vanishes. In contrast, attention becomes increasingly more expensive at scale, while their head sparsity remains stable and batch-invariant. We develop hardware-efficient, sparsity-aware GPU kernels for selective MLP and Attention computations, delivering up to \(2.2\times\) end-to-end speedups for models like OPT, LLaMA-2 \& 3, across various batch sizes and sequence lengths without compromising accuracy. To our knowledge, this is the first work to demonstrate that contextual sparsity can scale effectively to large batch sizes, delivering substantial inference acceleration with minimal changes, making Polar Sparsity practical for large-scale, high-throughput LLM deployment systems. Our code is available at: https://github.com/susavlsh10/Polar-Sparsity.

[Arxiv](https://arxiv.org/abs/2505.14884)