# 为视频语言模型统一专用视觉编码器

发布时间：2025年01月02日

`LLM应用` `视觉处理`

> Unifying Specialized Visual Encoders for Video Language Models

# 摘要

> 最近，大型语言模型（LLMs）的问世，借由视频大型语言模型（VideoLLMs）将精妙的推理能力带进了视频领域。然而，当前的 VideoLLMs 在所有视觉处理上都依赖单一视觉编码器，这限制了能传递给 LLM 的视觉信息的数量和类型。我们的方法——MERV，即视频的多编码器表示，利用多个冻结的视觉编码器创建视频的统一表征，为 VideoLLM 提供一整套专门的视觉知识。对每个编码器的特征进行时空对齐，让我们能够应对更广泛的开放式和多项选择视频理解问题，并且超越了先前的前沿成果。在标准的视频理解基准测试中，MERV 的准确率比 Video-LLaVA 高出 3.7%，同时 Video-ChatGPT 得分也更优。我们还将之前在零样本感知测试准确率方面表现最佳的 SeViLA 提高了 2.2%。MERV 引入的额外参数极少，训练速度比同等的单编码器方法快，同时实现了视觉处理的并行化。最后，我们提供了定性证据，表明 MERV 成功地从每个编码器中获取了领域知识。我们的成果为利用多个视觉编码器实现全面的视频理解指明了充满希望的方向。

> The recent advent of Large Language Models (LLMs) has ushered sophisticated reasoning capabilities into the realm of video through Video Large Language Models (VideoLLMs). However, VideoLLMs currently rely on a single vision encoder for all of their visual processing, which limits the amount and type of visual information that can be conveyed to the LLM. Our method, MERV, Multi-Encoder Representation of Videos, instead leverages multiple frozen visual encoders to create a unified representation of a video, providing the VideoLLM with a comprehensive set of specialized visual knowledge. Spatio-temporally aligning the features from each encoder allows us to tackle a wider range of open-ended and multiple-choice video understanding questions and outperform prior state-of-the-art works. MERV is up to 3.7% better in accuracy than Video-LLaVA across the standard suite video understanding benchmarks, while also having a better Video-ChatGPT score. We also improve upon SeViLA, the previous best on zero-shot Perception Test accuracy, by 2.2%. MERV introduces minimal extra parameters and trains faster than equivalent single-encoder methods while parallelizing the visual processing. Finally, we provide qualitative evidence that MERV successfully captures domain knowledge from each of its encoders. Our results offer promising directions in utilizing multiple vision encoders for comprehensive video understanding.

[Arxiv](https://arxiv.org/abs/2501.01426)