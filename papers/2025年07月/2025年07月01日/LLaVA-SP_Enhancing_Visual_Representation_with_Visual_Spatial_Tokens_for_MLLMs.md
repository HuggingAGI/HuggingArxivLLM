# LLaVA-SP：通过视觉空间标记增强多模态大语言模型的视觉表示能力

发布时间：2025年07月01日

`LLM应用

理由：这篇论文讨论了多模态大型语言模型（MLLMs）的架构改进，特别是通过添加空间视觉标记来增强视觉表征。论文提出了具体的方法和模型变体，并展示了在多模态基准测试中的优越性能，属于LLM应用的范畴。` `计算机视觉`

> LLaVA-SP: Enhancing Visual Representation with Visual Spatial Tokens for MLLMs

# 摘要

> 多模态大型语言模型（MLLMs）的架构通常将视觉编码器（如CLIP-ViT）与语言模型结合。尽管CLIP-ViT擅长捕捉全局图像特征，但其在建模局部补丁关系上表现不足，导致视觉表征较弱，影响了MLLMs的细节理解能力。为解决这一问题，我们提出LLaVA-SP，仅通过在原始视觉标记中添加六个空间视觉标记来增强视觉表征。我们的方法有三大优势：1)我们设计了一种新型投影器，使用卷积核从ViT补丁特征中提取视觉空间标记，模拟``从中心到全局''和``从抽象到具体''两种空间排序方式。随后，通过交叉注意力机制融合细粒度视觉信息，提升整体视觉表征。2)我们提供了两种模型变体：LLaVA-SP-Cropping通过渐进式裁剪关注细节特征，而LLaVA-SP-Pooling则通过自适应池化捕获全局语义，使模型能够应对多样化的视觉理解任务。3)大量实验证明，经过LoRA微调的LLaVA-SP在多模态基准测试中表现优异，超越了现有LLaVA-1.5模型，且推理延迟相近。代码和模型已在\href{https://github.com/CnFaker/LLaVA-SP}{	exttt{https://github.com/CnFaker/LLaVA-SP}}开源。

> The architecture of multimodal large language models (MLLMs) commonly connects a vision encoder, often based on CLIP-ViT, to a large language model. While CLIP-ViT works well for capturing global image features, it struggles to model local relationships between adjacent patches, leading to weaker visual representation, which in turn affects the detailed understanding ability of MLLMs. To solve this, we propose LLaVA-SP, which \textbf{ only adds six spatial visual tokens} to the original visual tokens to enhance the visual representation. Our approach offers three key advantages: 1)We propose a novel Projector, which uses convolutional kernels to derive visual spatial tokens from ViT patch features, simulating two visual spatial ordering approaches: ``from central region to global" and ``from abstract to specific". Then, a cross-attention mechanism is applied to fuse fine-grained visual information, enriching the overall visual representation. 2) We present two model variants: LLaVA-SP-Cropping, which focuses on detail features through progressive cropping, and LLaVA-SP-Pooling, which captures global semantics through adaptive pooling, enabling the model to handle diverse visual understanding tasks. 3) Extensive experiments show that LLaVA-SP, fine-tuned with LoRA, achieves significant performance improvements across various multimodal benchmarks, outperforming the state-of-the-art LLaVA-1.5 model in multiple tasks with nearly identical inference latency. The code and models are available at \href{https://github.com/CnFaker/LLaVA-SP}{\texttt{https://github.com/CnFaker/LLaVA-SP}}.

[Arxiv](https://arxiv.org/abs/2507.00505)