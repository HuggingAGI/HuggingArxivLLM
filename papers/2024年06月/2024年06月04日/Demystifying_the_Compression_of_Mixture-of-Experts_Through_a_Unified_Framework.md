# 揭秘混合专家模型压缩：统一框架下的探索

发布时间：2024年06月04日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLM）中的混合专家（MoE）方法的压缩技术，这是对LLM内部结构和优化方法的理论研究。论文提出了一种新的统一框架，整合了主流压缩技术，并系统地探讨了MoE的压缩方法，这属于对LLM理论层面的深入分析和改进，而非直接的应用或Agent行为研究。因此，它更适合归类于LLM理论。` `人工智能` `模型压缩`

> Demystifying the Compression of Mixture-of-Experts Through a Unified Framework

# 摘要

> 大型语言模型的规模扩展已革新了多个领域的表现，但模型规模的不断增长给实际部署带来了挑战。混合专家（MoE）方法通过动态激活部分专家，既降低了计算成本又保持了高性能。尽管如此，MoE也带来了参数冗余和通信开销。虽然已有多种压缩技术用于减少密集模型的冗余，但MoE的压缩研究仍显不足。我们提出了一种前沿的统一框架，它不仅整合了主流压缩技术，还系统地探讨了MoE的压缩方法。该框架采用两种策略：专家瘦身和专家修剪，前者压缩单个专家，后者移除结构模块。在此基础上，我们引入了层丢弃和块丢弃等激进技术，以大规模消除冗余。基于这些发现，我们提供了一套全面的指南，帮助实践者有效压缩MoE。实验结果显示，我们的方法在保持92%以上性能的同时，实现了6.05倍的加速和仅20.0GB的内存使用。

> Scaling large language models has revolutionized the performance across diverse domains, yet the continual growth in model size poses significant challenges for real-world deployment. The Mixture of Experts (MoE) approach addresses this by dynamically selecting and activating only a subset of experts, significantly reducing computational costs while maintaining high performance. However, MoE introduces potential redundancy (e.g., parameters) and extra costs (e.g., communication overhead). Despite numerous compression techniques developed for mitigating the redundancy in dense models, the compression of MoE remains under-explored. We first bridge this gap with a cutting-edge unified framework that not only seamlessly integrates mainstream compression methods but also helps systematically understand MoE compression. This framework approaches compression from two perspectives: Expert Slimming which compresses individual experts and Expert Trimming which removes structured modules. Within this framework, we explore the optimization space unexplored by existing methods,and further introduce aggressive Expert Trimming techniques, i.e., Layer Drop and Block Drop, to eliminate redundancy at larger scales. Based on these insights,we present a comprehensive recipe to guide practitioners in compressing MoE effectively. Extensive experimental results demonstrate the effectiveness of the compression methods under our framework and the proposed recipe, achieving a 6.05x speedup and only 20.0GB memory usage while maintaining over 92% of performance on Mixtral-8x7B.

![揭秘混合专家模型压缩：统一框架下的探索](../../../paper_images/2406.02500/x1.png)

![揭秘混合专家模型压缩：统一框架下的探索](../../../paper_images/2406.02500/x2.png)

![揭秘混合专家模型压缩：统一框架下的探索](../../../paper_images/2406.02500/x3.png)

![揭秘混合专家模型压缩：统一框架下的探索](../../../paper_images/2406.02500/x4.png)

![揭秘混合专家模型压缩：统一框架下的探索](../../../paper_images/2406.02500/x5.png)

![揭秘混合专家模型压缩：统一框架下的探索](../../../paper_images/2406.02500/x6.png)

![揭秘混合专家模型压缩：统一框架下的探索](../../../paper_images/2406.02500/x7.png)

![揭秘混合专家模型压缩：统一框架下的探索](../../../paper_images/2406.02500/x8.png)

![揭秘混合专家模型压缩：统一框架下的探索](../../../paper_images/2406.02500/x9.png)

![揭秘混合专家模型压缩：统一框架下的探索](../../../paper_images/2406.02500/x10.png)

![揭秘混合专家模型压缩：统一框架下的探索](../../../paper_images/2406.02500/x11.png)

![揭秘混合专家模型压缩：统一框架下的探索](../../../paper_images/2406.02500/x12.png)

![揭秘混合专家模型压缩：统一框架下的探索](../../../paper_images/2406.02500/x13.png)

![揭秘混合专家模型压缩：统一框架下的探索](../../../paper_images/2406.02500/x14.png)

![揭秘混合专家模型压缩：统一框架下的探索](../../../paper_images/2406.02500/x15.png)

![揭秘混合专家模型压缩：统一框架下的探索](../../../paper_images/2406.02500/x16.png)

![揭秘混合专家模型压缩：统一框架下的探索](../../../paper_images/2406.02500/x17.png)

![揭秘混合专家模型压缩：统一框架下的探索](../../../paper_images/2406.02500/x18.png)

[Arxiv](https://arxiv.org/abs/2406.02500)