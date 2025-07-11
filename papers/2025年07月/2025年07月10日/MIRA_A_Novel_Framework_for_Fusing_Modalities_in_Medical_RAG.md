# MIRA：医学 RAG 领域融合多模态的创新框架

发布时间：2025年07月10日

`RAG` `医学影像`

> MIRA: A Novel Framework for Fusing Modalities in Medical RAG

# 摘要

> 多模态大型语言模型（MLLMs）在AI辅助医学诊断领域取得了显著进展，但常会生成与医学知识相悖的事实性错误回答。基于检索增强生成（RAG）通过整合外部信息源提高了事实准确性，但面临两大关键挑战。首先，检索不足会遗漏关键信息，而过度检索则可能引入无关或误导性内容，干扰模型输出。其次，即使模型最初给出正确答案，过度依赖检索数据也可能导致事实错误。为解决这些问题，我们引入了多模态智能检索与增强框架（MIRA），旨在优化MLLM的事实准确性。MIRA包含两大核心组件：（1）校准式反思与重组模块，可动态调整检索上下文数量以控制事实风险；（2）医疗RAG框架，整合图像嵌入、医学知识库及查询重写模块，实现高效的多模态推理。这使模型能够有效结合自身知识与外部参考。我们对公开的医学VQA和报告生成基准测试的评估表明，MIRA显著提升了事实准确性和整体性能，达到了新的最优水平。代码已发布于https://github.com/mbzuai-oryx/MIRA。

> Multimodal Large Language Models (MLLMs) have significantly advanced AI-assisted medical diagnosis, but they often generate factually inconsistent responses that deviate from established medical knowledge. Retrieval-Augmented Generation (RAG) enhances factual accuracy by integrating external sources, but it presents two key challenges. First, insufficient retrieval can miss critical information, whereas excessive retrieval can introduce irrelevant or misleading content, disrupting model output. Second, even when the model initially provides correct answers, over-reliance on retrieved data can lead to factual errors. To address these issues, we introduce the Multimodal Intelligent Retrieval and Augmentation (MIRA) framework, designed to optimize factual accuracy in MLLM. MIRA consists of two key components: (1) a calibrated Rethinking and Rearrangement module that dynamically adjusts the number of retrieved contexts to manage factual risk, and (2) A medical RAG framework integrating image embeddings and a medical knowledge base with a query-rewrite module for efficient multimodal reasoning. This enables the model to effectively integrate both its inherent knowledge and external references. Our evaluation of publicly available medical VQA and report generation benchmarks demonstrates that MIRA substantially enhances factual accuracy and overall performance, achieving new state-of-the-art results. Code is released at https://github.com/mbzuai-oryx/MIRA.

[Arxiv](https://arxiv.org/abs/2507.07902)