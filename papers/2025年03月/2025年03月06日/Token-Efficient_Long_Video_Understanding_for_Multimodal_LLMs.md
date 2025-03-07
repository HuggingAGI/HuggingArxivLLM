# 高效利用token的长视频理解方法研究：面向多模态大语言模型

发布时间：2025年03月06日

`LLM应用` `视频理解` `计算机视觉`

> Token-Efficient Long Video Understanding for Multimodal LLMs

# 摘要

> 基于视频的多模态大语言模型（Video-LLMs）近期在视频理解领域取得了显著进展，通过将视频分解为图像帧序列进行处理。然而，现有方法在视觉主干中往往独立处理每一帧，缺乏显式的时间建模，这限制了它们捕捉动态模式和高效处理长视频的能力。为了解决这些局限，我们提出了STORM（	extbf{S}patiotemporal 	extbf{TO}ken 	extbf{R}eduction for 	extbf{M}ultimodal LLMs），一种在图像编码器与大语言模型之间引入专用时序编码器的创新架构。我们的时序编码器采用Mamba状态空间模型，将时间信息融入图像令牌，生成在整个视频序列中保留帧间动态的丰富表示。这种增强的编码不仅提升了视频推理能力，还支持多种有效的令牌缩减策略，包括测试时采样和基于训练的时间与空间池化，在保持关键时间信息的同时显著降低了大语言模型的计算负担。通过整合这些技术，我们的方法实现了训练和推理延迟的双重缩减，同时提升了性能，从而在长时间跨度内实现了高效且稳健的视频理解。实验结果表明，STORM在多个长视频理解基准测试中达到了领先水平（在MLVU和LongVideoBench上提升了超过5%），同时将计算成本降低了高达8倍，固定输入帧数下的解码延迟降低了2.4-2.9倍。项目页面可在https://research.nvidia.com/labs/lpr/storm访问。

> Recent advances in video-based multimodal large language models (Video-LLMs) have significantly improved video understanding by processing videos as sequences of image frames. However, many existing methods treat frames independently in the vision backbone, lacking explicit temporal modeling, which limits their ability to capture dynamic patterns and efficiently handle long videos. To address these limitations, we introduce STORM (\textbf{S}patiotemporal \textbf{TO}ken \textbf{R}eduction for \textbf{M}ultimodal LLMs), a novel architecture incorporating a dedicated temporal encoder between the image encoder and the LLM. Our temporal encoder leverages the Mamba State Space Model to integrate temporal information into image tokens, generating enriched representations that preserve inter-frame dynamics across the entire video sequence. This enriched encoding not only enhances video reasoning capabilities but also enables effective token reduction strategies, including test-time sampling and training-based temporal and spatial pooling, substantially reducing computational demands on the LLM without sacrificing key temporal information. By integrating these techniques, our approach simultaneously reduces training and inference latency while improving performance, enabling efficient and robust video understanding over extended temporal contexts. Extensive evaluations show that STORM achieves state-of-the-art results across various long video understanding benchmarks (more than 5\% improvement on MLVU and LongVideoBench) while reducing the computation costs by up to $8\times$ and the decoding latency by 2.4-2.9$\times$ for the fixed numbers of input frames. Project page is available at https://research.nvidia.com/labs/lpr/storm

[Arxiv](https://arxiv.org/abs/2503.04130)