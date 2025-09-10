# 预训练与大型语言模型时代下的查询扩展：综述

发布时间：2025年09月09日

`RAG` `零售与电商`

> Query Expansion in the Age of Pre-trained and Large Language Models: A Comprehensive Survey

# 摘要

> 现代信息检索（IR）需弥合简短模糊的查询与日益多样化、快速演变的语料库之间的鸿沟。查询扩展（QE）作为缓解词汇不匹配的核心机制，其设计空间已随预训练语言模型（PLMs）和大型语言模型（LLMs）的兴起发生显著转变。本综述从三个维度对该领域展开全面梳理：（i）查询扩展的四维框架——涵盖注入方式（显式与隐式QE）、基础与交互（知识库、模型内生能力、多轮检索）、学习对齐，直至基于知识图谱的论证；（ii）以模型为核心的分类体系，包括仅编码器、编码器-解码器、仅解码器、指令调优及领域/多语言变体，突出它们在QE中的独特优势（上下文消歧、可控生成、零/少样本推理）；（iii）神经QE的实践指南，阐明其在第一阶段检索、多查询融合、重排序及检索增强生成（RAG）中的应用场景与实现方式。我们从七个关键维度对比了传统QE与基于PLM/LLM的方法，并梳理了其在网络搜索、生物医学、电子商务、开放域问答/RAG、对话式与代码搜索及跨语言场景中的应用。综述提炼出设计基础与交互、对齐/蒸馏（SFT/PEFT/DPO）及知识图谱约束，将其作为解决主题漂移与幻觉问题的稳健方案。最后，我们提出未来研究方向，包括质量控制、成本感知调用、领域/时间适应性、超越终端任务指标的评估及公平性/隐私保护。这些洞见共同构成了在实际应用约束下选择与组合QE技术的系统性蓝图。

> Modern information retrieval (IR) must bridge short, ambiguous queries and ever more diverse, rapidly evolving corpora. Query Expansion (QE) remains a key mechanism for mitigating vocabulary mismatch, but the design space has shifted markedly with pre-trained language models (PLMs) and large language models (LLMs). This survey synthesizes the field from three angles: (i) a four-dimensional framework of query expansion - from the point of injection (explicit vs. implicit QE), through grounding and interaction (knowledge bases, model-internal capabilities, multi-turn retrieval) and learning alignment, to knowledge graph-based argumentation; (ii) a model-centric taxonomy spanning encoder-only, encoder-decoder, decoder-only, instruction-tuned, and domain/multilingual variants, highlighting their characteristic affordances for QE (contextual disambiguation, controllable generation, zero-/few-shot reasoning); and (iii) practice-oriented guidance on where and how neural QE helps in first-stage retrieval, multi-query fusion, re-ranking, and retrieval-augmented generation (RAG). We compare traditional query expansion with PLM/LLM-based methods across seven key aspects, and we map applications across web search, biomedicine, e-commerce, open-domain QA/RAG, conversational and code search, and cross-lingual settings. The review distills design grounding and interaction, alignment/distillation (SFT/PEFT/DPO), and KG constraints - as robust remedies to topic drift and hallucination. We conclude with an agenda on quality control, cost-aware invocation, domain/temporal adaptation, evaluation beyond end-task metrics, and fairness/privacy. Collectively, these insights provide a principled blueprint for selecting and combining QE techniques under real-world constraints.

[Arxiv](https://arxiv.org/abs/2509.07794)