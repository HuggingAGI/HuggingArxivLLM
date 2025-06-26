# 破损视频数据集：AI生成视频中细粒度伪影定位基准

发布时间：2025年06月24日

`LLM应用` `视频处理` `视频质量评估`

> BrokenVideos: A Benchmark Dataset for Fine-Grained Artifact Localization in AI-Generated Videos

# 摘要

> 深度生成模型的最新进展为视频生成领域带来了显著的突破，但AI生成视频的保真度仍有待提升。合成内容常出现视觉伪影，如时间不一致的运动、物理上不合理的轨迹、不自然的对象变形和局部模糊，这些问题削弱了视频的真实感和用户信任度。准确检测并定位这些伪影对于实现自动化质量控制以及指导改进生成模型的开发至关重要。然而，当前的研究社区缺乏专门用于AI生成视频中伪影定位的综合性基准测试。现有数据集要么局限于视频或帧级别检测，要么缺乏用于评估定位方法所需精细的空间标注。为了解决这一研究空白，我们推出了BrokenVideos，这是一个包含3,254个AI生成视频的基准数据集，每个视频都附有经过精心标注的像素级遮罩，突出显示视觉损坏区域。每项标注都经过详细的人工检查，以确保高质量的地面真实数据。我们的实验表明，在BrokenVideos上训练最先进的伪影检测模型和多模态大型语言模型（MLLMs）能够显著提升它们定位损坏区域的能力。通过广泛的评估，我们证明BrokenVideos为生成视频模型的伪影定位研究建立了一个关键的研究基准。该数据集可访问地址为：https://broken-video-detection-datetsets.github.io/Broken-Video-Detection-Datasets.github.io/。

> Recent advances in deep generative models have led to significant progress in video generation, yet the fidelity of AI-generated videos remains limited. Synthesized content often exhibits visual artifacts such as temporally inconsistent motion, physically implausible trajectories, unnatural object deformations, and local blurring that undermine realism and user trust. Accurate detection and spatial localization of these artifacts are crucial for both automated quality control and for guiding the development of improved generative models. However, the research community currently lacks a comprehensive benchmark specifically designed for artifact localization in AI generated videos. Existing datasets either restrict themselves to video or frame level detection or lack the fine-grained spatial annotations necessary for evaluating localization methods. To address this gap, we introduce BrokenVideos, a benchmark dataset of 3,254 AI-generated videos with meticulously annotated, pixel-level masks highlighting regions of visual corruption. Each annotation is validated through detailed human inspection to ensure high quality ground truth. Our experiments show that training state of the art artifact detection models and multi modal large language models (MLLMs) on BrokenVideos significantly improves their ability to localize corrupted regions. Through extensive evaluation, we demonstrate that BrokenVideos establishes a critical foundation for benchmarking and advancing research on artifact localization in generative video models. The dataset is available at: https://broken-video-detection-datetsets.github.io/Broken-Video-Detection-Datasets.github.io/.

[Arxiv](https://arxiv.org/abs/2506.20103)