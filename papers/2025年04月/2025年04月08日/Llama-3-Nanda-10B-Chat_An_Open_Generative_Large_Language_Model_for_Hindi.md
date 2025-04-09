# Llama-3-Nanda-10B-Chat: 一个开放的生成式大型语言模型，专注于印地语

发布时间：2025年04月08日

`LLM应用

理由：这篇论文主要讨论了开发针对印地语的大型语言模型（LLM）的具体挑战和解决方案，包括模型架构、训练策略、数据处理以及模型的应用。这些内容属于LLM的应用层面，因此归类为LLM应用。` `印地语` `人工智能`

> Llama-3-Nanda-10B-Chat: An Open Generative Large Language Model for Hindi

# 摘要

> 开发高质量的大型语言模型（LLMs）对于中等资源语言而言，面临数据可用性、模型适配和评估方面的独特挑战。我们介绍了Llama-3-Nanda-10B-Chat，简称Nanda，一款以印地语为中心的指令微调生成型LLM，旨在突破开源印地语语言模型的边界。Nanda 基于 Llama-3-8B 构建，采用扩展的 Transformer 块进行持续预训练，并运用了 Llama Pro 方法论。一个关键挑战是高质量印地语文本数据的匮乏；我们通过严格的数据清洗、增强以及双语策略训练来应对这一问题，平衡印地语和英语语料库，以优化跨语言知识迁移。拥有100亿参数的Nanda跻身同类开源印地语和多语言模型的顶尖行列，相较于现有众多模型展现出显著优势。我们深入探讨了训练策略、微调技术、安全对齐以及评估指标，展示了这些方法如何助力Nanda实现 state-of-the-art 的成果。通过开源Nanda，我们致力于推动印地语LLMs的研究，并支持学术界、产业界及公共服务领域的广泛应用。

> Developing high-quality large language models (LLMs) for moderately resourced languages presents unique challenges in data availability, model adaptation, and evaluation. We introduce Llama-3-Nanda-10B-Chat, or Nanda for short, a state-of-the-art Hindi-centric instruction-tuned generative LLM, designed to push the boundaries of open-source Hindi language models. Built upon Llama-3-8B, Nanda incorporates continuous pre-training with expanded transformer blocks, leveraging the Llama Pro methodology. A key challenge was the limited availability of high-quality Hindi text data; we addressed this through rigorous data curation, augmentation, and strategic bilingual training, balancing Hindi and English corpora to optimize cross-linguistic knowledge transfer. With 10 billion parameters, Nanda stands among the top-performing open-source Hindi and multilingual models of similar scale, demonstrating significant advantages over many existing models. We provide an in-depth discussion of training strategies, fine-tuning techniques, safety alignment, and evaluation metrics, demonstrating how these approaches enabled Nanda to achieve state-of-the-art results. By open-sourcing Nanda, we aim to advance research in Hindi LLMs and support a wide range of real-world applications across academia, industry, and public services.

[Arxiv](https://arxiv.org/abs/2504.06011)