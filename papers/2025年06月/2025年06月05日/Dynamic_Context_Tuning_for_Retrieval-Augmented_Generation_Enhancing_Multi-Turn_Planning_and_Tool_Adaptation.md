# 动态上下文调优在检索增强生成中的应用：优化多轮规划与工具适配

发布时间：2025年06月05日

`RAG` `智能家居`

> Dynamic Context Tuning for Retrieval-Augmented Generation: Enhancing Multi-Turn Planning and Tool Adaptation

# 摘要

> 检索增强生成（RAG）通过与外部工具和知识来源结合，显著提升了大型语言模型（LLMs）的能力。然而，现有的RAG系统往往局限于静态单轮交互和固定的工具集，难以适应医疗和智能家居等动态领域，因为这些领域中用户意图、可用工具和上下文因素会随时间变化。我们提出了动态上下文调优（DCT），这是一个轻量级框架，支持多轮对话和动态工具环境，无需重新训练。DCT通过基于注意力的上下文缓存跟踪历史信息，利用LoRA检索动态选择特定领域工具，并采用高效压缩保持输入在模型上下文限制内。实验显示，DCT将计划准确率提升14%，幻觉减少37%，成本更低却接近GPT-4性能。此外，DCT能推广至新工具，在各种动态环境中实现灵活高效的人工智能助手。

> Retrieval-Augmented Generation (RAG) has significantly advanced large language models (LLMs) by grounding their outputs in external tools and knowledge sources. However, existing RAG systems are typically constrained to static, single-turn interactions with fixed toolsets, making them ill-suited for dynamic domains such as healthcare and smart homes, where user intent, available tools, and contextual factors evolve over time. We present Dynamic Context Tuning (DCT), a lightweight framework that extends RAG to support multi-turn dialogue and evolving tool environments without requiring retraining. DCT integrates an attention-based context cache to track relevant past information, LoRA-based retrieval to dynamically select domain-specific tools, and efficient context compression to maintain inputs within LLM context limits. Experiments on both synthetic and real-world benchmarks show that DCT improves plan accuracy by 14% and reduces hallucinations by 37%, while matching GPT-4 performance at significantly lower cost. Furthermore, DCT generalizes to previously unseen tools, enabling scalable and adaptable AI assistants across a wide range of dynamic environments.

[Arxiv](https://arxiv.org/abs/2506.11092)