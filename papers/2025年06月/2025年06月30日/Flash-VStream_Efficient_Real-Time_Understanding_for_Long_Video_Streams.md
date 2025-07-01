# # 闪流：长视频流的高效实时理解

发布时间：2025年06月30日

`LLM应用` `视频处理` `人工智能`

> Flash-VStream: Efficient Real-Time Understanding for Long Video Streams

# 摘要

> 得益于大型语言模型和跨模态对齐技术的突破，现有的多模态大语言模型在图像和短视频理解方面表现优异。然而，长视频处理仍面临挑战，其长上下文特性带来了显著的计算和内存开销。目前大多数研究将长视频与短视频采用相同处理方式，这不仅效率低下，也难以推广至更长视频。针对这一问题，我们提出Flash-VStream——一款高效视频语言模型，能够处理超长视频并实时响应用户查询。特别地，我们设计了闪存模块，包含低容量上下文内存和高容量增强内存：前者聚合长上下文时间信息并建模信息密度分布，后者根据该分布检索详细空间信息。相比现有模型，Flash-VStream显著降低了推理延迟。在EgoSchema、MLVU、LVBench、MVBench和Video-MME等多个长视频和综合视频基准上的实验，充分验证了我们方法的最先进性能和卓越效率。代码已开源：https://github.com/IVGSZ/Flash-VStream。

> Benefiting from the advances in large language models and cross-modal alignment, existing multimodal large language models have achieved prominent performance in image and short video understanding. However, the understanding of long videos is still challenging, as their long-context nature results in significant computational and memory overhead. Most existing work treats long videos in the same way as short videos, which is inefficient for real-world applications and hard to generalize to even longer videos. To address these issues, we propose Flash-VStream, an efficient video language model capable of processing extremely long videos and responding to user queries in real time. Particularly, we design a Flash Memory module, containing a low-capacity context memory to aggregate long-context temporal information and model the distribution of information density, and a high-capacity augmentation memory to retrieve detailed spatial information based on this distribution. Compared to existing models, Flash-VStream achieves significant reductions in inference latency. Extensive experiments on long video benchmarks and comprehensive video benchmarks, i.e., EgoSchema, MLVU, LVBench, MVBench and Video-MME, demonstrate the state-of-the-art performance and outstanding efficiency of our method. Code is available at https://github.com/IVGSZ/Flash-VStream.

[Arxiv](https://arxiv.org/abs/2506.23825)