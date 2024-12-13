# PVC：大型视觉语言模型中用于统一图像和视频处理的渐进式视觉标记压缩

发布时间：2024年12月12日

`LLM应用`

> PVC: Progressive Visual Token Compression for Unified Image and Video Processing in Large Vision-Language Models

# 摘要

> 大型视觉语言模型（VLMs）已能理解图像和视频。通过视觉标记压缩来缩短视觉输入的冗长标记。为满足不同任务需求，现有的高性能模型常以不同标记压缩策略分别处理图像和视频，这限制了图像与视频的结合能力。为此，我们把每个图像拓展成“静态”视频，并引入名为渐进式视觉标记压缩（PVC）的统一策略，逐步编码和自适应压缩每一帧的标记，以补充前一帧未提取的信息。利用内在的时间冗余高效压缩视频标记。图像重复为静态视频，空间细节能在多帧中逐步补充。PVC 统一了图像和视频的标记压缩。在每帧标记数量有限（默认 64 个）的情况下，仍能保留空间细节和时间变化。实验表明，我们的模型在各类视频理解基准测试中表现卓越，涵盖长视频任务和细粒度短视频任务。同时，我们的统一标记压缩策略在图像基准测试中不造成性能损失，尤其在细节敏感任务中。

> Large Vision-Language Models (VLMs) have been extended to understand both images and videos. Visual token compression is leveraged to reduce the considerable token length of visual inputs. To meet the needs of different tasks, existing high-performance models usually process images and videos separately with different token compression strategies, limiting the capabilities of combining images and videos. To this end, we extend each image into a "static" video and introduce a unified token compression strategy called Progressive Visual Token Compression (PVC), where the tokens of each frame are progressively encoded and adaptively compressed to supplement the information not extracted from previous frames. Video tokens are efficiently compressed with exploiting the inherent temporal redundancy. Images are repeated as static videos, and the spatial details can be gradually supplemented in multiple frames. PVC unifies the token compressing of images and videos. With a limited number of tokens per frame (64 tokens by default), spatial details and temporal changes can still be preserved. Experiments show that our model achieves state-of-the-art performance across various video understanding benchmarks, including long video tasks and fine-grained short video tasks. Meanwhile, our unified token compression strategy incurs no performance loss on image benchmarks, particularly in detail-sensitive tasks.

[Arxiv](https://arxiv.org/abs/2412.09613)