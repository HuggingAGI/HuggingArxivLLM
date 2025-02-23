# 幻觉与真相：对 RAG、LoRA 和 DoRA 的全面准确性评估

发布时间：2025年02月14日

`LLM应用` `生成式AI`

> Hallucinations and Truth: A Comprehensive Accuracy Evaluation of RAG, LoRA and DoRA

# 摘要

> 生成式AI的最新进展显著提升了自然语言处理（NLP）系统的效率和适应性，特别是在检索增强生成（RAG）、低秩适配（LoRA）和权重分解低秩适配（DoRA）方面。RAG通过整合外部知识来提高生成输出的事实一致性，而LoRA则实现了大型语言模型（LLMs）的参数高效微调。DoRA进一步优化了这一过程，通过自适应参数排序和领域感知权重调整来优化微调，同时保持推理性能，提高学习效率。

本文对RAG、LoRA和DoRA进行了大规模的实证评估，基于20,000个基于FAQ的查询评估了模型微调和生成性能，知识库涵盖400,000个条目。研究分析了准确性、相关性和推理延迟等关键性能指标。实验结果表明，DoRA在准确性（90.1%）、相关性得分（0.88）和延迟（每查询110毫秒）方面均达到最高水平，优于LoRA和RAG，在特定领域的真实世界生成式AI应用中表现出色。

此外，本研究探讨了不同模型在微调效率、计算成本和实时适应性之间的权衡。研究发现，RAG在知识基础方面表现出色，LoRA在领域适应方面具有成本效益，而DoRA则能够平衡微调效率与模型精度。这些见解为在医疗、金融和法律服务等准确性关键领域部署AI驱动的生成系统提供了实用指导，确保在动态环境中实现可扩展性、可靠性和最佳性能。


> Recent advancements in Generative AI have significantly improved the efficiency and adaptability of natural language processing (NLP) systems, particularly through Retrieval-Augmented Generation (RAG), Low-Rank Adaptation (LoRA), and Weight-Decomposed Low-Rank Adaptation (DoRA). RAG integrates external knowledge to enhance factual consistency in generative outputs, while LoRA enables parameter-efficient fine-tuning of large language models (LLMs). DoRA further refines this process by optimizing fine-tuning through adaptive parameter ranking and domain-aware weight adjustments, improving learning efficiency while maintaining inference performance.
  This paper presents a large-scale empirical evaluation of RAG, LoRA, and DoRA, with model fine-tuning and generation performance assessed on 20,000 FAQ-based queries, while the knowledge base spans 400,000 entries. The study analyzes key performance metrics such as accuracy, relevance, and inference latency. Experimental results demonstrate that DoRA achieves the highest accuracy (90.1%), relevance score (0.88), and lowest latency (110 ms per query), outperforming both LoRA and RAG in real-world, domain-specific generative AI applications.
  Furthermore, this study examines the trade-offs between fine-tuning efficiency, computational cost, and real-time adaptability across different models. Findings highlight RAG's effectiveness in knowledge grounding, LoRA's cost-efficient domain adaptation, and DoRA's ability to balance fine-tuning efficiency with model precision. These insights provide practical guidance for deploying AI-driven generative systems in accuracy-critical domains such as healthcare, finance, and legal services, ensuring scalability, reliability, and optimal performance in dynamic environments.

[Arxiv](https://arxiv.org/abs/2502.10497)