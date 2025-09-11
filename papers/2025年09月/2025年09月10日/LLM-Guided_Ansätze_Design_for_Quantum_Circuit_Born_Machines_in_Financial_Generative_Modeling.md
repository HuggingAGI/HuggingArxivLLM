# 金融生成建模中量子电路玻恩机的LLM引导拟设设计

发布时间：2025年09月10日

`LLM应用` `金融科技`

> LLM-Guided Ansätze Design for Quantum Circuit Born Machines in Financial Generative Modeling

# 摘要

> 量子电路玻恩机（QCBMs）驱动的量子生成建模为实现实际量子优势展现出巨大潜力。然而，设计兼具表达能力与硬件效率的量子线路（ansätze）仍是一大核心挑战，尤其在嘈杂中尺度量子（NISQ）设备上。为此，我们提出一种基于提示的框架，借助大型语言模型（LLMs）生成硬件适配的QCBM架构。提示内容根据量子比特连接性、门错误率及硬件拓扑动态调整，同时结合Kullback-Leibler（KL）散度、电路深度和有效性等指标进行迭代反馈，持续优化电路设计。我们在日本政府债券（JGB）利率日波动的金融建模任务中对该方法进行了验证。结果显示，在12量子比特的真实IBM量子硬件上，LLM生成的量子线路不仅深度显著降低，生成性能也远超标准基线。这些发现不仅证实了LLM驱动量子架构搜索的实用价值，更为构建适用于近期量子设备的稳健可部署生成模型指明了方向。

> Quantum generative modeling using quantum circuit Born machines (QCBMs) shows promising potential for practical quantum advantage. However, discovering ansätze that are both expressive and hardware-efficient remains a key challenge, particularly on noisy intermediate-scale quantum (NISQ) devices. In this work, we introduce a prompt-based framework that leverages large language models (LLMs) to generate hardware-aware QCBM architectures. Prompts are conditioned on qubit connectivity, gate error rates, and hardware topology, while iterative feedback, including Kullback-Leibler (KL) divergence, circuit depth, and validity, is used to refine the circuits. We evaluate our method on a financial modeling task involving daily changes in Japanese government bond (JGB) interest rates. Our results show that the LLM-generated ansätze are significantly shallower and achieve superior generative performance compared to the standard baseline when executed on real IBM quantum hardware using 12 qubits. These findings demonstrate the practical utility of LLM-driven quantum architecture search and highlight a promising path toward robust, deployable generative models for near-term quantum devices.

[Arxiv](https://arxiv.org/abs/2509.08385)