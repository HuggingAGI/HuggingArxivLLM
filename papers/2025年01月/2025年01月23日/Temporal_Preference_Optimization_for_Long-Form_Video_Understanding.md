# 长视频理解中的时间偏好优化

发布时间：2025年01月23日

`LLM应用

**理由**：这篇论文主要讨论了如何通过时间偏好优化（TPO）框架来提升视频大型多模态模型（video-LMMs）的时间定位能力。虽然涉及多模态模型，但其核心是优化和提升模型在特定任务（长视频时间定位）上的性能，属于LLM在实际应用中的改进和优化，因此归类为LLM应用。` `视频理解` `时间定位`

> Temporal Preference Optimization for Long-Form Video Understanding

# 摘要

> 尽管视频大型多模态模型（video-LMMs）取得了显著进展，但在长视频中实现精准的时间定位仍是现有模型的一大挑战。为此，我们提出了时间偏好优化（TPO），一种创新的训练后框架，通过偏好学习提升video-LMMs的时间定位能力。TPO采用自训练策略，利用两种粒度的偏好数据集——局部时间定位（聚焦特定视频片段）和全面时间定位（捕捉整个视频序列的时间依赖关系）——帮助模型区分精准与不准确的时间响应。通过优化这些偏好数据集，TPO显著提升了时间理解能力，同时减少了对人工标注数据的依赖。在LongVideoBench、MLVU和Video-MME三个长视频理解基准测试上的广泛实验表明，TPO在两个顶尖video-LMMs上表现卓越。其中，LLaVA-Video-TPO在Video-MME基准测试中脱颖而出，成为领先的7B模型，彰显了TPO作为长视频时间推理高效解决方案的巨大潜力。项目页面：https://ruili33.github.io/tpo_website。

> Despite significant advancements in video large multimodal models (video-LMMs), achieving effective temporal grounding in long-form videos remains a challenge for existing models. To address this limitation, we propose Temporal Preference Optimization (TPO), a novel post-training framework designed to enhance the temporal grounding capabilities of video-LMMs through preference learning. TPO adopts a self-training approach that enables models to differentiate between well-grounded and less accurate temporal responses by leveraging curated preference datasets at two granularities: localized temporal grounding, which focuses on specific video segments, and comprehensive temporal grounding, which captures extended temporal dependencies across entire video sequences. By optimizing on these preference datasets, TPO significantly enhances temporal understanding while reducing reliance on manually annotated data. Extensive experiments on three long-form video understanding benchmarks--LongVideoBench, MLVU, and Video-MME--demonstrate the effectiveness of TPO across two state-of-the-art video-LMMs. Notably, LLaVA-Video-TPO establishes itself as the leading 7B model on the Video-MME benchmark, underscoring the potential of TPO as a scalable and efficient solution for advancing temporal reasoning in long-form video understanding. Project page: https://ruili33.github.io/tpo_website.

[Arxiv](https://arxiv.org/abs/2501.13919)