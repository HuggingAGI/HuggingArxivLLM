# MambaMia：基于状态空间模型的压缩方法，助力大型多模态模型实现高效视频理解

发布时间：2025年06月16日

`LLM应用` `视频处理` `计算机视觉`

> MambaMia: A State-Space-Model-Based Compression for Efficient Video Understanding in Large Multimodal Models

# 摘要

> 我们提出了一种高效框架，用于在将多帧视频特征输入大型多模态模型前进行压缩，有效缓解长视频或密集视频带来的严重token爆炸问题。我们的设计采用了一种配备门控跳跃连接和可学习加权平均池化机制的双向状态空间块，并定期插入学习查询。这种结构能够在空间和时间维度上实现层次化下采样，在保持性能的同时以成本效益高的方式压缩数据。在长视频和密集视频理解任务中，我们的方法在与现有最先进模型的竞争中表现出色，同时大幅降低了token预算。值得注意的是，将我们的状态空间块替换为传统Transformer会导致性能大幅下降，突显了状态空间建模在压缩多帧视频数据方面的优势。我们的框架注重资源效率，适用于实际部署。我们在多个基准测试中验证了其扩展性和通用性，实现了高效资源利用与全面视频理解的双重目标。

> We propose an efficient framework to compress multiple video-frame features before feeding them into large multimodal models, thereby mitigating the severe token explosion arising from long or dense videos. Our design leverages a bidirectional state-space-based block equipped with a gated skip connection and a learnable weighted-average pooling mechanism applied to periodically inserted learned queries. This structure enables hierarchical downsampling across both spatial and temporal dimensions, preserving performance in a cost-effective manner. Across challenging long and dense video understanding tasks, our approach demonstrates competitive results against state-of-the-art models, while significantly reducing overall token budget. Notably, replacing our proposed state-space block with a conventional Transformer results in substantial performance degradation, highlighting the advantages of state-space modeling for effectively compressing multi-frame video data. Our framework emphasizes resource-conscious efficiency, making it practical for real-world deployments. We validate its scalability and generality across multiple benchmarks, achieving the dual objectives of efficient resource usage and comprehensive video understanding.

[Arxiv](https://arxiv.org/abs/2506.13564)