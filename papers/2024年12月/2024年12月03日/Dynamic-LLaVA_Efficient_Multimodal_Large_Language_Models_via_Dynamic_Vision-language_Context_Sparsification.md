# Dynamic-LLaVA：借助动态视觉语言上下文稀疏化打造高效的多模态大型语言模型

发布时间：2024年12月03日

`LLM应用` `语言模型`

> Dynamic-LLaVA: Efficient Multimodal Large Language Models via Dynamic Vision-language Context Sparsification

# 摘要

> 多模态大型语言模型（MLLMs）在视觉理解、推理和交互领域成果斐然。但在解码时，随着输出标记的产生，推理计算量和内存逐步递增，直接影响了 MLLMs 的效率。现有方法试图降低视觉上下文的冗余来实现 MLLMs 的高效运行。可惜的是，在预填充阶段减少视觉上下文所带来的效率优势，在解码阶段逐渐弱化。为应对此问题，我们提出了动态视觉语言上下文稀疏化框架 Dynamic-LLaVA，它能在预填充阶段动态降低视觉上下文的冗余，并减少解码时生成的语言上下文的内存和计算开销。Dynamic-LLaVA 针对不同的推理模式（如预填充、有和没有 KV 缓存的解码）设计了专门的稀疏化推理方案，以实现 MLLMs 的高效推理。实际应用中，Dynamic-LLaVA 在预填充阶段能减少约 75％的计算量。同时，在 MLLMs 的整个生成过程中，Dynamic-LLaVA 在无 KV 缓存的解码下能减少约 50％的计算量，在有 KV 缓存的解码时能节省约 50％的 GPU 内存开销，这得益于视觉语言上下文的稀疏化。大量实验也表明，与全上下文推理基线相比，Dynamic-LLaVA 为 MLLMs 实现了高效推理，理解和生成能力的下降微乎其微，甚至还有性能提升。代码可在 https://github.com/Osilly/dynamic_llava 获取。

> Multimodal Large Language Models (MLLMs) have achieved remarkable success in vision understanding, reasoning, and interaction. However, the inference computation and memory increase progressively with the generation of output tokens during decoding, directly affecting the efficacy of MLLMs. Existing methods attempt to reduce the vision context redundancy to achieve efficient MLLMs. Unfortunately, the efficiency benefits of the vision context reduction in the prefill stage gradually diminish during the decoding stage. To address this problem, we proposed a dynamic vision-language context sparsification framework Dynamic-LLaVA, which dynamically reduces the redundancy of vision context in the prefill stage and decreases the memory and computation overhead of the generated language context during decoding. Dynamic-LLaVA designs a tailored sparsification inference scheme for different inference modes, i.e., prefill, decoding with and without KV cache, to achieve efficient inference of MLLMs. In practice, Dynamic-LLaVA can reduce computation consumption by $\sim$75\% in the prefill stage. Meanwhile, throughout the entire generation process of MLLMs, Dynamic-LLaVA reduces the $\sim$50\% computation consumption under decoding without KV cache, while saving $\sim$50\% GPU memory overhead when decoding with KV cache, due to the vision-language context sparsification. Extensive experiments also demonstrate that Dynamic-LLaVA achieves efficient inference for MLLMs with negligible understanding and generation ability degradation or even performance gains compared to the full-context inference baselines. Code is available at https://github.com/Osilly/dynamic_llava .

[Arxiv](https://arxiv.org/abs/2412.00876)