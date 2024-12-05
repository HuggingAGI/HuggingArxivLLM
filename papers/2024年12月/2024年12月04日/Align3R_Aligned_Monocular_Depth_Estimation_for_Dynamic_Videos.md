# Align3R：针对动态视频的对齐式单目深度估计

发布时间：2024年12月04日

`其他` `深度估计`

> Align3R: Aligned Monocular Depth Estimation for Dynamic Videos

# 摘要

> 摘要：单目深度估计方法的最新进展虽能实现单视图图像的高质量深度估计，却难以在不同帧间得出一致的视频深度。近期的研究通过采用视频扩散模型，依据输入视频生成视频深度来应对此问题，然而这种方法训练成本高，且只能产生无相机姿态的尺度不变深度值。本文提出了一种名为 Align3R 的新颖视频深度估计方法，用于估算动态视频的时间一致深度图。其核心思路是借助最新的 DUSt3R 模型来对齐不同时间步的估计单目深度图。首先，针对动态场景，以额外的估计单目深度作为输入对 DUSt3R 模型进行微调。接着，应用优化来重建深度图和相机姿态。大量实验表明，Align3R 能为单目视频估计出一致的视频深度和相机姿态，性能优于基准方法。

> 
Abstract:Recent developments in monocular depth estimation methods enable high-quality depth estimation of single-view images but fail to estimate consistent video depth across different frames. Recent works address this problem by applying a video diffusion model to generate video depth conditioned on the input video, which is training-expensive and can only produce scale-invariant depth values without camera poses. In this paper, we propose a novel video-depth estimation method called Align3R to estimate temporal consistent depth maps for a dynamic video. Our key idea is to utilize the recent DUSt3R model to align estimated monocular depth maps of different timesteps. First, we fine-tune the DUSt3R model with additional estimated monocular depth as inputs for the dynamic scenes. Then, we apply optimization to reconstruct both depth maps and camera poses. Extensive experiments demonstrate that Align3R estimates consistent video depth and camera poses for a monocular video with superior performance than baseline methods.
    

[Arxiv](https://arxiv.org/pdf/2412.03079)