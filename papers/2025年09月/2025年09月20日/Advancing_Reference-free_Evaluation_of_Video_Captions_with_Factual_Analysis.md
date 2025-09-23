# 基于事实分析优化视频描述的无参考评估

发布时间：2025年09月20日

`LLM应用` `媒体与娱乐`

> Advancing Reference-free Evaluation of Video Captions with Factual Analysis

# 摘要

> 视频字幕能简洁呈现视频中的人物、物体与动作，是问答、事件定位等应用的重要资源。然而，获取视频字幕的人工标注成本高昂，有时甚至不切实际，尤其在面对多样化视频领域时。现有基于有监督数据训练的模型在跨领域性能评估中面临挑战，原因是它们依赖于需要真实字幕的参考型评估协议，而这种假设在评估真实场景视频时并不现实。为解决这些问题，我们提出了一种无需真实字幕的无参考评估框架，通过聚焦事实依据来准确评估字幕质量。我们提出了VC-Inspector——一种兼具无参考性与事实依据的新型字幕质量评估器。我们利用大型语言模型，基于有监督数据生成不同质量的伪字幕，进而训练多模态模型（如Qwen2.5-VL）作为评估器。在VATEX-Eval数据集上，我们的方法与人类判断的一致性显著优于现有方法。若将图像视作单帧视频，该性能还可推广至图像字幕数据集Flickr8K-Expert与Flickr8K-CF。综上，VC-Inspector为评估视频字幕的事实准确性提供了可扩展、可推广的解决方案，为多样化视频领域构建更高效、客观的评估方法奠定了基础。

> Video captions offer concise snapshots of actors, objects, and actions within a video, serving as valuable assets for applications such as question answering and event localization. However, acquiring human annotations for video captions is costly or even impractical, especially when dealing with diverse video domains. Existing models trained on supervised datasets face challenges in evaluating performance across different domains due to the reliance on reference-based evaluation protocols, which necessitate ground truth captions. This assumption is unrealistic for evaluating videos in the wild. To address these limitations, we propose a reference-free evaluation framework that does not require ground truth captions, focusing on factual grounding to ensure accurate assessment of caption quality. We introduce VC-Inspector, a novel caption quality evaluator that is both reference-free and factually grounded. Utilizing large language models, we generate pseudo captions of varying quality based on supervised data, which are subsequently used to train a multimodal model (i.e., Qwen2.5-VL) as the evaluator. Our approach demonstrates superior alignment with human judgments on the VATEX-Eval dataset, outperforming existing methods. The performance also generalizes to image caption datasets, Flickr8K-Expert and Flickr8K-CF, when viewing images as 1-frame videos. Overall, VC-Inspector offers a scalable and generalizable solution for evaluating the factual accuracy of video captions, paving the way for more effective and objective assessment methodologies in diverse video domains.

[Arxiv](https://arxiv.org/abs/2509.16538)