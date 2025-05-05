# # PolyPath: 针对多幻灯片病理报告生成任务，适应大型多模态模型

发布时间：2025年02月14日

`LLM应用` `计算病理学`

> PolyPath: Adapting a Large Multimodal Model for Multi-slide Pathology Report Generation

# 摘要

> 对病理切片的解读在医学诊断和治疗决策中至关重要。通常，病理学家需要整合和总结每例病例中多张切片的发现。然而，目前计算病理学中的视觉-语言能力主要局限于小区域兴趣点、低倍镜下的较大区域或单张全切片图像（WSIs）。这种局限性限制了对跨越多张 WSIs 上多个高倍镜区域的发现的解读。

借助 Gemini 1.5 Flash——一款具有 100 万令牌上下文窗口的大型多模态模型 (LMM)，我们展示了从多张 10 倍放大 WSIs 中的多达 40,000 张 768x768 像素图像补丁生成最终诊断的能力。这相当于以 1 fps 的速度播放长达 11 小时的视频。专家病理学家的评估表明，生成的报告文本在临床上准确，并且对于包含多达 5 张切片的 68% 的多切片示例（95% CI：[60%，76%]），生成的报告与原始报告相当或更优。

虽然对于包含 6 张或更多切片的示例性能有所下降，但本研究表明，利用现代 LMM 的长上下文能力在医学报告生成这一极具挑战性的任务中具有潜力，因为每个病例可能包含数千张图像补丁。

> The interpretation of histopathology cases underlies many important diagnostic and treatment decisions in medicine. Notably, this process typically requires pathologists to integrate and summarize findings across multiple slides per case. Existing vision-language capabilities in computational pathology have so far been largely limited to small regions of interest, larger regions at low magnification, or single whole-slide images (WSIs). This limits interpretation of findings that span multiple high-magnification regions across multiple WSIs. By making use of Gemini 1.5 Flash, a large multimodal model (LMM) with a 1-million token context window, we demonstrate the ability to generate bottom-line diagnoses from up to 40,000 768x768 pixel image patches from multiple WSIs at 10X magnification. This is the equivalent of up to 11 hours of video at 1 fps. Expert pathologist evaluations demonstrate that the generated report text is clinically accurate and equivalent to or preferred over the original reporting for 68% (95% CI: [60%, 76%]) of multi-slide examples with up to 5 slides. While performance decreased for examples with 6 or more slides, this study demonstrates the promise of leveraging the long-context capabilities of modern LMMs for the uniquely challenging task of medical report generation where each case can contain thousands of image patches.

[Arxiv](https://arxiv.org/abs/2502.10536)