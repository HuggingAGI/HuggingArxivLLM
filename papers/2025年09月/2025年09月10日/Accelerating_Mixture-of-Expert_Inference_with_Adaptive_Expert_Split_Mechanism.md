# 基于自适应专家拆分机制加速混合专家推理

发布时间：2025年09月10日

`LLM应用` `基础理论`

> Accelerating Mixture-of-Expert Inference with Adaptive Expert Split Mechanism

# 摘要

> 混合专家模型（MoE）已成为现代大型语言模型（LLMs）的潜力架构。但海量参数带来了巨大的GPU内存（即显存，VRAM）需求，阻碍了其广泛应用。将专家参数卸载到CPU内存是缓解MoE推理显存压力的有效手段。现有方法通常在显存中缓存少量专家，并在推理时从内存动态预取，然而缓存命中率低和专家加载延迟高导致推理速度大幅下降。本研究提出MoEpic——一种具备新型专家分割机制的高效MoE推理系统。具体来说，每个专家被垂直拆分为顶部段和底部段。MoEpic缓存热门专家的顶部段，在有限显存预算下能存储更多专家，进而提高缓存命中率。在每层推理时，MoEpic会预测并预取下一层将要激活的专家。由于缓存专家的顶部段无需重新获取，加载时间得以缩短，从而实现高效的传输-计算重叠。不过，MoEpic的性能很大程度上取决于缓存配置（即每层的显存预算和专家分割比例）。为此，我们提出基于不动点迭代的分治算法，用于自适应缓存配置。在主流MoE大型语言模型上的大量实验显示，MoEpic能节省约一半的GPU成本，同时推理延迟较基线方法降低37.51%-65.73%。

> Mixture-of-Experts (MoE) has emerged as a promising architecture for modern large language models (LLMs). However, massive parameters impose heavy GPU memory (i.e., VRAM) demands, hindering the widespread adoption of MoE LLMs. Offloading the expert parameters to CPU RAM offers an effective way to alleviate the VRAM requirements for MoE inference. Existing approaches typically cache a small subset of experts in VRAM and dynamically prefetch experts from RAM during inference, leading to significant degradation in inference speed due to the poor cache hit rate and substantial expert loading latency. In this work, we propose MoEpic, an efficient MoE inference system with a novel expert split mechanism. Specifically, each expert is vertically divided into two segments: top and bottom. MoEpic caches the top segment of hot experts, so that more experts will be stored under the limited VRAM budget, thereby improving the cache hit rate. During each layer's inference, MoEpic predicts and prefetches the activated experts for the next layer. Since the top segments of cached experts are exempt from fetching, the loading time is reduced, which allows efficient transfer-computation overlap. Nevertheless, the performance of MoEpic critically depends on the cache configuration (i.e., each layer's VRAM budget and expert split ratio). To this end, we propose a divide-and-conquer algorithm based on fixed-point iteration for adaptive cache configuration. Extensive experiments on popular MoE LLMs demonstrate that MoEpic can save about half of the GPU cost, while lowering the inference latency by about 37.51%-65.73% compared to the baselines.

[Arxiv](https://arxiv.org/abs/2509.08342)