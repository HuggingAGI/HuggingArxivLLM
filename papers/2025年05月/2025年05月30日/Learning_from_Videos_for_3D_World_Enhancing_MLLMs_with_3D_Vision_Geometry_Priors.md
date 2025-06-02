# 从视频学习构建三维世界：融合三维视觉几何先验增强多模态语言模型

发布时间：2025年05月30日

`LLM应用` `视频处理` `3D技术`

> Learning from Videos for 3D World: Enhancing MLLMs with 3D Vision Geometry Priors

# 摘要

> 此前的研究探讨了多模态大型语言模型（MLLMs）在通过解读视频理解3D场景中的应用。这些方法通常依赖于全面的3D数据输入，如点云或重建的鸟瞰图（BEV）地图。在我们的研究中，我们推动了这一领域的进步，增强了MLLMs直接从视频数据理解并推理3D空间的能力，无需额外的3D输入。我们提出了一种新颖且高效的方法，即视频-3D几何大型语言模型（VG LLM）。我们的方法采用了3D视觉几何编码器，从视频序列中提取3D先验信息。这些信息与视觉令牌结合后输入MLLM。大量实验表明，我们的方法在与3D场景理解和空间推理相关的各种任务中取得了显著改进，所有这些改进均直接从视频来源中学习而来。令人印象深刻的是，我们无需依赖显式3D数据输入的4B模型，在VSI-Bench评估中不仅与现有最先进方法相比取得了具有竞争力的结果，甚至超越了Gemini-1.5-Pro。

> Previous research has investigated the application of Multimodal Large Language Models (MLLMs) in understanding 3D scenes by interpreting them as videos. These approaches generally depend on comprehensive 3D data inputs, such as point clouds or reconstructed Bird's-Eye View (BEV) maps. In our research, we advance this field by enhancing the capability of MLLMs to understand and reason in 3D spaces directly from video data, without the need for additional 3D input. We propose a novel and efficient method, the Video-3D Geometry Large Language Model (VG LLM). Our approach employs a 3D visual geometry encoder that extracts 3D prior information from video sequences. This information is integrated with visual tokens and fed into the MLLM. Extensive experiments have shown that our method has achieved substantial improvements in various tasks related to 3D scene understanding and spatial reasoning, all directly learned from video sources. Impressively, our 4B model, which does not rely on explicit 3D data inputs, achieves competitive results compared to existing state-of-the-art methods, and even surpasses the Gemini-1.5-Pro in the VSI-Bench evaluations.

[Arxiv](https://arxiv.org/abs/2505.24625)