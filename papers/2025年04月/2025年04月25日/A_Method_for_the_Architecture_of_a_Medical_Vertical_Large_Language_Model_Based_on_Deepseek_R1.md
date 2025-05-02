# 基于Deepseek R1的医疗垂直领域大型语言模型架构设计方法

发布时间：2025年04月25日

`LLM应用`

> A Method for the Architecture of a Medical Vertical Large Language Model Based on Deepseek R1

# 摘要

> 近年来，尽管DeepSeek-R1和ChatGPT等基础模型在通用任务中表现出色，但专业知识壁垒、计算资源需求和部署环境限制严重制约了它们在医疗领域的实际应用。本文针对这些挑战，提出了一种高效的轻量化医疗垂直大型语言模型架构方法，从知识获取、模型压缩和计算优化三个维度系统性地解决医疗大模型的轻量化问题。

在知识获取层面，我们设计了从微调后的DeepSeek-R1-Distill-70B教师模型到DeepSeek-R1-Distill-7B学生模型的知识迁移管道，并采用低秩适配（LoRA）技术精准调节关键注意力层。在模型压缩层面，实现了包括4位权重量化在内的压缩技术，同时保留了医疗推理的核心表示能力。在计算优化层面，集成了Flash Attention加速和连续批处理等推理优化技术，并构建了专业提示模板系统以适应不同类型医疗问题。

实验结果表明，本文提出的方法在保持专业准确性的同时，将内存消耗降低了64.7%，推理延迟降低了12.4%，为医疗大模型在边缘计算设备等资源受限环境中的应用提供了有效解决方案。

> In recent years, despite foundation models like DeepSeek-R1 and ChatGPT demonstrating significant capabilities in general tasks, professional knowledge barriers, computational resource requirements, and deployment environment limitations have severely hindered their application in actual medical scenarios. Addressing these challenges, this paper proposes an efficient lightweight medical vertical large language model architecture method, systematically solving the lightweight problem of medical large models from three dimensions: knowledge acquisition, model compression, and computational optimization. At the knowledge acquisition level, a knowledge transfer pipeline is designed from the fine-tuned DeepSeek-R1-Distill-70B teacher model to the DeepSeek-R1-Distill-7B student model, and Low-Rank Adaptation (LoRA) technology is adopted to precisely adjust key attention layers. At the model compression level, compression techniques including 4-bit weight quantization are implemented while preserving the core representation ability for medical reasoning. At the computational optimization level, inference optimization techniques such as Flash Attention acceleration and continuous batching are integrated, and a professional prompt template system is constructed to adapt to different types of medical problems. Experimental results on medical question-answering datasets show that the method proposed in this paper maintains professional accuracy while reducing memory consumption by 64.7\% and inference latency by 12.4\%, providing an effective solution for the application of medical large models in resource-constrained environments such as edge computing devices.

[Arxiv](https://arxiv.org/abs/2505.00025)