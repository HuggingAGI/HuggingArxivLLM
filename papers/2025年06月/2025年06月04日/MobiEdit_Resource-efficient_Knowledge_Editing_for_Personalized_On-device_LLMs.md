# MobiEdit: 资源高效的设备端个性化LLM知识编辑方案

发布时间：2025年06月04日

`LLM应用

理由：这篇论文探讨了在移动设备上高效部署和个性化大型语言模型的方法，属于实际应用层面的优化和实现。` `移动设备` `智能助手`

> MobiEdit: Resource-efficient Knowledge Editing for Personalized On-device LLMs

# 摘要

> 大型语言模型（LLMs）在移动设备上的部署为智能助手等应用注入了强大动力。然而，在通用语料库上预训练的LLMs在处理个性化或未见过的查询时，常常会产生错误或过时的回答。知识编辑通过精准调整模型权重中的关键部分，解决了这一问题，同时保留了模型的通用知识。然而，传统知识编辑方法由于需要资源密集型的反向传播（BP）更新，难以在本地设备上实际应用。我们提出了MobiEdit，这是首个能在商用现货（COTS）移动设备上实现高效LLM个性化的移动知识编辑框架。通过采用量化仅前向梯度估计替代全精度BP，MobiEdit完美适配节能的移动神经处理单元（NPUs）。为提升梯度估计效率，我们还引入了两项创新优化：自适应成功的提前停止机制和跨步骤复用计算的前缀缓存。与传统方法相比，MobiEdit使30亿参数模型（Qwen2.5-3B-Instruct）在COTS移动设备上的实时编辑成为可能，且内存占用减少7.6倍，能耗减少14.7倍，延迟减少3.6倍。

> Large language models (LLMs) are deployed on mobile devices to power killer applications such as intelligent assistants. LLMs pre-trained on general corpora often hallucinate when handling personalized or unseen queries, leading to incorrect or outdated responses. Knowledge editing addresses this by identifying and adjusting a small crucial portion of model weights, without compromising the general knowledge. However, prior knowledge editing methods are impractical to run on local devices due to the resource-heavy backpropagation (BP) needed for updates. We present MobiEdit, the first mobile knowledge editing framework that enables efficient LLM personalization on commercial off-the-shelf (COTS) mobile devices. MobiEdit replaces full-precision BP with quantized forward-only gradient estimation, thus compatible with the energy-efficient mobile neural processing units (NPUs). MobiEdit replaces full-precision backpropagation with quantized forward-only gradient estimation, making it compatible with energy-efficient mobile NPUs. To further improve gradient estimation efficiency, we introduce two optimizations: an early stoping mechanism that adaptively terminates editing upon success and a prefix cache that reuses computation across steps. Our approach enables real-time editing of a 3B-parameter model (Qwen2.5-3B-Instruct) on COTS mobile devices with 7.6$\times$ less memory, 14.7 $\times$ less energy and 3.6$\times$ less latency compared to previous knowledge editing methods.

[Arxiv](https://arxiv.org/abs/2506.13772)