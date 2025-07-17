# AutoRAG-LoRA：轻量级适配器驱动的幻觉触发知识再调优

发布时间：2025年07月11日

`RAG` `信息检索` `问答系统`

> AutoRAG-LoRA: Hallucination-Triggered Knowledge Retuning via Lightweight Adapters

# 摘要

> 大型语言模型（LLMs）在各类自然语言任务中展现出卓越的流畅性，但其生成内容中的幻觉问题（事实性错误）却严重阻碍了实际应用中的信任度。我们提出了一种名为AutoRAG-LoRA的模块化检索增强生成（RAG）框架，通过轻量级的基于LoRA的适配器和KL正则化训练有效解决大型语言模型中的幻觉问题。该框架整合了自动提示重写、混合检索和低秩适配器调优技术，确保生成内容基于可靠检索证据。此外，我们设计了一个幻觉检测模块，采用分类器与自评估相结合的方法，为生成输出分配置信度评分，并可触发反馈修正循环，通过对比KL损失和适配器微调实现事实对齐。实验结果表明，AutoRAG-LoRA显著降低了事实偏差，同时保持了模型的高效性和模块化优势。

> Large Language Models (LLMs) have demonstrated remarkable fluency across a range of natural language tasks, yet remain vulnerable to hallucinations - factual inaccuracies that undermine trust in real world deployment. We present AutoRAG-LoRA, a modular framework for Retrieval-Augmented Generation (RAG) that tackles hallucination in large language models through lightweight LoRA-based adapters and KL-regularized training. Our pipeline integrates automated prompt rewriting, hybrid retrieval, and low-rank adapter tuning to ground responses in retrieved evidence. A hallucination detection module, using both classifier-based and self-evaluation techniques, assigns confidence scores to generated outputs, triggering an optional feedback correction loop. This loop enforces factual alignment via contrastive KL loss and adapter fine tuning. We demonstrate that AutoRAG-LoRA significantly reduces the factual drift while preserving the efficiency and modularity of the model.

[Arxiv](https://arxiv.org/abs/2507.10586)