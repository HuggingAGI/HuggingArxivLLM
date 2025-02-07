# MaxInfo: 基于最大体积的无训练关键帧选择方法，提升视频理解能力

发布时间：2025年02月05日

`LLM应用

**理由**：该论文主要讨论了一种改进视频大语言模型（VLLMs）输入表示质量的方法（MaxInfo），并展示了其在多个基准测试中的性能提升。虽然涉及视频处理，但其核心是优化大语言模型的输入表示，属于大语言模型在实际应用中的改进和优化，因此应归类为LLM应用。` `视频分析` `人工智能`

> MaxInfo: A Training-Free Key-Frame Selection Method Using Maximum Volume for Enhanced Video Understanding

# 摘要

> 现代视频大语言模型（VLLMs）通常采用均匀帧采样来理解视频，但由于帧冗余和视频内容的变化，这种方法往往难以捕捉关键信息。我们提出了MaxInfo，一种基于最大体积原理的无训练方法，能够从输入视频中筛选并保留最具代表性的帧。通过最大化所选嵌入的几何体积，MaxInfo确保所选帧覆盖嵌入空间中最具信息量的区域，既减少了冗余，又保持了多样性。这一方法显著提升了输入表示的质量，并在多个基准测试中改善了长视频理解性能。例如，MaxInfo在LongVideoBench上提升了3.28%，在EgoSchema上为LLaVA-Video-7B提升了6.4%，为LLaVA-Video-72B提升了3.47%。该方法实现简单，无需额外训练即可与现有VLLMs无缝集成，是传统均匀采样方法的实用且高效的替代方案。

> Modern Video Large Language Models (VLLMs) often rely on uniform frame sampling for video understanding, but this approach frequently fails to capture critical information due to frame redundancy and variations in video content. We propose MaxInfo, a training-free method based on the maximum volume principle, which selects and retains the most representative frames from the input video. By maximizing the geometric volume formed by selected embeddings, MaxInfo ensures that the chosen frames cover the most informative regions of the embedding space, effectively reducing redundancy while preserving diversity. This method enhances the quality of input representations and improves long video comprehension performance across benchmarks. For instance, MaxInfo achieves a 3.28% improvement on LongVideoBench and a 6.4% improvement on EgoSchema for LLaVA-Video-7B. It also achieves a 3.47% improvement for LLaVA-Video-72B. The approach is simple to implement and works with existing VLLMs without the need for additional training, making it a practical and effective alternative to traditional uniform sampling methods.

[Arxiv](https://arxiv.org/abs/2502.03183)