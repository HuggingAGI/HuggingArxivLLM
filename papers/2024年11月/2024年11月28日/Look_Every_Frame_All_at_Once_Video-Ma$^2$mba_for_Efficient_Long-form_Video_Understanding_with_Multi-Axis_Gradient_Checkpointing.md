# 一次性查看每一帧：利用 Video-Ma$^2$mba 与多轴梯度检查点实现高效的长格式视频理解

发布时间：2024年11月28日

`其他` `人工智能`

> Look Every Frame All at Once: Video-Ma$^2$mba for Efficient Long-form Video Understanding with Multi-Axis Gradient Checkpointing

# 摘要

> 随着视频数据的规模与复杂性持续增大，由于现有的基于Transformer的大型多模态模型（LMMs）所带来的内存和计算需求呈二次方增长，高效处理长视频序列面临重大挑战。为应对这些难题，我们推出了 Video-Ma$^2$mba，这是一种在 Mamba-2 框架内融入状态空间模型（SSMs）、替代注意力机制的全新架构。如此一来，LMMs 在时间和内存需求上实现了线性扩展，让处理长时长视频内容成为可能。另外，我们引入多轴梯度检查点（MA-GC）方法来增强内存效率，该方法通过在多个计算轴上仅保留关键激活来策略性管理内存。相比标准梯度检查点，我们的方法大幅降低了内存占用。实证分析显示，Video-Ma$^2$mba 能够在单个 GPU 上处理大量视频序列——相当于数百万个标记或者超过两小时（帧率 1 FPS）的连续序列。通过对时间动态的精细捕捉，我们的模型在长视频理解任务中提升了响应的准确性和相关性，相比现有框架展现出显著优势。

> With the growing scale and complexity of video data, efficiently processing long video sequences poses significant challenges due to the quadratic increase in memory and computational demands associated with existing transformer-based Large Multi-modal Models (LMMs). To address these issues, we introduce Video-Ma$^2$mba, a novel architecture that incorporates State Space Models (SSMs) within the Mamba-2 framework, replacing the attention mechanisms. This allows the LMMs to scale linearly in terms of time and memory requirements, making it feasible to handle long-duration video content. Furthermore, we enhance the memory efficiency introducing the Multi-Axis Gradient Checkpointing (MA-GC) method, which strategically manages memory by retaining only essential activations across multiple computational axes. Our approach significantly reduces the memory footprint compared to standard gradient checkpointing. Empirical analyses show that Video-Ma$^2$mba can process extensive video sequences-equivalent to millions of tokens or over two hours of continuous sequences at 1 FPS-on a single GPU. By maintaining a detailed capture of temporal dynamics, our model improves the accuracy and relevance of responses in long video understanding tasks, demonstrating substantial advantages over existing frameworks.

[Arxiv](https://arxiv.org/abs/2411.19460)