# 引导式解码及其在检索增强生成中的关键作用

发布时间：2025年09月08日

`RAG` `基础理论`

> Guided Decoding and Its Critical Role in Retrieval-Augmented Generation

# 摘要

> 大型语言模型（LLMs）在各类应用中的整合，催生了对结构化、可靠响应的需求。检索增强生成（RAG）系统的一大核心挑战在于，如何确保输出符合预期格式，同时最大限度降低幻觉现象。本研究探讨引导解码在RAG系统中的作用，在0轮、1轮、2轮等不同多轮提示设置下，对比了Outlines、XGrammar和LM Format Enforcer三种方法。通过评估成功率、幻觉率及输出质量，我们深入分析了这些方法的性能表现与适用场景。研究结果揭示了多轮交互对引导解码的影响机制，还发现了意外的性能波动，这些发现可为特定场景下的方法选型提供依据。本研究深化了对RAG系统结构化输出生成的理解，为LLM的实际部署提供了兼具理论价值与实践意义的指导。

> The integration of Large Language Models (LLMs) into various applications has driven the need for structured and reliable responses. A key challenge in Retrieval-Augmented Generation (RAG) systems is ensuring that outputs align with expected formats while minimizing hallucinations. This study examines the role of guided decoding in RAG systems, comparing three methods, Outlines, XGrammar, and LM Format Enforcer, across different multi-turn prompting setups (0-turn, 1-turn, and 2-turn). By evaluating success rates, hallucination rates, and output quality, we provide insights into their performance and applicability. Our findings reveal how multi-turn interactions influence guided decoding, uncovering unexpected performance variations that can inform method selection for specific use cases. This work advances the understanding of structured output generation in RAG systems, offering both theoretical insights and practical guidance for LLM deployment.

[Arxiv](https://arxiv.org/abs/2509.06631)