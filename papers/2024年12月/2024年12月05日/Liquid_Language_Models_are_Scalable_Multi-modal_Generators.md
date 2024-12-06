# Liquid：语言模型是具有可扩展性的多模态生成器

发布时间：2024年12月05日

`LLM应用` `视觉语言` `多模态`

> Liquid: Language Models are Scalable Multi-modal Generators

# 摘要

> 我们推出了 Liquid 这一自回归生成范式，它能将图像标记为离散代码，并在用于视觉和语言的共享特征空间中，与文本标记一同学习这些代码嵌入，从而实现视觉理解与生成的无缝融合。和以往的多模态大型语言模型（MLLM）不同，Liquid 仅依靠单个大型语言模型（LLM）就达成了这种融合，无需像 CLIP 这类外部预训练的视觉嵌入。Liquid 首次发现了一个缩放规律，即随着模型规模增大，由视觉和语言任务统一训练所不可避免导致的性能下降会逐渐减少。而且，统一的标记空间能让视觉生成和理解任务相互促进，有效消除了早期模型常见的干扰。我们证明，现有的 LLM 能够成为 Liquid 的坚实基础，节省 100 倍的训练成本，在多模态能力上超越 Chameleon，同时语言性能与主流 LLM 如 LLAMA2 相当。Liquid 还优于 SD v2.1 和 SD-XL 等模型（在 MJHQ-30K 上的 FID 为 5.47），在视觉语言和纯文本任务中表现卓越。此项工作表明，像 LLAMA3.2 和 GEMMA2 这样的 LLM 是强大的多模态生成器，为提升视觉语言的理解和生成能力提供了可扩展的解决方案。代码和模型将会予以发布。

> We present Liquid, an auto-regressive generation paradigm that seamlessly integrates visual comprehension and generation by tokenizing images into discrete codes and learning these code embeddings alongside text tokens within a shared feature space for both vision and language. Unlike previous multimodal large language model (MLLM), Liquid achieves this integration using a single large language model (LLM), eliminating the need for external pretrained visual embeddings such as CLIP. For the first time, Liquid uncovers a scaling law that performance drop unavoidably brought by the unified training of visual and language tasks diminishes as the model size increases. Furthermore, the unified token space enables visual generation and comprehension tasks to mutually enhance each other, effectively removing the typical interference seen in earlier models. We show that existing LLMs can serve as strong foundations for Liquid, saving 100x in training costs while outperforming Chameleon in multimodal capabilities and maintaining language performance comparable to mainstream LLMs like LLAMA2. Liquid also outperforms models like SD v2.1 and SD-XL (FID of 5.47 on MJHQ-30K), excelling in both vision-language and text-only tasks. This work demonstrates that LLMs such as LLAMA3.2 and GEMMA2 are powerful multimodal generators, offering a scalable solution for enhancing both vision-language understanding and generation. The code and models will be released.

[Arxiv](https://arxiv.org/abs/2412.04332)