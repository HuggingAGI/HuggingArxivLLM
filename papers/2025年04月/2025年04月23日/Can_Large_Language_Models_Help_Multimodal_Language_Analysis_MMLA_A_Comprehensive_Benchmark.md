# # 摘要
大型语言模型能否助力多模态语言分析？MMLA：一个全面基准测试

发布时间：2025年04月23日

`LLM应用` `数据科学`

> Can Large Language Models Help Multimodal Language Analysis? MMLA: A Comprehensive Benchmark

# 摘要

> 多模态语言分析正迅速发展，它结合多种模态以更深入地理解人类对话中的高层次语义。尽管这一领域的重要性不言而喻，但目前少有研究关注多模态大型语言模型（MLLMs）在认知层面语义理解方面的能力。本文推出MMLA，这是一个专门设计的综合性基准测试，旨在填补这一研究空白。MMLA包含超过61,000个多模态 utterances，涵盖了 staged 和 real-world 场景，覆盖了多模态语义的六个核心维度：意图、情感、对话行为、情感倾向、说话风格和沟通行为。我们采用零-shot 推理、监督微调和指令调优三种方法，评估了八种主流的 LLMs 和 MLLMs。通过广泛的实验发现，即使是经过微调的模型，准确率也只有约60%~70%，这凸显了当前 MLLMs 在理解复杂人类语言方面的局限性。我们相信，MMLA 将为探索大型语言模型在多模态语言分析中的潜力奠定坚实基础，并为推动这一领域的发展提供宝贵的资源。数据集和代码已开源，地址为 https://github.com/thuiar/MMLA。


> Multimodal language analysis is a rapidly evolving field that leverages multiple modalities to enhance the understanding of high-level semantics underlying human conversational utterances. Despite its significance, little research has investigated the capability of multimodal large language models (MLLMs) to comprehend cognitive-level semantics. In this paper, we introduce MMLA, a comprehensive benchmark specifically designed to address this gap. MMLA comprises over 61K multimodal utterances drawn from both staged and real-world scenarios, covering six core dimensions of multimodal semantics: intent, emotion, dialogue act, sentiment, speaking style, and communication behavior. We evaluate eight mainstream branches of LLMs and MLLMs using three methods: zero-shot inference, supervised fine-tuning, and instruction tuning. Extensive experiments reveal that even fine-tuned models achieve only about 60%~70% accuracy, underscoring the limitations of current MLLMs in understanding complex human language. We believe that MMLA will serve as a solid foundation for exploring the potential of large language models in multimodal language analysis and provide valuable resources to advance this field. The datasets and code are open-sourced at https://github.com/thuiar/MMLA.

[Arxiv](https://arxiv.org/abs/2504.16427)