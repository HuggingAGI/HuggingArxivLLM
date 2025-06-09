# SmoothRot: 通过融合通道级缩放与旋转，实现量化友好型大语言模型

发布时间：2025年06月04日

`LLM应用

摘要中的论文提出了一种新的后训练量化技术，SmoothRot，用于优化大型语言模型的量化效率。该技术通过结合通道缩放和Hadamard变换，解决了激活异常值的问题，从而提高了量化精度。实验结果表明，SmoothRot显著提升了量化模型的性能，缩小了与FP16模型的差距，并且没有增加推理延迟。这种技术属于模型优化和实际应用层面的改进，因此归类为LLM应用。` `人工智能` `机器学习`

> SmoothRot: Combining Channel-Wise Scaling and Rotation for Quantization-Friendly LLMs

# 摘要

> 我们推出了一种全新的后训练量化技术——SmoothRot，它能够显著提升大型语言模型（LLMs）中4位量化的效率。通过巧妙结合通道缩放与Hadamard变换，SmoothRot成功解决了大量激活异常值这一难题。该技术将极端异常值转化为更易量化的形式，从而大幅提升了量化精度。在LLaMA2 7B、LLaMA3.1 8B和Mistral 7B等流行模型上的实验结果表明，SmoothRot在语言生成和零样本推理任务中，将量化模型与FP16模型的性能差距缩小了约10-30%，并且不会增加推理延迟。代码已开源，地址为https://github.com/czakop/smoothrot。

> We present SmoothRot, a novel post-training quantization technique to enhance the efficiency of 4-bit quantization in Large Language Models (LLMs). SmoothRot addresses the critical challenge of massive activation outliers, by integrating channel-wise scaling with Hadamard transformations. Our technique effectively transforms extreme outliers into quantization-friendly activations, significantly improving quantization accuracy. Experiments conducted on popular LLMs (LLaMA2 7B, LLaMA3.1 8B, and Mistral 7B) demonstrate that SmoothRot consistently reduces the performance gap between quantized and FP16 models by approximately 10-30\% across language generation and zero-shot reasoning tasks, without introducing additional inference latency. Code is available at https://github.com/czakop/smoothrot.

[Arxiv](https://arxiv.org/abs/2506.05413)