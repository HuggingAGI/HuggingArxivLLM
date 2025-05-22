# 驾驭本地大型语言模型：实证结果与对AI PC的启示

发布时间：2025年05月20日

`LLM应用` `边缘计算` `隐私保护`

> Harnessing Large Language Models Locally: Empirical Results and Implications for AI PC

# 摘要

> 随着模型进展和硬件改进的推动，大型语言模型 (LLMs) 在边缘设备上的日益增多的部署为隐私保护带来了显著优势。然而，这些设备端的 LLMs 由于模型容量的缩减和必要的压缩技术，本质上面临性能瓶颈。为了解决这一问题，我们提出了一套系统性的方法，涵盖模型能力、开发效率和系统资源，用于评估设备端 LLMs。我们的全面评估涵盖了从 0.5B 到 14B 参数的模型，以及在普通笔记本电脑上应用的七种后训练量化 (PTQ) 方法，得出了几个关键见解：1) 系统级指标表现出与有效每权重比特数 (BPW) 近乎线性的关系。2) 存在一个约 3.5 有效 BPW 的实际阈值，超过该阈值的较大模型在低比特量化下始终优于使用更高比特精度的小型模型。3) 低 BPW 的量化会导致轻微的精度损失，但能带来显著的内存节省。4) CPU 上的功耗由底层实现细节决定，其中计算密集型操作比内存密集型操作消耗更多电量。这些发现为在资源受限的边缘设备上高效部署和优化配置 LLMs 提供了关键见解和实用指南。我们的代码库可在 https://github.com/simmonssong/LLMOnDevice 获取。

> The increasing deployment of Large Language Models (LLMs) on edge devices, driven by model advancements and hardware improvements, offers significant privacy benefits. However, these on-device LLMs inherently face performance limitations due to reduced model capacity and necessary compression techniques. To address this, we introduce a systematic methodology -- encompassing model capability, development efficiency, and system resources -- for evaluating on-device LLMs. Our comprehensive evaluation, encompassing models from 0.5B to 14B parameters and seven post-training quantization (PTQ) methods on commodity laptops, yields several critical insights: 1) System-level metrics exhibit near-linear scaling with effective bits-per-weight (BPW). 2) A practical threshold exists around $\sim$3.5 effective BPW, larger models subjected to low-bit quantization consistently outperform smaller models utilizing higher bit-precision. 3) Quantization with low BPW incurs marginal accuracy loss but significant memory savings. 4) Determined by low-level implementation specifics power consumption on CPU, where computation-intensive operations spend more power than memory-intensive ones. These findings offer crucial insights and practical guidelines for the efficient deployment and optimized configuration of LLMs on resource-constrained edge devices. Our codebase is available at https://github.com/simmonssong/LLMOnDevice.

[Arxiv](https://arxiv.org/abs/2505.15030)