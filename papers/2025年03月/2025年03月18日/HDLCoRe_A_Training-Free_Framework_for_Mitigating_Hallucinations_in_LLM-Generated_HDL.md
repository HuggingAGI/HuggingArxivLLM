# HDLCoRe：无需训练，专为缓解LLM生成HDL中的幻觉问题而设计的框架。

发布时间：2025年03月18日

`RAG` `电子设计` `电子设计自动化`

> HDLCoRe: A Training-Free Framework for Mitigating Hallucinations in LLM-Generated HDL

# 摘要

> 大型语言模型（LLMs）在代码生成领域表现非凡，但面对硬件描述语言（HDL）时，数据稀缺性导致模型表现受限，常出现代码幻觉和生成错误。为突破这一瓶颈，我们提出无需训练的 HDLCoRe 框架，通过提示工程和增强型检索生成（RAG）技术提升 LLMs 的 HDL 生成能力。该框架包含两大核心组件：（1）一种基于复杂度和类型分类、融合领域知识并引导 LLMs 逐步自我模拟以实现错误修正的 HDL 感知链式思考（CoT）提示技术；（2）一个通过关键组件提取解决格式不一致问题，并通过顺序过滤和重排序高效检索相关 HDL 示例的两阶段异构 RAG 系统。HDLCoRe 消除了对模型微调的需求，显著提升了 LLMs 的 HDL 生成能力。实验结果表明，HDLCoRe 在 RTLLM2.0 基准测试中表现卓越，大幅减少了幻觉现象，同时显著提升了代码的语法和功能性正确性。

> Recent advances in large language models (LLMs) have demonstrated remarkable capabilities in code generation tasks. However, when applied to hardware description languages (HDL), these models exhibit significant limitations due to data scarcity, resulting in hallucinations and incorrect code generation. To address these challenges, we propose HDLCoRe, a training-free framework that enhances LLMs' HDL generation capabilities through prompt engineering techniques and retrieval-augmented generation (RAG). Our approach consists of two main components: (1) an HDL-aware Chain-of-Thought (CoT) prompting technique with self-verification that classifies tasks by complexity and type, incorporates domain-specific knowledge, and guides LLMs through step-by-step self-simulation for error correction; and (2) a two-stage heterogeneous RAG system that addresses formatting inconsistencies through key component extraction and efficiently retrieves relevant HDL examples through sequential filtering and re-ranking. HDLCoRe eliminates the need for model fine-tuning while substantially improving LLMs' HDL generation capabilities. Experimental results demonstrate that our framework achieves superior performance on the RTLLM2.0 benchmark, significantly reducing hallucinations and improving both syntactic and functional correctness.

[Arxiv](https://arxiv.org/abs/2503.16528)