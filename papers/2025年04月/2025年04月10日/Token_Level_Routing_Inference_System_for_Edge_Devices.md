# # 边缘设备的Token级别路由推理系统
一种专为边缘设备设计的Token级别路由推理系统。

发布时间：2025年04月10日

`LLM应用` `人工智能` `边缘计算`

> Token Level Routing Inference System for Edge Devices

# 摘要

> 大型语言模型（LLM）的计算复杂度在边缘设备上的部署效率方面存在显著限制。相比之下，小型语言模型虽然具有更快的解码速度和更低的资源消耗，但常面临响应质量下降和幻觉问题。为解决这一权衡，协作解码作为一种有前景的解决方案应运而生，其中大型模型协助生成关键令牌。这种范式通过大型模型的有选择性干预，结合了两种模型的优点，实现了高质量推理，同时保持了小型模型的速度和效率。我们提出了一种新型协作解码推理系统，使小型模型能够在设备上进行推理，同时有选择地咨询基于云的大型模型以生成关键令牌。令人瞩目的是，该系统在 CommonsenseQA 上实现了 60% 的性能提升，仅在 M1 MacBook 上使用 0.5B 模型，且仅有不到 7% 的令牌生成上传到云端大型模型。

> The computational complexity of large language model (LLM) inference significantly constrains their deployment efficiency on edge devices. In contrast, small language models offer faster decoding and lower resource consumption but often suffer from degraded response quality and heightened susceptibility to hallucinations. To address this trade-off, collaborative decoding, in which a large model assists in generating critical tokens, has emerged as a promising solution. This paradigm leverages the strengths of both model types by enabling high-quality inference through selective intervention of the large model, while maintaining the speed and efficiency of the smaller model. In this work, we present a novel collaborative decoding inference system that allows small models to perform on-device inference while selectively consulting a cloud-based large model for critical token generation. Remarkably, the system achieves a 60% performance gain on CommonsenseQA using only a 0.5B model on an M1 MacBook, with under 7% of tokens generation uploaded to the large model in the cloud.

[Arxiv](https://arxiv.org/abs/2504.07878)