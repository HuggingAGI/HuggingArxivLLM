# # Video-Bench：与人类对齐的视频生成基准

发布时间：2025年04月07日

`LLM应用` `计算机视觉`

> Video-Bench: Human-Aligned Video Generation Benchmark

# 摘要

> 视频生成评估是确保生成模型输出视觉真实、高质量且符合人类预期视频的关键环节。当前视频生成基准主要分为两类：传统基准通过指标和嵌入方法多维度评估视频质量，但常与人类判断不一致；基于大型语言模型（LLM）的基准虽能进行类人推理，却受限于对视频质量指标和跨模态一致性的理解。为解决这些问题并建立更符合人类偏好的基准，本文提出了Video-Bench——一个拥有丰富提示套件和广泛评估维度的综合基准。这是首次尝试在生成模型的所有相关视频生成评估维度上系统地利用多语言大型语言模型（MLLMs）。通过引入少量样本评分和查询链技术，Video-Bench提供了一种结构化、可扩展的生成视频评估方法。在包括Sora在内的先进模型上的实验表明，Video-Bench在所有维度上均实现了与人类偏好更优的对齐。此外，即使在我们的框架评估与人类评估出现分歧的情况下，它始终提供更客观和准确的见解，表明其相较于传统人工判断具有更大的潜在优势。

> Video generation assessment is essential for ensuring that generative models produce visually realistic, high-quality videos while aligning with human expectations. Current video generation benchmarks fall into two main categories: traditional benchmarks, which use metrics and embeddings to evaluate generated video quality across multiple dimensions but often lack alignment with human judgments; and large language model (LLM)-based benchmarks, though capable of human-like reasoning, are constrained by a limited understanding of video quality metrics and cross-modal consistency. To address these challenges and establish a benchmark that better aligns with human preferences, this paper introduces Video-Bench, a comprehensive benchmark featuring a rich prompt suite and extensive evaluation dimensions. This benchmark represents the first attempt to systematically leverage MLLMs across all dimensions relevant to video generation assessment in generative models. By incorporating few-shot scoring and chain-of-query techniques, Video-Bench provides a structured, scalable approach to generated video evaluation. Experiments on advanced models including Sora demonstrate that Video-Bench achieves superior alignment with human preferences across all dimensions. Moreover, in instances where our framework's assessments diverge from human evaluations, it consistently offers more objective and accurate insights, suggesting an even greater potential advantage over traditional human judgment.

[Arxiv](https://arxiv.org/abs/2504.04907)