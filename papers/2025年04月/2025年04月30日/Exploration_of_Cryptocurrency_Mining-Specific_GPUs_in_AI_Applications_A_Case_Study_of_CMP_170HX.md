# 研究加密货币挖矿专用GPU在AI应用中的价值：以CMP 170HX为例

发布时间：2025年04月30日

`其他` `边缘计算` `轻量级AI推理`

> Exploration of Cryptocurrency Mining-Specific GPUs in AI Applications: A Case Study of CMP 170HX

# 摘要

> 本研究系统性地测试了开源社区提出的一种计算能力复用方案，该方案通过修改CUDA源代码，在NVIDIA CMP 170HX平台上禁用特定指令集（融合乘加指令）。实验结果验证了该方案的有效性，部分恢复了GPU在人工智能（AI）任务中的计算能力。通过开源GPU基准测试（OpenCL基准、mixbench）和AI基准测试（LLAMA-benchmark）进行的性能评估表明，其FP32浮点性能超过了原始能力的15倍，而大型语言模型在某些精度水平下的推理性能也提升了三倍以上。此外，基于硬件架构分析，本文提出了通过替代适应路径进一步提升计算利用率的理论假设。结合能效比和成本模型，评估了此类老旧GPU在边缘计算和轻量级AI推理场景中的回收价值。研究结果表明，合理复用挖矿GPU的剩余计算能力，不仅能够显著缓解电子垃圾带来的环境负担，还能为低成本计算场景提供经济高效的硬件解决方案。

> This study systematically tests a computational power reuse scheme proposed by the open source community disabling specific instruction sets (Fused Multiply Add instructions) through CUDA source code modifications on the NVIDIA CMP 170HX platform. Experimental results validate the effectiveness of this approach, partially restoring the GPU's computational capabilities in artificial intelligence (AI) tasks. Performance evaluations using open-source GPU benchmarks (OpenCL benchmark, mixbench) and AI benchmarks (LLAMA-benchmark) reveal that its FP32 floating-point performance exceeds 15 times the original capability, while inference performance for certain precision levels in large language models surpasses threefold improvements. Furthermore, based on hardware architecture analysis, this paper proposes theoretical conjectures for further improving computational utilization through alternative adaptation pathways.Combining energy efficiency ratios and cost models, the recycling value of such obsolete GPUs in edge computing and lightweight AI inference scenarios is evaluated. The findings demonstrate that rationally reusing residual computational power from mining GPUs can significantly mitigate the environmental burden of electronic waste while offering cost-effective hardware solutions for low-budget computing scenarios.

[Arxiv](https://arxiv.org/abs/2505.03782)