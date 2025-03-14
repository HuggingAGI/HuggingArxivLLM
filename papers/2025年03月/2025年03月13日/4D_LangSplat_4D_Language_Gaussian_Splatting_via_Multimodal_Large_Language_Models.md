# # 4D LangSplat：通过多模态大语言模型实现4D语言高斯体素化

发布时间：2025年03月13日

`LLM应用` `视频处理` `多模态处理`

> 4D LangSplat: 4D Language Gaussian Splatting via Multimodal Large Language Models

# 摘要

> 学习4D语言场，实现在动态场景中进行时间敏感和开放性语言查询，对许多现实应用至关重要。尽管LangSplat成功将CLIP特征嵌入3D高斯表示，并在静态3D场景中表现出色，但它无法处理动态4D场，因为CLIP专为静态图像-文本任务设计，无法捕捉视频的时间动态。现实环境动态多变，物体语义随时间演变。构建精准4D语言场需获取像素对齐的基于物体视频特征，但现有视觉模型难以实现。为此，我们提出4D LangSplat，学习4D语言场，高效处理动态场景中的开放词汇查询。4D LangSplat跳过从视觉特征学习语言场的步骤，直接从多模态大型语言模型（MLLMs）生成的基于物体视频描述文本中学习。具体而言，我们提出了一种多模态基于物体的视频提示方法，包含视觉和文本提示，引导MLLMs生成详细、时间一致、高质量的物体描述。这些描述通过大型语言模型编码为高质量句子嵌入，作为像素对齐的基于物体特征监督，通过共享嵌入空间实现开放词汇文本查询。鉴于4D场景中物体状态间平滑过渡，我们进一步提出状态可变形网络，有效建模随时间的连续变化。多个基准测试结果表明，4D LangSplat在时间敏感和时间无关的开放词汇查询中均表现精准高效。

> Learning 4D language fields to enable time-sensitive, open-ended language queries in dynamic scenes is essential for many real-world applications. While LangSplat successfully grounds CLIP features into 3D Gaussian representations, achieving precision and efficiency in 3D static scenes, it lacks the ability to handle dynamic 4D fields as CLIP, designed for static image-text tasks, cannot capture temporal dynamics in videos. Real-world environments are inherently dynamic, with object semantics evolving over time. Building a precise 4D language field necessitates obtaining pixel-aligned, object-wise video features, which current vision models struggle to achieve. To address these challenges, we propose 4D LangSplat, which learns 4D language fields to handle time-agnostic or time-sensitive open-vocabulary queries in dynamic scenes efficiently. 4D LangSplat bypasses learning the language field from vision features and instead learns directly from text generated from object-wise video captions via Multimodal Large Language Models (MLLMs). Specifically, we propose a multimodal object-wise video prompting method, consisting of visual and text prompts that guide MLLMs to generate detailed, temporally consistent, high-quality captions for objects throughout a video. These captions are encoded using a Large Language Model into high-quality sentence embeddings, which then serve as pixel-aligned, object-specific feature supervision, facilitating open-vocabulary text queries through shared embedding spaces. Recognizing that objects in 4D scenes exhibit smooth transitions across states, we further propose a status deformable network to model these continuous changes over time effectively. Our results across multiple benchmarks demonstrate that 4D LangSplat attains precise and efficient results for both time-sensitive and time-agnostic open-vocabulary queries.

[Arxiv](https://arxiv.org/abs/2503.10437)