# 为多模态大语言模型注入视频时空定位能力：SpaceVLLM

发布时间：2025年03月18日

`LLM应用` `视频处理` `计算机视觉`

> SpaceVLLM: Endowing Multimodal Large Language Model with Spatio-Temporal Video Grounding Capability

# 摘要

> 多模态大语言模型 (MLLMs) 在时空定位领域取得了显著进展，但在视频时空定位方面仍面临挑战。这一局限主要源于两大难题：首先，难以准确提取视频中每帧的时空信息；其次，大量视觉令牌使得难以精确将每帧的视觉令牌映射到其对应的空间坐标。为解决这些问题，我们提出了具备视频时空定位能力的多模态大语言模型 SpaceVLLM。具体而言，我们采用了一组交错的时空感知查询来捕捉时间感知和动态空间信息，并提出了一种查询引导的空间解码器，以在查询与空间坐标之间建立对应关系。此外，鉴于缺乏时空数据集，我们构建了包含三个任务、48 万实例的统一时空定位 (Uni-STG) 数据集，充分利用了 MLLM 的潜力，同时促进了时间和空间维度的定位。大量实验表明，SpaceVLLM 在涵盖时间、空间、时空和视频理解任务的 11 个基准测试中达到了最先进的性能，凸显了我们方法的有效性。我们的代码、数据集和模型即将开源。

> Multimodal large language models (MLLMs) have made remarkable progress in either temporal or spatial localization. However, they struggle to perform spatio-temporal video grounding. This limitation stems from two major challenges. Firstly, it is difficult to extract accurate spatio-temporal information of each frame in the video. Secondly, the substantial number of visual tokens makes it challenging to precisely map visual tokens of each frame to their corresponding spatial coordinates. To address these issues, we introduce SpaceVLLM, a MLLM endowed with spatio-temporal video grounding capability. Specifically, we adopt a set of interleaved Spatio-Temporal Aware Queries to capture temporal perception and dynamic spatial information. Moreover, we propose a Query-Guided Space Decoder to establish a corresponding connection between the queries and spatial coordinates. Additionally, due to the lack of spatio-temporal datasets, we construct the Unified Spatio-Temporal Grounding (Uni-STG) dataset, comprising 480K instances across three tasks. This dataset fully exploits the potential of MLLM to simultaneously facilitate localization in both temporal and spatial dimensions. Extensive experiments demonstrate that SpaceVLLM achieves the state-of-the-art performance across 11 benchmarks covering temporal, spatial, spatio-temporal and video understanding tasks, highlighting the effectiveness of our approach. Our code, datasets and model will be released.

[Arxiv](https://arxiv.org/abs/2503.13983)