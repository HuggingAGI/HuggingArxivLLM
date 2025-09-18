# 基于门控残差标记化的密集视频理解

发布时间：2025年09月17日

`LLM应用` `教育科技`

> Dense Video Understanding with Gated Residual Tokenization

# 摘要

> 在视频理解中，高时间分辨率是捕捉细粒度细节的关键。但当前视频大型语言模型（VLLMs）及相关基准大多依赖低帧率采样（如均匀采样或关键帧选择），从而丢失了密集的时间信息。这种折中虽避免了逐帧token化的高昂成本（否则会造成冗余计算，且token数量随视频长度呈线性增长），但在讲座理解等任务中却无能为力：这类任务的信息几乎每一帧都有，且需要精确的时间对齐。为填补这一空白，我们提出密集视频理解（DVU），它通过降低token化时间和token开销，实现了高FPS视频的理解。现有基准也存在局限，其问答对（QA pairs）仅关注粗粒度的内容变化。为此，我们提出DIVE（密集信息视频评估）——首个专为密集时间推理打造的基准。为让DVU落地实用，我们提出门控残差token化（GRT）两阶段框架：（1）运动补偿跨门控token化通过像素级运动估计在token化时跳过静态区域，实现token数量和计算量的亚线性增长；（2）语义场景内token合并则融合场景中静态区域的token，在保留动态语义的同时进一步降低冗余。在DIVE上的实验显示，GRT不仅性能超过更大规模的VLLM基线模型，还能随FPS提升而正向扩展。这些结果不仅凸显了密集时间信息的关键作用，还证明GRT能高效、可扩展地实现高FPS视频理解。

> High temporal resolution is essential for capturing fine-grained details in video understanding. However, current video large language models (VLLMs) and benchmarks mostly rely on low-frame-rate sampling, such as uniform sampling or keyframe selection, discarding dense temporal information. This compromise avoids the high cost of tokenizing every frame, which otherwise leads to redundant computation and linear token growth as video length increases. While this trade-off works for slowly changing content, it fails for tasks like lecture comprehension, where information appears in nearly every frame and requires precise temporal alignment. To address this gap, we introduce Dense Video Understanding (DVU), which enables high-FPS video comprehension by reducing both tokenization time and token overhead. Existing benchmarks are also limited, as their QA pairs focus on coarse content changes. We therefore propose DIVE (Dense Information Video Evaluation), the first benchmark designed for dense temporal reasoning. To make DVU practical, we present Gated Residual Tokenization (GRT), a two-stage framework: (1) Motion-Compensated Inter-Gated Tokenization uses pixel-level motion estimation to skip static regions during tokenization, achieving sub-linear growth in token count and compute. (2) Semantic-Scene Intra-Tokenization Merging fuses tokens across static regions within a scene, further reducing redundancy while preserving dynamic semantics. Experiments on DIVE show that GRT outperforms larger VLLM baselines and scales positively with FPS. These results highlight the importance of dense temporal information and demonstrate that GRT enables efficient, scalable high-FPS video understanding.

[Arxiv](https://arxiv.org/abs/2509.14199)