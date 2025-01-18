# Vchitect-2.0: 并行Transformer助力视频扩散模型扩展

发布时间：2025年01月14日

`其他

理由：这篇论文主要讨论的是Vchitect-2.0，一种专为大规模文本到视频生成设计的并行变压器架构。虽然它涉及到文本到视频的生成，但主要内容集中在架构设计、训练框架和数据处理流程的优化上，并没有直接涉及Agent、RAG、LLM应用或LLM理论。因此，将其分类为“其他”更为合适。` `视频生成` `人工智能`

> Vchitect-2.0: Parallel Transformer for Scaling Up Video Diffusion Models

# 摘要

> 我们推出了 Vchitect-2.0，一种专为大规模文本到视频生成设计的并行变压器架构。Vchitect-2.0 系统具备几大亮点：(1) 通过创新的多模态扩散块，我们实现了文本描述与生成视频帧的精准对齐，同时确保序列间的时间连贯性。(2) 针对内存和计算瓶颈，我们提出了内存高效训练框架，结合混合并行性和内存优化技术，支持在分布式系统上高效训练长视频序列。(3) 此外，我们优化了数据处理流程，通过严格的注释和美学评估，构建了高质量的百万级训练数据集 Vchitect T2V DataVerse。大量实验证明，Vchitect-2.0 在视频质量、训练效率和可扩展性上均优于现有方法，是高保真视频生成的理想选择。

> We present Vchitect-2.0, a parallel transformer architecture designed to scale up video diffusion models for large-scale text-to-video generation. The overall Vchitect-2.0 system has several key designs. (1) By introducing a novel Multimodal Diffusion Block, our approach achieves consistent alignment between text descriptions and generated video frames, while maintaining temporal coherence across sequences. (2) To overcome memory and computational bottlenecks, we propose a Memory-efficient Training framework that incorporates hybrid parallelism and other memory reduction techniques, enabling efficient training of long video sequences on distributed systems. (3) Additionally, our enhanced data processing pipeline ensures the creation of Vchitect T2V DataVerse, a high-quality million-scale training dataset through rigorous annotation and aesthetic evaluation. Extensive benchmarking demonstrates that Vchitect-2.0 outperforms existing methods in video quality, training efficiency, and scalability, serving as a suitable base for high-fidelity video generation.

[Arxiv](https://arxiv.org/abs/2501.08453)