# 幻觉评分：缓解生成图像超分辨率中的幻觉

发布时间：2025年07月18日

`LLM应用` `计算机视觉` `图像处理`

> Hallucination Score: Towards Mitigating Hallucinations in Generative Image Super-Resolution

# 摘要

> 生成式超级分辨率 (GSR) 在感知图像质量方面表现卓越，成功克服了传统非生成模型的“均值回归”模糊问题。然而，从人类视角来看，这类模型尚未实现质量与保真度的完美平衡。更值得关注的是，GSR 中存在一类关键却未被充分研究的 artifacts：生成的细节在感知上无法与低分辨率图像 (LRI) 或真实图像 (GTI) 匹配，这一问题严重限制了 GSR 的实际应用。本研究聚焦于测量、分析和缓解这些 artifacts（即“幻觉”）。我们发现，现有图像指标或质量模型无法有效表征幻觉，因为它们既不等同于精确保真度，也不同于无参考质量。为此，我们利用多模态大型语言模型 (MLLM)，构建了一个评估幻觉视觉元素的提示，并生成“幻觉分数” (HS)。研究发现，我们的 HS 与人工评估高度一致，同时为用于超级分辨率 (SR) 模型的先前图像指标提供了补充见解。此外，我们发现某些深度特征距离与 HS 具有强相关性。因此，我们提出利用这些特征作为可微奖励函数来对齐 GSR 模型，从而有效缓解幻觉问题。

> Generative super-resolution (GSR) currently sets the state-of-the-art in terms of perceptual image quality, overcoming the "regression-to-the-mean" blur of prior non-generative models. However, from a human perspective, such models do not fully conform to the optimal balance between quality and fidelity. Instead, a different class of artifacts, in which generated details fail to perceptually match the low resolution image (LRI) or ground-truth image (GTI), is a critical but under studied issue in GSR, limiting its practical deployments. In this work, we focus on measuring, analyzing, and mitigating these artifacts (i.e., "hallucinations"). We observe that hallucinations are not well-characterized with existing image metrics or quality models, as they are orthogonal to both exact fidelity and no-reference quality. Instead, we take advantage of a multimodal large language model (MLLM) by constructing a prompt that assesses hallucinatory visual elements and generates a "Hallucination Score" (HS). We find that our HS is closely aligned with human evaluations, and also provides complementary insights to prior image metrics used for super-resolution (SR) models. In addition, we find certain deep feature distances have strong correlations with HS. We therefore propose to align the GSR models by using such features as differentiable reward functions to mitigate hallucinations.

[Arxiv](https://arxiv.org/abs/2507.14367)