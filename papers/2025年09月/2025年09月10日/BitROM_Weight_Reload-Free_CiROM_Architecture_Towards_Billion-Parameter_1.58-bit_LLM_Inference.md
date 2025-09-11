# BitROM：免权重重载的CiROM架构——面向十亿参数级1.58位LLM推理

发布时间：2025年09月10日

`LLM应用` `工业与制造`

> BitROM: Weight Reload-Free CiROM Architecture Towards Billion-Parameter 1.58-bit LLM Inference

# 摘要

> 计算型只读存储器（CiROM）加速器通过消除运行时权重更新，为卷积神经网络（CNNs）带来了卓越的能效。然而，由于LLM参数规模庞大，CiROM在LLM上的可扩展性受到了根本性制约。以LLaMA系列最小的模型LLaMA-7B为例，即便采用先进CMOS工艺节点，其所需硅面积仍超过1000平方厘米。本文提出BitROM——首个基于CiROM的加速器，它通过与BitNet的1.58位量化模型协同设计突破了这一限制，让边缘端LLM推理既实用又高效。

BitROM的核心创新有三：1) 新型双向ROM阵列：单个晶体管可存储两个三值权重；2) 三模式本地累加器：专为三值权重计算量身优化；3) 集成解码-刷新（DR）嵌入式DRAM：支持片上KV缓存管理，大幅降低了解码时的外部存储器访问。此外，BitROM还集成基于LoRA的适配器，可高效支持多下游任务的迁移学习。

基于65nm CMOS工艺的评估显示，BitROM能效达20.8 TOPS/W，位密度为4967 kB/mm²，面积效率较以往数字CiROM设计提升了10倍。同时，DR嵌入式DRAM将外部DRAM访问量降低43.6%，进一步提升了LLM在边缘应用中的部署效率。

> Compute-in-Read-Only-Memory (CiROM) accelerators offer outstanding energy efficiency for CNNs by eliminating runtime weight updates. However, their scalability to Large Language Models (LLMs) is fundamentally constrained by their vast parameter sizes. Notably, LLaMA-7B - the smallest model in LLaMA series - demands more than 1,000 cm2 of silicon area even in advanced CMOS nodes. This paper presents BitROM, the first CiROM-based accelerator that overcomes this limitation through co-design with BitNet's 1.58-bit quantization model, enabling practical and efficient LLM inference at the edge. BitROM introduces three key innovations: 1) a novel Bidirectional ROM Array that stores two ternary weights per transistor; 2) a Tri-Mode Local Accumulator optimized for ternary-weight computations; and 3) an integrated Decode-Refresh (DR) eDRAM that supports on-die KV-cache management, significantly reducing external memory access during decoding. In addition, BitROM integrates LoRA-based adapters to enable efficient transfer learning across various downstream tasks. Evaluated in 65nm CMOS, BitROM achieves 20.8 TOPS/W and a bit density of 4,967 kB/mm2 - offering a 10x improvement in area efficiency over prior digital CiROM designs. Moreover, the DR eDRAM contributes to a 43.6% reduction in external DRAM access, further enhancing deployment efficiency for LLMs in edge applications.

[Arxiv](https://arxiv.org/abs/2509.08542)