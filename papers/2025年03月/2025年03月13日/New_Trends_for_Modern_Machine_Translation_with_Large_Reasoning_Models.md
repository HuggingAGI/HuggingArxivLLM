# # 新趋势：大型推理模型驱动的现代机器翻译

发布时间：2025年03月13日

`LLM应用

理由：这篇论文探讨了大型推理模型（LRMs）在机器翻译中的应用，特别是基于链式思维推理（CoT）的模型如何改变了翻译任务的处理方式。论文详细讨论了LRMs在翻译中的三个核心转变，展示了其在不同翻译任务中的卓越表现，并指出了相关挑战。这些内容属于大型语言模型在特定领域的实际应用，因此归类为“LLM应用”。` `机器翻译`

> New Trends for Modern Machine Translation with Large Reasoning Models

# 摘要

> 大型推理模型（LRMs）特别是基于链式思维推理（CoT）的模型，为机器翻译领域带来了革命性突破。本文认为，LRMs通过将翻译重新定义为需要上下文理解、文化推断和语言推理的动态任务，彻底改变了传统的神经机器翻译和基于LLMs的翻译范式。我们总结了三个核心转变：1）上下文连贯性，LRMs通过跨句推理和复杂场景分析解决模糊性，保持语篇结构；2）文化意图性，模型能够根据说话者意图、受众期望和社交语言规范调整输出；3）自我反思能力，LRMs在推理过程中能够主动识别并纠正翻译错误，尤其在处理高噪声文本时展现出更强的鲁棒性。我们通过实例展示了LRMs在风格化翻译、文档级翻译和多模态翻译中的卓越表现。同时，我们也指出LRMs在MT中的新现象和挑战，包括自动转译、过度本地化和推理效率问题。我们认为，LRMs重新定义了翻译系统，使其不仅是文本转换器，更是具备跨语言推理能力的智能代理。这种范式转变提醒我们，在更广泛的背景下思考翻译问题，借助LRMs实现超越传统翻译的更多可能性。


> Recent advances in Large Reasoning Models (LRMs), particularly those leveraging Chain-of-Thought reasoning (CoT), have opened brand new possibility for Machine Translation (MT). This position paper argues that LRMs substantially transformed traditional neural MT as well as LLMs-based MT paradigms by reframing translation as a dynamic reasoning task that requires contextual, cultural, and linguistic understanding and reasoning. We identify three foundational shifts: 1) contextual coherence, where LRMs resolve ambiguities and preserve discourse structure through explicit reasoning over cross-sentence and complex context or even lack of context; 2) cultural intentionality, enabling models to adapt outputs by inferring speaker intent, audience expectations, and socio-linguistic norms; 3) self-reflection, LRMs can perform self-reflection during the inference time to correct the potential errors in translation especially extremely noisy cases, showing better robustness compared to simply mapping X->Y translation. We explore various scenarios in translation including stylized translation, document-level translation and multimodal translation by showcasing empirical examples that demonstrate the superiority of LRMs in translation. We also identify several interesting phenomenons for LRMs for MT including auto-pivot translation as well as the critical challenges such as over-localisation in translation and inference efficiency. In conclusion, we think that LRMs redefine translation systems not merely as text converters but as multilingual cognitive agents capable of reasoning about meaning beyond the text. This paradigm shift reminds us to think of problems in translation beyond traditional translation scenarios in a much broader context with LRMs - what we can achieve on top of it.

[Arxiv](https://arxiv.org/abs/2503.10351)