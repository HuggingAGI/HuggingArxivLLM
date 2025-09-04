# # 通过透明近数据处理增强面向LLM推理的CXL内存有效带宽

发布时间：2025年09月03日

`其他` `基础理论`

> Amplifying Effective CXL Memory Bandwidth for LLM Inference via Transparent Near-Data Processing

# 摘要

> 大型语言模型（LLM）的推理性能因用于容量扩展的CXL内存带宽有限而受限。为此，我们提出CXL-NDP——一种透明的近数据处理架构，无需修改CXL.mem接口或AI模型，就能显著提升CXL的有效带宽。CXL-NDP集成了精度可扩展的位平面布局以实现动态量化，并在CXL设备内部直接对权重和KV缓存进行透明无损压缩。在端到端服务场景下，CXL-NDP可将吞吐量提升43%，最大上下文长度延长87%，KV缓存占用减少46.9%，且不会损失精度。硬件综合结果表明，CXL-NDP的硅片面积适中，这为生成式AI基础设施采用高效、可扩展的CXL内存降低了门槛。

> Large language model (LLM) inference is bottlenecked by the limited bandwidth of CXL-based memory used for capacity expansion. We introduce CXL-NDP, a transparent near-data processing architecture that amplifies effective CXL bandwidth without requiring changes to the CXL.mem interface or AI models. CXL-NDP integrates a precision-scalable bit-plane layout for dynamic quantization with transparent lossless compression of weights and KV caches directly within the CXL device. In end-to-end serving, CXL-NDP improves throughput by 43%, extends the maximum context length by 87%, and reduces the KV cache footprint by 46.9% without accuracy loss. Hardware synthesis confirms its practicality with a modest silicon footprint, lowering the barrier for adopting efficient, scalable CXL-based memory in generative AI infrastructure.

[Arxiv](https://arxiv.org/abs/2509.03377)