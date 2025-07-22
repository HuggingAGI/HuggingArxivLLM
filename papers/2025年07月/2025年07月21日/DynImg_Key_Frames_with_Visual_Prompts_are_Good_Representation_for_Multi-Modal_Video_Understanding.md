# DynImg：关键帧配视觉提示，助力多模态视频理解！

发布时间：2025年07月21日

`LLM应用` `视频理解` `视频处理`

> DynImg: Key Frames with Visual Prompts are Good Representation for Multi-Modal Video Understanding

# 摘要

> 近年来，多模态大语言模型（MLLMs）在视频理解任务中的应用日益普及。然而，如何有效整合时间信息仍是研究重点。传统方法将空间信息与时间信息分开处理，但由于运动模糊等问题，快速移动物体的空间信息难以准确表征。这可能导致在提取空间特征时，对时间上重要的区域关注不足，从而阻碍准确的空间-时间交互和视频理解。为解决这一限制，我们提出了一种创新的视频表示方法，名为动态图像（DynImg）。具体而言，我们引入一组非关键帧作为时间提示，以突出包含快速移动物体的空间区域。在视觉特征提取过程中，这些提示引导模型额外关注这些区域对应的细粒度空间特征。此外，为了保持DynImg的正确顺序，我们采用了相应的4D视频旋转位置嵌入。这保留了DynImg的时间和空间邻接性，帮助MLLM理解这种组合格式中的时空顺序。实验结果表明，与现有最优方法相比，DynImg在多个视频理解基准测试中提升了约2%的性能，证明了我们的时间提示在增强视频理解方面的有效性。

> In recent years, the introduction of Multi-modal Large Language Models (MLLMs) into video understanding tasks has become increasingly prevalent. However, how to effectively integrate temporal information remains a critical research focus. Traditional approaches treat spatial and temporal information separately. Due to issues like motion blur, it is challenging to accurately represent the spatial information of rapidly moving objects. This can lead to temporally important regions being underemphasized during spatial feature extraction, which in turn hinders accurate spatio-temporal interaction and video understanding. To address this limitation, we propose an innovative video representation method called Dynamic-Image (DynImg). Specifically, we introduce a set of non-key frames as temporal prompts to highlight the spatial areas containing fast-moving objects. During the process of visual feature extraction, these prompts guide the model to pay additional attention to the fine-grained spatial features corresponding to these regions. Moreover, to maintain the correct sequence for DynImg, we employ a corresponding 4D video Rotary Position Embedding. This retains both the temporal and spatial adjacency of DynImg, helping MLLM understand the spatio-temporal order within this combined format. Experimental evaluations reveal that DynImg surpasses the state-of-the-art methods by approximately 2% across multiple video understanding benchmarks, proving the effectiveness of our temporal prompts in enhancing video comprehension.

[Arxiv](https://arxiv.org/abs/2507.15569)