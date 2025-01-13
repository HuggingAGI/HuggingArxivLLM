# 利用EPD解耦技术高效服务大型多媒体模型

发布时间：2024年12月25日

`LLM应用

**理由**：这篇论文主要讨论了如何通过解耦编码、预填充和解码阶段来优化大型多模态模型（LMMs）的性能，特别是针对计算和内存开销的问题。虽然涉及多模态模型，但其核心是优化LLM在实际应用中的性能，因此应归类为LLM应用。` `人工智能` `多模态处理`

> Efficiently serving large multimedia models using EPD Disaggregation

# 摘要

> # 摘要
大型多模态模型（LMMs）通过处理图像、音频和视频等多种输入扩展了大型语言模型（LLMs），但代价是增加了多模态编码阶段，导致计算和内存开销增加。这一步骤将原始输入转换为标记化表示，从而在预填充阶段膨胀标记序列，对关键服务水平目标（SLOs）如首次标记时间（TTFT）和端到端吞吐量产生负面影响。我们提出了编码-预填充-解码（EPD）解耦框架，将编码、预填充和解码阶段分离到专用资源上。与当前将编码和预填充捆绑在一起的系统不同，我们的解耦方法缓解了内存瓶颈，减少了同步延迟，并支持灵活的批处理。具体来说，我们采用了一种新的多模态标记缓存机制，实现了多模态标记的异步传输，并引入了一个集成模块来优化EPD系统配置，最小化资源使用，同时最大化基于SLO的性能指标。对流行LMMs的实验评估显示，内存效率显著提高（编码阶段GPU内存减少高达15倍），支持高达22倍的批处理大小，每个请求的图像数量增加10倍，kv缓存大小增加2.2倍。此外，与不解耦的系统相比，端到端吞吐量显著提高（高达57%更好），延迟指标（TTFT降低高达71%）也有显著改善。我们的发现表明，EPD解耦在实现资源高效和高性能多模态推理方面具有巨大潜力。

> Large Multimodal Models (LMMs) extend Large Language Models (LLMs) by handling diverse inputs such as images, audio, and video, but at the cost of adding a multimodal encoding stage that increases both computational and memory overhead. This step helps convert raw inputs into tokenized representations that inflate the token sequence for the prefill phase, negatively impacting key Service Level Objectives (SLOs) like time to first token (TTFT) and end-to-end throughput. We introduce Encode-Prefill-Decode (EPD) Disaggregation, a novel framework that separates the encoding, prefill, and decode stages onto dedicated resources. Unlike current systems, which bundle encoding and prefill together, our disaggregation approach alleviates memory bottlenecks, mitigates synchronization delays, and supports flexible batching. Specifically, we employ a new caching mechanism for multimodal tokens, enabling asynchronous transfer of multimodal tokens and introduce an integrated module to find optimal config for EPD system and minimize resource usage while maximizing SLO-based performance metric. Experimental evaluations with popular LMMs show substantial gains in memory efficiency (up to 15$\times$ lesser for encoding-stage GPUs), that supports upto 22$\times$ higher batch sizes, 10$\times$ more number of images/ request, 2.2$\times$ higher kv cache size. Further, it leads to significant improvements in end-to-end throughput (up to 57\% better), and latency metrics (TTFT up to 71\% lower), compared to systems that do not disaggregate. Our findings underscore the potential of EPD disaggregation to enable resource-efficient and high-performance multimodal inference at scale.

[Arxiv](https://arxiv.org/abs/2501.05460)