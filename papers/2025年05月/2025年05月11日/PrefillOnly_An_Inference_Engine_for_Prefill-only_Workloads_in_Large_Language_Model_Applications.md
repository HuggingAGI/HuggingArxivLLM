# PrefillOnly：专为大型语言模型应用中预填充任务打造的推理引擎

发布时间：2025年05月11日

`LLM应用` `人工智能` `计算机科学`

> PrefillOnly: An Inference Engine for Prefill-only Workloads in Large Language Model Applications

# 摘要

> 除了 ChatGPT、GitHub Copilot 和 Cursor 这些典型的生成式应用，我们发现大型语言模型（LLMs）正在越来越多地被用于传统的判别任务，例如推荐、信用验证和数据标注。这些新兴场景的独特之处在于，LLM 仅生成一个输出标记，而非传统的长序列标记。我们将其称为“仅预填”工作负载。然而，现有的 LLM 引擎由于假设输出长度可变，未能充分利用仅预填工作负载的独特属性。在本文中，我们首次提出了 PrefillOnly，这是首个专门针对仅预填工作负载设计的 LLM 推理引擎，通过深度挖掘其特性显著提升了推理效率。首先，由于 PrefillOnly 仅生成一个标记，它只需存储最后一层计算的 KV 缓存，而非所有层的缓存。这极大减少了 LLM 推理所需的 GPU 内存占用，从而能够处理长输入，而无需采用降低吞吐量的跨 GPU KV 缓存并行化方案。其次，由于输出长度固定，PrefillOnly 可以在处理每个仅预填请求前精确预测其完成时间（JCT）。这使得可以实现高效的 JCT 感知调度策略，例如“剩余时间最短任务优先”。最终，PrefillOnly 每秒可以处理多达 4 倍的查询量，同时保持平均和 P99 延迟不变。

> Besides typical generative applications, like ChatGPT, GitHub Copilot, and Cursor, we observe an emerging trend that LLMs are increasingly used in traditional discriminative tasks, such as recommendation, credit verification, and data labeling. The key characteristic of these emerging use cases is that the LLM generates only a single output token, rather than an arbitrarily long sequence of tokens. We call this prefill-only workload. However, since existing LLM engines assume arbitrary output lengths, they fail to leverage the unique properties of prefill-only workloads. In this paper, we present PrefillOnly, the first LLM inference engine that improves the inference throughput and latency by fully embracing the properties of prefill-only workloads. First, since it generates only one token, PrefillOnly only needs to store the KV cache of only the last computed layer, rather than of all layers. This drastically reduces the GPU memory footprint of LLM inference and allows handling long inputs without using solutions that reduces throughput, such as cross-GPU KV cache parallelization. Second, because the output length is fixed, rather than arbitrary, PrefillOnly can precisely determine the job completion time (JCT) of each prefill-only request before it starts. This enables efficient JCT-aware scheduling policies such as shortest remaining job first. PrefillOnly can process upto 4x larger queries per second without inflating average and P99 latency.

[Arxiv](https://arxiv.org/abs/2505.07203)