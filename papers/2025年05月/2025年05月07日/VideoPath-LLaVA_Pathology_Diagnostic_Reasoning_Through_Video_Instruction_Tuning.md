# # VideoPath-LLaVA：借助视频指令微调实现病理诊断推理

发布时间：2025年05月07日

`LLM应用` `多模态模型`

> VideoPath-LLaVA: Pathology Diagnostic Reasoning Through Video Instruction Tuning

# 摘要

> 我们推出 VideoPath-LLaVA，这是计算病理学领域首个整合三种图像场景的大规模多模态模型（LMM），包括单块图像、自动关键帧提取片段和手动分割的视频病理图像，旨在模拟病理学家的诊断流程。该模型通过生成详细组织学描述并最终得出确切诊断结论，实现了视觉叙事与诊断推理的结合。
    我们的核心创新是 VideoPath-Instruct 数据集，包含 4278 对视频和诊断相关的思维链指令对，源自 YouTube 上的教育性组织病理学视频。尽管高质量数据对提升诊断推理能力至关重要，但其创建过程耗时且数量有限。为此，我们提出了一种创新方法：首先从现有单图像指令数据集迁移知识，用于训练基于弱标注的关键帧提取片段，随后在手动分割的视频上进行微调。VideoPath-LLaVA 在病理视频分析领域树立了新标杆，为未来通过整合视觉与诊断推理支持临床决策的 AI 系统奠定了基础。我们的代码、数据和模型已公开发布，访问链接为 https://github.com/trinhvg/VideoPath-LLaVA。

> We present VideoPath-LLaVA, the first large multimodal model (LMM) in computational pathology that integrates three distinct image scenarios, single patch images, automatically keyframe-extracted clips, and manually segmented video pathology images, to mimic the natural diagnostic process of pathologists. By generating detailed histological descriptions and culminating in a definitive sign-out diagnosis, VideoPath-LLaVA bridges visual narratives with diagnostic reasoning.
  Central to our approach is the VideoPath-Instruct dataset, comprising 4278 video and diagnosis-specific chain-of-thought instructional pairs sourced from educational histopathology videos on YouTube. Although high-quality data is critical for enhancing diagnostic reasoning, its creation is time-intensive and limited in volume. To overcome this challenge, we transfer knowledge from existing single-image instruction datasets to train on weakly annotated, keyframe-extracted clips, followed by fine-tuning on manually segmented videos. VideoPath-LLaVA establishes a new benchmark in pathology video analysis and offers a promising foundation for future AI systems that support clinical decision-making through integrated visual and diagnostic reasoning. Our code, data, and model are publicly available at https://github.com/trinhvg/VideoPath-LLaVA.

[Arxiv](https://arxiv.org/abs/2505.04192)