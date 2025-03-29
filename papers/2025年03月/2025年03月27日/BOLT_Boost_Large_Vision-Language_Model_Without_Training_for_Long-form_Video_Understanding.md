# BOLT：无需训练，助力大型视觉-语言模型实现长视频理解突破

发布时间：2025年03月27日

`LLM应用

理由：这篇论文专注于大型视频语言模型（VLMs）在长视频分析中的应用，提出了BOLT方法来优化帧选择策略，提升模型性能。它属于语言模型的实际应用，因此归类为LLM应用。` `视频处理` `视频分析`

> BOLT: Boost Large Vision-Language Model Without Training for Long-form Video Understanding

# 摘要

> 大型视频语言模型（VLMs）在视频理解任务中表现突出，但在长视频分析中受限于上下文窗口的长度。传统方法如均匀帧采样常将资源浪费在无关内容上，影响实际效果。本文提出BOLT方法，通过研究帧选择策略，在不额外训练的情况下提升VLMs性能。首先，我们提出多源检索评估设置，更真实地评估VLMs在长视频理解中的能力。研究发现，均匀采样在复杂背景下表现欠佳，凸显了帧选择的重要性。其次，我们基于查询-帧相似度探索了多种帧选择策略，发现逆变换采样能显著提升性能，使Video-MME基准准确率从53.8%提升至56.1%，MLVU基准从58.9%提升至63.4%。我们的代码可在GitHub上获取：https://github.com/sming256/BOLT。

> Large video-language models (VLMs) have demonstrated promising progress in various video understanding tasks. However, their effectiveness in long-form video analysis is constrained by limited context windows. Traditional approaches, such as uniform frame sampling, often inevitably allocate resources to irrelevant content, diminishing their effectiveness in real-world scenarios. In this paper, we introduce BOLT, a method to BOost Large VLMs without additional Training through a comprehensive study of frame selection strategies. First, to enable a more realistic evaluation of VLMs in long-form video understanding, we propose a multi-source retrieval evaluation setting. Our findings reveal that uniform sampling performs poorly in noisy contexts, underscoring the importance of selecting the right frames. Second, we explore several frame selection strategies based on query-frame similarity and analyze their effectiveness at inference time. Our results show that inverse transform sampling yields the most significant performance improvement, increasing accuracy on the Video-MME benchmark from 53.8% to 56.1% and MLVU benchmark from 58.9% to 63.4%. Our code is available at https://github.com/sming256/BOLT.

[Arxiv](https://arxiv.org/abs/2503.21483)