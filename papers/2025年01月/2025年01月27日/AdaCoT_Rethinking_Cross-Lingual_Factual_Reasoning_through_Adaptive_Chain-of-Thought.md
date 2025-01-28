# AdaCoT: 自适应思维链下的跨语言事实推理新视角

发布时间：2025年01月27日

`LLM应用

理由：这篇论文提出了一个名为AdaCoT的框架，旨在通过动态路由思维过程来增强多语言推理能力，最终生成目标语言响应。这涉及到如何改进大型语言模型（LLMs）在多语言环境中的表现，特别是通过自适应推理路径来提升事实推理质量和跨语言一致性。因此，这篇论文属于LLM应用类别，因为它关注的是如何将LLMs应用于多语言推理任务，并提出了具体的改进方法。` `多语言系统`

> AdaCoT: Rethinking Cross-Lingual Factual Reasoning through Adaptive Chain-of-Thought

# 摘要

> 大型语言模型（LLMs）通过多样化语料库的预训练展现了强大的多语言能力。然而，由于训练数据分布不均，这些模型在不同语言中的表现差异显著。现有方法如机器翻译、多语言预训练和跨语言调优，不仅面临可扩展性挑战，还难以捕捉跨语言的细微推理过程。本文提出AdaCoT（自适应思维链）框架，通过动态路由思维过程，经由中间“思考语言”增强多语言推理，最终生成目标语言响应。AdaCoT采用语言无关的核心，并结合自适应奖励机制选择最佳推理路径，无需额外预训练。我们在多个基准测试中进行了全面评估，结果显示AdaCoT在事实推理质量和跨语言一致性上均有显著提升，尤其在低资源语言环境中表现尤为突出。这表明，自适应推理路径不仅能有效缩小高资源与低资源语言之间的性能差距，还能保留文化和语言的细微差异。

> Large language models (LLMs) have shown impressive multilingual capabilities through pretraining on diverse corpora. While these models show strong reasoning abilities, their performance varies significantly across languages due to uneven training data distribution. Existing approaches using machine translation, and extensive multilingual pretraining and cross-lingual tuning face scalability challenges and often fail to capture nuanced reasoning processes across languages. In this paper, we introduce AdaCoT (Adaptive Chain-of-Thought), a framework that enhances multilingual reasoning by dynamically routing thought processes through intermediary "thinking languages" before generating target-language responses. AdaCoT leverages a language-agnostic core and incorporates an adaptive, reward-based mechanism for selecting optimal reasoning pathways without requiring additional pretraining. Our comprehensive evaluation across multiple benchmarks demonstrates substantial improvements in both factual reasoning quality and cross-lingual consistency, with particularly strong performance gains in low-resource language settings. The results suggest that adaptive reasoning paths can effectively bridge the performance gap between high and low-resource languages while maintaining cultural and linguistic nuances.

[Arxiv](https://arxiv.org/abs/2501.16154)