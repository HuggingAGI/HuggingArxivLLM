# 量化-采样-验证：通过自适应边缘-云推测解码加速大型语言模型

发布时间：2025年07月01日

`其他` `边缘计算`

> Quantize-Sample-and-Verify: LLM Acceleration via Adaptive Edge-Cloud Speculative Decoding

# 摘要

> 边缘-云推测解码（SD）中，边缘设备借助小型语言模型（SLMs）生成草稿标记，这些标记由云端的大语言模型（LLMs）进行验证。然而，此类系统的主要瓶颈在于边缘与云端之间的有限通信带宽，这要求对传输的生成标记信息进行量化。本研究提出了一种新型的量化采样（Q-S）策略，确保输出分布与基于云端模型的分布一致，从而使验证后的标记与LLM直接生成的标记分布相匹配。我们开发了一个边缘-云SD的吞吐量模型，该模型明确考虑了通信延迟。基于此模型，我们提出了一种自适应机制，通过动态调整草稿长度和量化精度，以应对语义不确定性和信道条件，从而优化标记吞吐量。仿真结果表明，所提出的Q-S方法在实际的边缘-云部署场景中显著提升了解码效率。

> In edge-cloud speculative decoding (SD), edge devices equipped with small language models (SLMs) generate draft tokens that are verified by large language models (LLMs) in the cloud. A key bottleneck in such systems is the limited communication bandwidth between edge and cloud, which necessitates quantization of the information transmitted about generated tokens. In this work, we introduce a novel quantize-sample (Q-S) strategy that provably preserves the output distribution of the cloud-based model, ensuring that the verified tokens match the distribution of those that would have been generated directly by the LLM. We develop a throughput model for edge-cloud SD that explicitly accounts for communication latency. Leveraging this model, we propose an adaptive mechanism that optimizes token throughput by dynamically adjusting the draft length and quantization precision in response to both semantic uncertainty and channel conditions. Simulations demonstrate that the proposed Q-S approach significantly improves decoding efficiency in realistic edge-cloud deployment scenarios.

[Arxiv](https://arxiv.org/abs/2507.00605)