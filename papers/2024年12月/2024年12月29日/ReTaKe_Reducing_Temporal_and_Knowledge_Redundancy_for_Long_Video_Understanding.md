# ReTaKe：为长视频理解降低时间和知识冗余

发布时间：2024年12月29日

`LLM应用` `人工智能`

> ReTaKe: Reducing Temporal and Knowledge Redundancy for Long Video Understanding

# 摘要

> 视频大型语言模型（VideoLLMs）在视频理解领域成果斐然。然而，现有的 VideoLLMs 通常会沿袭其骨干大型语言模型（LLMs）处理长序列的缺陷，致使长视频理解面临诸多难题。常见的解决办法要么单纯对视频帧进行均匀采样，要么压缩视觉标记，主要着眼于低级别的时间视觉冗余，却忽视了高级别的知识冗余。这就限制了在损失最小的情况下所能达到的压缩率。为此，我们推出了一种无需训练的方法——$	extbf{ReTaKe}$，它涵盖了两个新颖的模块 DPSelect 和 PivotKV，旨在共同对长视频理解中的时间视觉冗余和知识冗余进行建模与削减。具体而言，DPSelect 依据视觉特征识别出具有局部最大峰距的关键帧，这与人类的视频感知高度契合。PivotKV 把获取的关键帧当作枢轴，对注意力得分低的非枢轴标记进行 KV-Cache 压缩，这些得分源自 LLMs 学到的先验知识。在 VideoMME、MLVU 和 LVBench 等基准测试中的实验表明，ReTaKe 能够支持 4 倍更长的视频序列，性能损失极小（<1%），且比所有类似规模的 VideoLLMs 表现出色 3%-5%，甚至超越或与更大的模型旗鼓相当。我们的代码可在 https://github.com/SCZwangxiao/video-ReTaKe 获取。

> Video Large Language Models (VideoLLMs) have achieved remarkable progress in video understanding. However, existing VideoLLMs often inherit the limitations of their backbone LLMs in handling long sequences, leading to challenges for long video understanding. Common solutions either simply uniformly sample videos' frames or compress visual tokens, which focus primarily on low-level temporal visual redundancy, overlooking high-level knowledge redundancy. This limits the achievable compression rate with minimal loss. To this end. we introduce a training-free method, $\textbf{ReTaKe}$, containing two novel modules DPSelect and PivotKV, to jointly model and reduce both temporal visual redundancy and knowledge redundancy for long video understanding. Specifically, DPSelect identifies keyframes with local maximum peak distance based on their visual features, which are closely aligned with human video perception. PivotKV employs the obtained keyframes as pivots and conducts KV-Cache compression for the non-pivot tokens with low attention scores, which are derived from the learned prior knowledge of LLMs. Experiments on benchmarks VideoMME, MLVU, and LVBench, show that ReTaKe can support 4x longer video sequences with minimal performance loss (<1%) and outperform all similar-size VideoLLMs with 3%-5%, even surpassing or on par with much larger ones. Our code is available at https://github.com/SCZwangxiao/video-ReTaKe

[Arxiv](https://arxiv.org/abs/2412.20504)