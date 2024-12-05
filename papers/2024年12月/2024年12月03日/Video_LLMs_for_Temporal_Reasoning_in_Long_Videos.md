# 用于长视频时间推理的视频大型语言模型

发布时间：2024年12月03日

`LLM应用` `视频处理`

> Video LLMs for Temporal Reasoning in Long Videos

# 摘要

> 本文引入了 TemporalVLM，这是一种能在长视频中实现有效时间推理和精细理解的视频大型语言模型。其核心在于，有一个视觉编码器，能把长期输入的视频转化为具有时间感知、包含本地和全局线索的特征。具体而言，它先把输入视频分割成短期片段，这些片段连同其时间戳一起被编码为对时间敏感的本地特征。接着，本地特征会通过双向长短期记忆模块进行全局特征聚合。所提取的具有时间感知和多层次的特征，对长视频中的准确时间推理和精细理解至关重要。另外，为助力 TemporalVLM 的评估，我们推出了一个大规模的工业装配过程长视频数据集——IndustryASM，它由工厂车间录制的视频构成，其中的动作和时间戳由工业工程师标注，用于时间和动作研究以及时间动作分割评估。最后，在包括 TimeIT 和 IndustryASM 在内的长视频数据集上开展的大量实验显示，在时间推理和精细理解任务（比如密集视频字幕、时间视频定位、视频亮点检测以及时间动作分割）方面，TemporalVLM 的表现优于以往的方法。

> This paper introduces TemporalVLM, a video large language model capable of effective temporal reasoning and fine-grained understanding in long videos. At the core, our approach includes a visual encoder for mapping a long-term input video into features which are time-aware and contain both local and global cues. In particular, it first divides the input video into short-term clips, which are jointly encoded with their timestamps into time-sensitive local features. Next, the local features are passed through a bidirectional long short-term memory module for global feature aggregation. The extracted time-aware and multi-level features are important for accurate temporal reasoning and fine-grained understanding in long videos. Moreover, to facilitate the evaluation of TemporalVLM, we present a large-scale long video dataset of industry assembly processes, namely IndustryASM, which consists of videos recorded on factory floors with actions and timestamps annotated by industrial engineers for time and motion studies and temporal action segmentation evaluation. Finally, extensive experiments on datasets of long videos, including TimeIT and IndustryASM, show that TemporalVLM achieves superior performance than previous methods across temporal reasoning and fine-grained understanding tasks, namely dense video captioning, temporal video grounding, video highlight detection, and temporal action segmentation.

[Arxiv](https://arxiv.org/abs/2412.02930)