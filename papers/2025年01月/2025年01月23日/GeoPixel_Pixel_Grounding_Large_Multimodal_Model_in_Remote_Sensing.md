# GeoPixel: 遥感中的像素级接地大型多模态模型

发布时间：2025年01月23日

`LLM应用

**理由**：这篇论文主要讨论了多模态大模型（LMMs）在遥感（RS）领域的应用，特别是提出了一个名为GeoPixel的端到端高分辨率RS-LMM模型，用于像素级接地的视觉感知和对话生成。虽然论文涉及了多模态大模型的理论和架构设计，但其核心关注点在于如何将这些模型应用于遥感图像分析，并解决该领域中的具体问题（如高分辨率图像处理、细粒度视觉感知等）。因此，这篇论文更符合“LLM应用”这一分类。` `图像分析`

> GeoPixel: Pixel Grounding Large Multimodal Model in Remote Sensing

# 摘要

> # 摘要
多模态大模型（LMMs）的最新进展表明，细粒度接地是视觉理解和对话的关键。然而，这种优势在自然图像领域之外的应用有限，尤其是在遥感（RS）领域表现欠佳。高分辨率RS图像中的俯视视角、尺度变化和小物体给区域级理解带来了独特挑战。此外，缺乏细粒度的RS领域接地数据也限制了LMMs在RS中的对话能力发展。为此，我们提出了GeoPixel——首个支持像素级接地的端到端高分辨率RS-LMM。它通过在对话中生成交错掩码，实现了细粒度视觉感知，并支持高达4K高清分辨率的任意宽高比，非常适合高精度RS图像分析。为了支持RS图像中的接地对话生成（GCG），我们通过半自动化管道构建了视觉接地数据集GeoPixelD，利用为RS数据定制的标记集提示和空间先验，系统化控制数据生成过程。GeoPixel在像素级理解任务中表现卓越，在单目标和多目标分割任务中均超越了现有LMMs。通过方法消融研究，我们验证了架构中每个组件的有效性。代码和数据将公开发布。

> Recent advances in large multimodal models (LMMs) have recognized fine-grained grounding as an imperative factor of visual understanding and dialogue. However, the benefits of such representation in LMMs are limited to the natural image domain, and these models perform poorly for remote sensing (RS). The distinct overhead viewpoint, scale variation, and presence of small objects in high-resolution RS imagery present a unique challenge in region-level comprehension. Moreover, the development of the grounding conversation capability of LMMs within RS is hindered by the lack of granular, RS domain-specific grounded data. Addressing these limitations, we propose GeoPixel - the first end-to-end high resolution RS-LMM that supports pixel-level grounding. This capability allows fine-grained visual perception by generating interleaved masks in conversation. GeoPixel supports up to 4K HD resolution in any aspect ratio, ideal for high-precision RS image analysis. To support the grounded conversation generation (GCG) in RS imagery, we curate a visually grounded dataset GeoPixelD through a semi-automated pipeline that utilizes set-of-marks prompting and spatial priors tailored for RS data to methodically control the data generation process. GeoPixel demonstrates superior performance in pixel-level comprehension, surpassing existing LMMs in both single-target and multi-target segmentation tasks. Our methodological ablation studies validate the effectiveness of each component in the overall architecture. Our code and data will be publicly released.

[Arxiv](https://arxiv.org/abs/2501.13925)