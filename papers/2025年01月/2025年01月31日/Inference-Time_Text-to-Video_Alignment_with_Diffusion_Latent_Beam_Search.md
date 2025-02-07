# 推理时文本-视频对齐：基于扩散潜在波束搜索

发布时间：2025年01月31日

`其他

理由：这篇论文主要讨论的是文本到视频扩散模型的优化问题，特别是如何通过前瞻估计器和扩散潜在波束搜索方法来提升视频生成的感知质量。虽然提到了视觉语言模型作为人类代理评估输出，但整体内容并不直接涉及大型语言模型（LLM）的应用、理论、Agent或RAG（Retrieval-Augmented Generation）技术。因此，将其分类为“其他”更为合适。` `视频生成` `人工智能`

> Inference-Time Text-to-Video Alignment with Diffusion Latent Beam Search

# 摘要

> 文本到视频扩散模型的突破性进展使得生成的照片级真实感视频成为可能，尽管生成的视频内容常有不自然的运动、变形、反向播放和静止场景。最近，对齐问题备受关注，即根据内容质量指标引导扩散模型的输出。由于帧方向上的感知质量仍有很大提升空间，我们需要明确在视频生成中应优化哪些指标及如何优化。本文提出了一种带有前瞻估计器的扩散潜在波束搜索方法，能在推理时选择更优的扩散潜在以最大化对齐奖励。我们指出，提升感知视频质量需通过加权现有指标进行奖励校准。当使用视觉语言模型作为人类代理评估输出时，许多传统视频自然度指标并不总是与评估相关，且依赖于评估提示中的动态描述程度。我们证明，基于校准奖励的方法无需更新模型参数即可提升感知质量，并在与贪婪搜索和最佳N采样的对比中生成最佳结果。我们还提供了关于如何在反向扩散过程中分配推理时间计算的实用指南，涵盖搜索预算、奖励估计的前瞻步骤和去噪步骤。

> The remarkable progress in text-to-video diffusion models enables photorealistic generations, although the contents of the generated video often include unnatural movement or deformation, reverse playback, and motionless scenes. Recently, an alignment problem has attracted huge attention, where we steer the output of diffusion models based on some quantity on the goodness of the content. Because there is a large room for improvement of perceptual quality along the frame direction, we should address which metrics we should optimize and how we can optimize them in the video generation. In this paper, we propose diffusion latent beam search with lookahead estimator, which can select better diffusion latent to maximize a given alignment reward, at inference time. We then point out that the improvement of perceptual video quality considering the alignment to prompts requires reward calibration by weighting existing metrics. When evaluating outputs by using vision language models as a proxy of humans, many previous metrics to quantify the naturalness of video do not always correlate with evaluation and also depend on the degree of dynamic descriptions in evaluation prompts. We demonstrate that our method improves the perceptual quality based on the calibrated reward, without model parameter update, and outputs the best generation compared to greedy search and best-of-N sampling. We provide practical guidelines on which axes, among search budget, lookahead steps for reward estimate, and denoising steps, in the reverse diffusion process, we should allocate the inference-time computation.

[Arxiv](https://arxiv.org/abs/2501.19252)