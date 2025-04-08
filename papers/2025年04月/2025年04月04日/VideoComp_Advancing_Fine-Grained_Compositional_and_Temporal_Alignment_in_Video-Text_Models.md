# VideoComp：致力于提升视频文本模型中的细粒度组合与时序对齐能力

发布时间：2025年04月04日

`其他` `视频处理` `多模态学习`

> VideoComp: Advancing Fine-Grained Compositional and Temporal Alignment in Video-Text Models

# 摘要

> 我们推出 VideoComp，一个全新的基准测试和学习框架，致力于推动视频文本组合性理解的发展，特别是在细粒度时间对齐方面。与现有专注于静态图像文本组合性或孤立单事件视频的基准不同，VideoComp 独具匠心地聚焦于连续多事件视频中的对齐问题。基于具有时间定位事件描述的视频文本数据集（如 ActivityNet-Captions 和 YouCook2），我们精心构建了两个组合性基准测试：ActivityNet-Comp 和 YouCook2-Comp。为了挑战模型的极限，我们设计了多种具有细微时间扰乱的负样本，包括重新排序、动作词替换、部分描述以及组合扰乱。这些基准测试全面评估了模型在处理扩展、连贯视频文本序列时的组合敏感性。

为了提升模型性能，我们提出了一种创新的层次化成对偏好损失，通过强化时间准确配对的对齐，并逐步惩罚日益紊乱的配对，从而激发模型进行细粒度的组合学习。为了解决密集标注视频数据有限的难题，我们引入了一种预训练策略，通过连接短视频描述对来模拟多事件序列。我们在 VideoComp 上评估了多种视频文本基础模型和大型多模态模型（LMMs），不仅发现了它们在组合性理解方面的优势，也识别出了有待改进的空间。总的来说，VideoComp 提供了一个全面的框架，用于评估和增强模型在实现细粒度、时间连贯的视频文本对齐方面的能力，为未来研究指明了方向。

> We introduce VideoComp, a benchmark and learning framework for advancing video-text compositionality understanding, aimed at improving vision-language models (VLMs) in fine-grained temporal alignment. Unlike existing benchmarks focused on static image-text compositionality or isolated single-event videos, our benchmark targets alignment in continuous multi-event videos. Leveraging video-text datasets with temporally localized event captions (e.g. ActivityNet-Captions, YouCook2), we construct two compositional benchmarks, ActivityNet-Comp and YouCook2-Comp. We create challenging negative samples with subtle temporal disruptions such as reordering, action word replacement, partial captioning, and combined disruptions. These benchmarks comprehensively test models' compositional sensitivity across extended, cohesive video-text sequences. To improve model performance, we propose a hierarchical pairwise preference loss that strengthens alignment with temporally accurate pairs and gradually penalizes increasingly disrupted ones, encouraging fine-grained compositional learning. To mitigate the limited availability of densely annotated video data, we introduce a pretraining strategy that concatenates short video-caption pairs to simulate multi-event sequences. We evaluate video-text foundational models and large multimodal models (LMMs) on our benchmark, identifying both strengths and areas for improvement in compositionality. Overall, our work provides a comprehensive framework for evaluating and enhancing model capabilities in achieving fine-grained, temporally coherent video-text alignment.

[Arxiv](https://arxiv.org/abs/2504.03970)