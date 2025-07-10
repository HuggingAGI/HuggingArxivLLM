# 通过任务驱动的 Stable Diffusion 实现多模态理解

发布时间：2025年07月09日

`LLM应用` `视觉问答` `多模态模型`

> Towards Multimodal Understanding via Stable Diffusion as a Task-Aware Feature Extractor

# 摘要

> 多模态大语言模型（MLLMs）的最新进展使基于图像的问答成为可能。然而，使用CLIP作为视觉编码器存在一个关键限制：它虽能捕获全局信息，却常遗漏与输入查询相关的细节。本研究探讨了预训练的文本到图像扩散模型是否可作为指令感知的视觉编码器。通过分析其内部表示，我们发现扩散特征在语义上丰富且能实现强大的图像-文本对齐。此外，我们发现可通过文本条件控制，使模型关注与输入问题相关的区域。随后，我们研究了如何将这些特征与大语言模型对齐，并发现了一种信息泄漏现象：大语言模型可无意中从原始扩散提示中恢复信息。我们分析了泄漏原因并提出了解决策略。基于这些发现，我们提出了一种简单的融合策略，结合CLIP和条件扩散特征。我们在通用VQA和专门的MLLM基准上评估了方法，展示了扩散模型在视觉理解，特别是在需要空间和组合推理的视觉核心任务中的潜力。项目页面：https://vatsalag99.github.io/mustafar/。

> Recent advances in multimodal large language models (MLLMs) have enabled image-based question-answering capabilities. However, a key limitation is the use of CLIP as the visual encoder; while it can capture coarse global information, it often can miss fine-grained details that are relevant to the input query. To address these shortcomings, this work studies whether pre-trained text-to-image diffusion models can serve as instruction-aware visual encoders. Through an analysis of their internal representations, we find diffusion features are both rich in semantics and can encode strong image-text alignment. Moreover, we find that we can leverage text conditioning to focus the model on regions relevant to the input question. We then investigate how to align these features with large language models and uncover a leakage phenomenon, where the LLM can inadvertently recover information from the original diffusion prompt. We analyze the causes of this leakage and propose a mitigation strategy. Based on these insights, we explore a simple fusion strategy that utilizes both CLIP and conditional diffusion features. We evaluate our approach on both general VQA and specialized MLLM benchmarks, demonstrating the promise of diffusion models for visual understanding, particularly in vision-centric tasks that require spatial and compositional reasoning. Our project page can be found https://vatsalag99.github.io/mustafar/.

[Arxiv](https://arxiv.org/abs/2507.07106)